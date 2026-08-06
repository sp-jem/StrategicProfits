# Complete Facebook Ads Launch Checklist

Complete these before Session 16. No ads run without them. This is the full technical checklist -- not just the assets, but everything Meta requires before your first ad can go live.

---

## PHASE 1: BUSINESS MANAGER FOUNDATION

### Account Setup
- [ ] Business Manager account created at business.facebook.com
- [ ] Business name matches your legal business name
- [ ] Two-factor authentication (2FA) enabled on your personal Facebook account
- [ ] Payment method added (Settings > Payment Methods > credit card or PayPal)
- [ ] Spending limit set for testing (recommended: start at $500/month while learning)

### Facebook Page
- [ ] Facebook Business Page connected to your Business Manager
- [ ] Page has a profile photo (your headshot or logo)
- [ ] Page has a cover photo
- [ ] "About" section filled out with your business description
- [ ] At least 1 post published on the page (Meta may flag brand-new pages with zero content)

### Domain Verification
- [ ] Your website domain verified in Business Manager (Settings > Brand Safety > Domains)
- [ ] Verification method completed (DNS TXT record, HTML file upload, or meta tag)
- [ ] Why this matters: Required for full conversion tracking, link editing in ads, and Aggregated Event Measurement

**How to verify:** Add a DNS TXT record through your domain registrar (GoDaddy, Namecheap, Cloudflare, etc.), OR upload an HTML file to your site root, OR add a meta tag to your homepage `<head>`. Claude can walk you through whichever method fits your hosting setup.

---

## PHASE 2: LANDING PAGE + THANK YOU PAGE

### Landing Page (the page your ad sends people to)
- [ ] Landing page LIVE at a working URL
- [ ] Page loads in under 3 seconds on mobile
- [ ] Mobile-responsive (test on your phone)
- [ ] Headline matches your ad copy (Meta checks for consistency)
- [ ] Clear call-to-action (opt-in form, button, etc.)
- [ ] **Privacy Policy link** visible on the page (REQUIRED -- Meta will reject ads without this)
- [ ] Business contact information accessible (email or contact page)
- [ ] No fake urgency, fake scarcity, or misleading claims (triggers ad rejection)

### Thank You Page (the page people see AFTER they opt in / purchase)
- [ ] Thank you page exists as a **separate URL** (e.g., yoursite.com/thank-you) -- NOT a popup or inline message
- [ ] Thank you page confirms the action ("Thanks! Check your email for your download")
- [ ] Thank you page URL is different from your landing page URL

**Why a separate thank you page matters:** This is how Meta tracks conversions. The pixel fires a "Lead" or "Purchase" event when someone lands on your thank you page URL. If you only show a popup on the same page, the pixel has no way to distinguish someone who converted from someone who just visited. A separate URL = trackable conversion.

**Quick setup:** Most landing page builders (Carrd, Leadpages, ClickFunnels, Systeme.io) let you set a "thank you page" or "success page" URL. Point your form submission to redirect to that URL.

---

## PHASE 3: PIXEL + CONVERSION TRACKING

### Create and Install the Meta Pixel
- [ ] Pixel created in Events Manager (Events Manager > Connect Data Sources > Web > Meta Pixel)
- [ ] Pixel named clearly (e.g., "[Your Business] Pixel")
- [ ] Pixel base code installed on **ALL pages** of your site (landing page AND thank you page)

**Installation options:**
- **Manual:** Paste pixel base code in `<head>` section of every page
- **Partner Integration:** WordPress (Facebook for WordPress plugin), Shopify (built-in Facebook channel), Squarespace (Settings > Advanced > Code Injection), Wix (Marketing Integrations > Facebook Pixel), Carrd (add embed in head)
- **Google Tag Manager:** Create new tag > Custom HTML > paste pixel code > trigger on All Pages

### Configure Conversion Events

This is the critical part most beginners miss. The pixel base code fires "PageView" on every page automatically. But you need SPECIFIC events on specific pages:

| Event | Where It Fires | What It Tracks | Code |
|-------|----------------|----------------|------|
| PageView | Every page (automatic) | Someone visited your site | Fires automatically with base pixel |
| ViewContent | Landing page | Someone saw your offer | `fbq('track', 'ViewContent');` |
| **Lead** | **Thank you page ONLY** | **Someone opted in** | `fbq('track', 'Lead');` |
| **Purchase** | **Order confirmation page ONLY** | **Someone bought** | `fbq('track', 'Purchase', {value: 47.00, currency: 'USD'});` |

- [ ] **Lead event** (or Purchase event) code added to your **thank you page only** -- NOT your landing page
- [ ] ViewContent event added to your landing page (optional but recommended)
- [ ] Verified that Lead/Purchase event fires ONLY on the thank you page (not on every page)

**The most common mistake:** Putting the Lead event on your landing page instead of your thank you page. If Lead fires on the landing page, Meta counts every visitor as a conversion, your data is garbage, and the algorithm optimizes for clicks instead of actual leads.

### Verify Everything Works
- [ ] **Meta Pixel Helper** Chrome extension installed
- [ ] Visit your landing page -- Pixel Helper shows green checkmark with "PageView" event
- [ ] Visit your thank you page -- Pixel Helper shows "PageView" AND "Lead" (or "Purchase") events
- [ ] Events Manager shows pixel status as **"Active"**
- [ ] Test Events tool used (Events Manager > Test Events > enter your URL > complete a test conversion > verify events appear)

### Conversion Event Configuration
- [ ] In Events Manager: conversion event (Lead or Purchase) appears under "Overview"
- [ ] If using Advantage+ campaigns: your conversion event is available for selection as the optimization goal

---

## PHASE 4: CONVERSIONS API (RECOMMENDED)

The Conversions API (CAPI) sends conversion data directly from your server to Meta, bypassing browser limitations. After iOS 14.5, the pixel alone misses a significant portion of conversions from Apple devices.

- [ ] Conversions API set up (OR acknowledged as a post-launch improvement)

**Easiest setup paths for beginners:**
- **Shopify / WooCommerce:** Built-in CAPI integration (toggle it on in settings)
- **Zapier / Make.com:** Connect your form tool to Meta's Conversions API -- no coding
- **Landing page platforms:** Some (Leadpages, ClickFunnels) have built-in CAPI support

**If you can't set up CAPI before Session 16:** Launch with the pixel only. CAPI improves data quality but is not a blocker for your first test campaign. Add it after your first campaign is live. But know that your reported conversions may be lower than actual conversions.

---

## PHASE 5: AD CREATIVE + COPY

### Creative Assets
- [ ] At least 3 ad creatives ready (static images and/or videos)
- [ ] Images sized correctly: **1080x1080** (square, for feed) and/or **1080x1920** (vertical, for Stories/Reels)
- [ ] No more than 20% text on images (Meta deprioritizes text-heavy images)
- [ ] If using video: MP4 or MOV format, under 4GB, 15-60 seconds recommended
- [ ] Creatives do NOT contain: before/after transformation images, personal attribute claims ("Are you struggling with..."), or misleading claims

### Ad Copy
- [ ] Primary text written for each creative (recommended: under 125 characters for above-the-fold visibility, full text can be longer)
- [ ] Headline written for each creative (under 40 characters)
- [ ] Description written (under 25 characters, optional)
- [ ] Call-to-action selected (Learn More, Sign Up, Download, Get Offer, etc.)
- [ ] Copy does NOT make income claims, health cure claims, or reference personal attributes

### What Gets Ads Rejected (Avoid These)
- Before/after comparison images (even if real)
- "Are YOU tired of..." (personal attributes -- implies knowledge of the reader's condition)
- Income or earnings claims without disclaimers
- Clickbait ("You won't BELIEVE...")
- Landing page content that doesn't match ad claims
- Missing privacy policy on landing page
- AI-generated content without disclosure (Meta's 2025 policy)

---

## THE RULES

1. **Imperfect and live beats perfect and not launched.** A basic Carrd page with your Output 01 copy, a thank you page, a pixel with Lead event, and 3 Canva images is enough to run your first test. You iterate after seeing real data.

2. **The thank you page is non-negotiable.** Without it, Meta cannot track conversions. Your campaign will optimize for link clicks instead of leads, and you'll burn budget on traffic that doesn't convert.

3. **The 72-Hour Rule.** After launching, do NOT touch your campaign for 72 hours. The algorithm needs time to learn. Panic-editing in the first 3 days kills performance.

---

## MINIMUM VIABLE LAUNCH (Absolute Bare Minimum)

If you're short on time, these 8 items are the absolute floor. Everything else improves performance but isn't required to press "Publish":

1. [ ] Business Manager active with payment method
2. [ ] Facebook Page connected with profile photo + 1 post
3. [ ] Pixel installed on landing page AND thank you page
4. [ ] Lead event firing on thank you page ONLY
5. [ ] Landing page live with privacy policy link
6. [ ] Thank you page live at a separate URL
7. [ ] 3 ad creatives (images or video)
8. [ ] Ad copy for each creative + break-even CPA number

---

## CHECK YOUR READINESS

**Run the verification prompt** (Prompt 10 in this lesson) 3-4 days before Session 16. Give the prompt to Claude and it will:
- Walk through every item on this checklist with you
- Verify what's done vs. what's missing
- Tell you exactly what to fix and how long each fix takes
- Give you a READY / NOT READY verdict

**Or run Prompt 09** (Ready for Ads Self-Assessment) which scans your vault, scores you out of 100, and generates a prioritized action plan.

- **80+:** Ready to go
- **60-79:** A day or two of focused work
- **Below 60:** Focus only on Minimum Viable Launch items

---

## REFERENCE: FULL SESSION 14 SETUP GUIDE

For the complete step-by-step platform setup walkthrough (including audience creation, campaign structure, LinkedIn setup, and troubleshooting), see the **Session 14 Platform Setup Checklist** in your Lesson 14 materials.

---

*This checklist incorporates requirements as of February 2026. Meta updates policies frequently -- if something doesn't match what you see in Ads Manager, flag it in office hours.*
