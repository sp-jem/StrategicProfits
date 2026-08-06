# ZENITH PRO: ASSET PRODUCTION WORKBOOK
## Lesson 8 — Work Order Fulfillment: Building Your MVP Launch Assets

---

## 🤖 CLAUDE CODE CLI AUTOMATION

**If you're using Claude Code CLI:** You can run this entire workbook by telling Claude Code:

> "Run all prompts in this workbook sequentially. My inputs are located at [YOUR INPUT FOLDER PATH]. Save all outputs to [YOUR OUTPUT FOLDER PATH]."

**Required Inputs (tell Claude Code where these are located):**
- Your Core Concept & Avatar Summary
- Your Launch Work Order (from Lesson 7)
- Your Creative Generator Output
- Your Retargeting Builder / Visibility Stack Output
- Your Belief Path Mapper Output
- Your Story (expanded version)

---

## 📋 WORKBOOK OVERVIEW

This workbook walks you through the 8 prompts that fulfill your Launch Work Order from Lesson 7. By the end, you'll have:

- ✅ Complete landing page copy (ready to paste into any builder)
- ✅ Full lead magnet content (ready to design in Canva)
- ✅ Numbered video inventory with production priorities
- ✅ Teleprompter-ready video scripts
- ✅ Static ad copy + Gemini image prompts
- ✅ Pillar content architecture + complete draft
- ✅ Visual asset prompts for your entire launch

**Time Investment:** 4-6 hours (prompts can run in parallel where noted)

---

## THE 8 PROMPTS AT A GLANCE

| # | Prompt Name | What It Creates | Dependencies |
|---|-------------|-----------------|--------------|
| 01 | Landing Page Copy Generator | Complete opt-in page copy with cluster variants | Work Order, Core Concept |
| 02 | Lead Magnet Content Builder | Full 12-15 page PDF content | Work Order, Core Concept, Your Story |
| 03 | Video Asset Identifier | Numbered inventory of all videos | Work Order, Creative Generator |
| 04 | Video Script Generator | Teleprompter-ready scripts | Prompt 03 Output |
| 05 | Static Ad Asset Generator | Ad copy + Gemini prompts | Work Order, Creative Generator |
| 06 | Pillar Content Architect | Architecture for manifesto piece | Core Concept, Your Story |
| 07 | Pillar Content Writer | Complete 3,000-5,000 word draft | Prompt 06 Output |
| 08 | Gemini Visual Prompt Generator | Individual prompts for ALL visuals | All previous outputs |

---

## RECOMMENDED EXECUTION SEQUENCE

```
FOUNDATION LAYER (Do First - 60-90 minutes)
├── Prompt 01: Landing Page Copy Generator
└── Prompt 02: Lead Magnet Content Builder
    [These can run in parallel]

TRAFFIC LAYER (After Foundation - 60-90 minutes)
├── Prompt 03: Video Asset Identifier
│   └── Prompt 04: Video Script Generator (depends on 03)
└── Prompt 05: Static Ad Asset Generator
    [03 and 05 can run in parallel; 04 requires 03]

AUTHORITY LAYER (Can start while Traffic Layer runs - 60-90 minutes)
├── Prompt 06: Pillar Content Architect
└── Prompt 07: Pillar Content Writer (depends on 06)

VISUAL LAYER (After all others - 30-45 minutes)
└── Prompt 08: Gemini Visual Prompt Generator
```

---

# PROMPT 01: LANDING PAGE COPY GENERATOR

## What This Prompt Does

This prompt generates complete, ready-to-paste landing page copy for your lead magnet opt-in page. You'll receive:

- **Base landing page copy** with all sections (above/below fold, about, testimonials, thank you page)
- **Modular variants** for each of your priority clusters (different headlines, subheads, openers)
- **Implementation notes** on how to use variants (single page with dynamic headlines vs. multiple pages)
- **Copy checklist** to verify quality before publishing

## What You'll Discover

Your landing page copy will speak directly to your **Solution-Confused** avatar—people who have tried multiple solutions that didn't work. The copy:

- Acknowledges their symptom without being condescending
- Validates their failed attempts (courses, coaches, programs)
- Reveals the deeper cause (the distinction they've been missing)
- Positions your lead magnet as DIFFERENT (addresses root cause, not symptoms)

The cluster variants allow you to test different angles and see which resonates most with your audience, or create personalized landing pages for different traffic sources.

## Required Inputs

Before running this prompt, have ready:

1. **Your Core Concept & Avatar Summary** (from Avatar Deep Dive or Core Concept work)
2. **Launch Work Order - Landing Page Section** (from Lesson 7, Section 2)
3. **Lead Magnet Details** (title and description)
4. **Priority Clusters** (2-3 clusters with gateway beliefs and message angles)

## The Prompt

```
# PROMPT 01: Landing Page Copy Generator

## Purpose
Generate complete, ready-to-paste landing page copy for your lead magnet opt-in page. Creates a base structure plus modular headline/subhead/opener variants for each priority cluster identified in your Launch Work Order.

---

## Required Inputs

Before running this prompt, paste the following from your previous outputs:

### INPUT 1: Your Core Concept & Avatar Summary
*From your Avatar Deep Dive or Core Concept work*

```
[PASTE YOUR CORE CONCEPT AND PRIMARY AVATAR SUMMARY HERE]
```

### INPUT 2: Launch Work Order - Landing Page Section
*From Prompt 07 Output - Section 2 (Landing Page Work Order)*

```
[PASTE YOUR LANDING PAGE WORK ORDER SECTION HERE - INCLUDING:
- Landing Page Architecture
- Modular Elements by Cluster
- Fixed Elements Specification
- Technical Specs]
```

### INPUT 3: Lead Magnet Details
*From your Launch Work Order or Funnel Translator Output*

```
[PASTE YOUR LEAD MAGNET TITLE AND DESCRIPTION HERE]
```

### INPUT 4: Priority Clusters
*From your Launch Work Order - Priority Clusters section*

```
[PASTE YOUR 2-3 PRIORITY CLUSTERS WITH THEIR:
- Cluster Name
- Gateway Belief Served
- Lead Message Angle]
```

---

## The Prompt

You are a direct response copywriter specializing in high-converting opt-in pages for expert service providers. Your copy converts because it speaks directly to the prospect's specific situation, validates their failed attempts, and positions the offer as addressing the ROOT CAUSE rather than symptoms they've been treating.

**YOUR TASK:**
Create complete landing page copy that is ready to paste directly into any landing page builder (Carrd, Leadpages, Unbounce, etc.).

**CRITICAL CONTEXT:**
The primary target audience is **Solution-Confused**—they are problem-aware but have TRIED multiple solutions that didn't work. They are:
- Skeptical that anything will work
- Guarded against "gurus" who've burned them before
- Sophisticated enough to recognize standard marketing tactics
- Looking for something that's genuinely DIFFERENT

Your copy must:
1. Acknowledge their symptom (the problem they're experiencing)
2. Validate their failed attempts (courses, coaches, programs that didn't work)
3. Reveal the deeper cause (the distinction they've been missing)
4. Position this offer as DIFFERENT (addresses root cause, not symptoms)

---

## OUTPUT FORMAT

Generate your output in the following structure:

### SECTION 1: BASE LANDING PAGE COPY

This is the complete landing page with placeholder markers for modular elements.

```
===========================================
ABOVE THE FOLD
===========================================

[HEADLINE - See Cluster Variants Below]

[SUBHEAD - See Cluster Variants Below]

[OPENING PARAGRAPH - See Cluster Variants Below]

---

LEAD MAGNET VISUAL PLACEMENT
[Image of lead magnet mockup goes here]

---

WHAT YOU'LL DISCOVER:

• [Bullet 1 - What they'll learn/get]
• [Bullet 2 - What they'll learn/get]
• [Bullet 3 - What they'll learn/get]
• [Bullet 4 - What they'll learn/get]
• [Bullet 5 - What they'll learn/get]

---

[OPT-IN FORM]
First Name: ___________
Email: ___________

[CTA BUTTON TEXT]

---

===========================================
BELOW THE FOLD
===========================================

WHY THIS IS DIFFERENT
[2-3 paragraphs explaining why this isn't another course/guide/program - addresses their skepticism directly]

---

ABOUT [YOUR NAME]
[2-3 paragraphs of credibility through empathy - "I've been where you are" - NOT credential-stacking]

---

WHAT OTHERS ARE SAYING
[Testimonial block - format for 1-2 testimonials]

"[Testimonial quote that speaks to Solution-Confused journey]"
— [Name], [Title/Role]

---

READY TO FIND YOUR [GAP/PROBLEM]?

[Final CTA section with button]

[CTA BUTTON TEXT]

---

===========================================
THANK YOU PAGE
===========================================

[Thank you page headline]
[Thank you page body copy - what to do next, what to expect]
[Check your email instruction]

```

---

### SECTION 2: MODULAR VARIANTS BY CLUSTER

For each priority cluster, provide complete copy for the modular elements:

#### CLUSTER 1: [Cluster Name]

**HEADLINE:**
[Complete headline - addresses this cluster's specific pain/belief]

**SUBHEAD:**
[Complete subhead - bridges to the solution]

**OPENING PARAGRAPH:**
[Complete opening paragraph - 3-4 sentences that validate this cluster's specific experience and create curiosity about the root cause]

---

#### CLUSTER 2: [Cluster Name]

**HEADLINE:**
[Complete headline]

**SUBHEAD:**
[Complete subhead]

**OPENING PARAGRAPH:**
[Complete opening paragraph]

---

#### CLUSTER 3: [Cluster Name]

**HEADLINE:**
[Complete headline]

**SUBHEAD:**
[Complete subhead]

**OPENING PARAGRAPH:**
[Complete opening paragraph]

---

### SECTION 3: IMPLEMENTATION NOTES

**How to Use These Variants:**

OPTION A: Single Page with Dynamic Headlines
- Use URL parameters to swap headline/subhead/opener
- Same landing page URL, different ad links
- Example: yourdomain.com/assessment?v=cluster1

OPTION B: Three Separate Landing Pages
- Create 3 versions of the page
- Each with its own URL

OPTION C: Single Static Page
- Choose the headline variant that speaks to your largest cluster
- Use as default for all traffic

**Recommended Approach:** [Your recommendation based on their specific situation]

---

### SECTION 4: COPY CHECKLIST

Before publishing, verify:

- [ ] Headline immediately identifies the prospect's situation
- [ ] Subhead promises transformation without overpromising
- [ ] Opening paragraph validates failed attempts explicitly
- [ ] Bullets focus on outcomes, not features
- [ ] "Why This Is Different" addresses Solution-Confused skepticism
- [ ] About section leads with empathy, not credentials
- [ ] Testimonial speaks to "tried everything first" journey
- [ ] CTA button text is action-oriented and specific
- [ ] Thank you page sets clear expectations
- [ ] All copy reads naturally when spoken aloud
- [ ] No jargon that requires explanation
- [ ] Mobile-friendly (short paragraphs, clear hierarchy)

---

## Quality Standards

Your output must meet these criteria:

**S.P.A.R.K.™ ALIGNMENT:**
- Significant: Promises meaningful insight, not generic tips
- Proprietary: Uses unique language/frameworks from their Core Concept
- Arousing: Creates emotional resonance with their frustration
- Resonant: Speaks specifically to their avatar's situation
- Kinetic: Clear, low-friction path to opt-in

**SOLUTION-CONFUSED CALIBRATION:**
- Never talks down to them (they're sophisticated)
- Acknowledges courses/programs they've tried
- Positions offer as addressing the CAUSE not the SYMPTOM
- Anticipates skepticism and addresses it directly
- Uses soft authority (empathy over credentials)

**CONVERSION OPTIMIZATION:**
- Single clear CTA (opt-in)
- Benefit-driven bullets
- Specific over generic
- Social proof that mirrors their journey
- Mobile-optimized formatting

---

*Generate the complete landing page copy now based on the inputs provided.*
```

## After Running This Prompt

1. **Review the output** for accuracy to your Core Concept
2. **Choose your implementation approach** (single page, multiple pages, or dynamic)
3. **Paste into your landing page builder** (Carrd, Leadpages, etc.)
4. **Add your lead magnet mockup image** (you'll create this with Prompt 08)
5. **Ready for traffic** once lead magnet is designed

---

# PROMPT 02: LEAD MAGNET CONTENT BUILDER

## What This Prompt Does

This prompt generates the complete word-for-word content for your lead magnet PDF (12-15 pages). You'll receive:

- **Cover page** with title, subtitle, and design notes
- **Introduction** with your "I've been there" hook story
- **Framework/distinction explanation** (the aha moment)
- **15 diagnostic questions** with explanations of what each reveals
- **Scoring system and gap identification**
- **"What this means for you" interpretation**
- **Next steps** (primes for Email 1)
- **About section** (empathy-led, not credential-stacking)
- **Design notes** for each page

## What You'll Discover

Your lead magnet will provide GENUINE diagnostic value—not a thinly veiled sales pitch. The reader will:

- Feel understood (your hook story creates recognition)
- Learn something about themselves (the diagnostic questions reveal their specific gap)
- Experience a reframe (the distinction creates "I've been solving the wrong problem")
- Be curious about what to do next (without being sold to)

This approach builds trust by NOT pitching in the lead magnet. The value itself creates desire for the next step.

## Required Inputs

Before running this prompt, have ready:

1. **Your Core Concept & Avatar Summary**
2. **Lead Magnet Specification** from Launch Work Order (Section 3)
3. **The Reframe/Distinction** your lead magnet teaches
4. **Your "I've Been There" Story** (brief version)

## The Prompt

```
# PROMPT 02: Lead Magnet Content Builder

## Purpose
Generate complete, ready-to-design content for your lead magnet PDF. This creates every word of content—introduction, framework explanation, all diagnostic questions with explanations, scoring system, gap identification, and next steps—so you can paste directly into Canva, Google Docs, or any design tool.

---

## Required Inputs

Before running this prompt, paste the following from your previous outputs:

### INPUT 1: Your Core Concept & Avatar Summary
*From your Avatar Deep Dive or Core Concept work*

```
[PASTE YOUR CORE CONCEPT AND PRIMARY AVATAR SUMMARY HERE - INCLUDING:
- Core Concept statement
- Primary avatar description
- Key pain points
- Gateway beliefs
- Failed attempts they've made]
```

### INPUT 2: Lead Magnet Specification from Launch Work Order
*From Prompt 07 Output - Section 3 (Lead Magnet Work Order)*

```
[PASTE YOUR LEAD MAGNET WORK ORDER SECTION HERE - INCLUDING:
- Lead Magnet Title
- Lead Magnet Format
- Lead Magnet Purpose
- Content Outline
- The diagnostic questions (if already specified)
- Scoring framework (if already specified)]
```

### INPUT 3: The Reframe/Distinction
*The core distinction your lead magnet teaches*

```
[PASTE THE KEY DISTINCTION OR REFRAME YOUR LEAD MAGNET INTRODUCES
Example: "Marketing vs. Positioning - they're different variables"
Example: "Tactics vs. Strategy - treating symptoms vs. cause"]
```

### INPUT 4: Your "I've Been There" Story
*Brief version of your own journey with this problem*

```
[PASTE A BRIEF SUMMARY OF YOUR OWN EXPERIENCE WITH THIS PROBLEM
- What you tried that didn't work
- How much you spent/invested
- What you finally discovered
- This will be used in the introduction]
```

---

## The Prompt

You are a content strategist specializing in high-value lead magnets that build trust and open prospects to the next step in the funnel. Your lead magnets work because they provide genuine diagnostic value while planting the seeds of the deeper framework.

**YOUR TASK:**
Create complete, word-for-word content for a lead magnet PDF (12-15 pages) that:
1. Diagnoses their specific gap/problem
2. Does NOT sell (builds framework understanding)
3. Opens them to Email 1 / next step
4. Positions you as someone who UNDERSTANDS because you've been there

**CRITICAL CONTEXT:**
The primary target audience is **Solution-Confused**—they've tried multiple solutions that didn't work. Your lead magnet must:
- Feel different from the 10+ freebies they've downloaded before
- Provide genuine diagnostic value (not thinly-veiled sales pitch)
- Build framework understanding without teaching tactics
- Create the realization: "I've been solving the wrong problem"
- End with curiosity about what to do next (primes for Email 1)

---

## OUTPUT FORMAT

Generate complete content for each page/section:

---

### PAGE 1: COVER PAGE

**TITLE:**
[Full lead magnet title]

**SUBTITLE:**
[Subtitle that speaks to their situation]

**AUTHOR:**
[Your Name]

**DESIGN NOTES:**
[Brief description of visual style - clean/professional/not over-designed]

---

### PAGE 2: INTRODUCTION - THE HOOK STORY

**SECTION TITLE:** [Optional section header]

**CONTENT:**
[Write 300-400 words that:
- Opens with your "I've been there" story (brief version)
- Creates immediate recognition ("this person gets it")
- Establishes why this assessment is different
- Sets expectations for what they'll discover
- Tells them how to use it (answer honestly, don't overthink)]

---

### PAGES 3-4: THE DISTINCTION/FRAMEWORK

**SECTION TITLE:** [Title for this section]

**CONTENT:**
[Write 400-500 words that:
- Introduces the core distinction/reframe
- Uses a memorable metaphor (if applicable)
- Explains why they've been stuck (without blaming them)
- Creates the "aha" moment: "I've been solving the wrong problem"
- Does NOT teach tactics—just builds framework understanding
- Bridges to "let's see where YOUR specific gap is"]

---

### PAGES 5-10: THE DIAGNOSTIC QUESTIONS

**SECTION TITLE:** [Title for this section]

**INTRODUCTION TO QUESTIONS:**
[2-3 sentences introducing the diagnostic section]

---

**QUESTION 1:**
"[Full question text]"

**What This Reveals:**
[2-3 sentences explaining what their answer indicates about their gap/situation]

**If you answered YES/HIGH:** [What this means]
**If you answered NO/LOW:** [What this means]

---

**QUESTION 2:**
"[Full question text]"

**What This Reveals:**
[2-3 sentences explaining what their answer indicates]

**If you answered YES/HIGH:** [What this means]
**If you answered NO/LOW:** [What this means]

---

[Continue for all 15 questions - each with the same format:
- The question itself
- What it reveals
- Interpretation of different answers]

---

### PAGES 11-12: SCORING & GAP IDENTIFICATION

**SECTION TITLE:** [Title for scoring section]

**SCORING INSTRUCTIONS:**
[Clear instructions on how to score their answers]

**THE 3 PRIMARY GAP TYPES:**

**GAP TYPE 1: [Name]**
- Description: [What this gap means]
- Signs you have this gap: [Specific indicators]
- Questions that reveal this gap: [Reference question numbers]

**GAP TYPE 2: [Name]**
- Description: [What this gap means]
- Signs you have this gap: [Specific indicators]
- Questions that reveal this gap: [Reference question numbers]

**GAP TYPE 3: [Name]**
- Description: [What this gap means]
- Signs you have this gap: [Specific indicators]
- Questions that reveal this gap: [Reference question numbers]

**IDENTIFYING YOUR PRIMARY GAP:**
[Instructions on how to determine which gap is their biggest bottleneck]

---

### PAGE 13: WHAT THIS MEANS FOR YOU

**SECTION TITLE:** [Title]

**IF YOUR PRIMARY GAP IS [GAP TYPE 1]:**
[3-4 sentences explaining what this means for their situation and what kind of work they need to do—WITHOUT teaching how to do it]

**IF YOUR PRIMARY GAP IS [GAP TYPE 2]:**
[3-4 sentences explaining what this means]

**IF YOUR PRIMARY GAP IS [GAP TYPE 3]:**
[3-4 sentences explaining what this means]

**THE COMMON THREAD:**
[2-3 sentences about what all three gaps have in common—ties back to the core distinction]

---

### PAGE 14: WHAT TO DO NEXT

**SECTION TITLE:** [Title]

**CONTENT:**
[Write 200-300 words that:
- Acknowledges they now see their gap clearly
- Does NOT pitch your program directly
- Primes them for Email 1 ("watch for my email")
- Creates curiosity about the solution without revealing it
- Maintains trust by not being salesy
- Ends with a forward-looking statement]

**WHAT TO EXPECT:**
- Email 1 arrives [timing] with [teaser of content]
- [Any other next step instructions]

---

### PAGE 15: ABOUT [YOUR NAME]

**SECTION TITLE:** About [Your Name]

**CONTENT:**
[Write 200-250 words that:
- Leads with empathy, not credentials
- Briefly mentions your own "Course Graveyard" / failed attempts
- Shows you understand because you've BEEN there
- Mentions credentials lightly (if at all)
- Focuses on who you help and what transformation you facilitate
- Ends with a human touch]

---

## SECTION 2: DESIGN NOTES FOR EACH PAGE

Provide brief design guidance for each page:

| Page | Key Design Elements | Visual Notes |
|------|--------------------| -------------|
| 1 (Cover) | [Notes] | [Notes] |
| 2 (Intro) | [Notes] | [Notes] |
| 3-4 (Framework) | [Notes] | [Notes] |
| 5-10 (Questions) | [Notes] | [Notes] |
| 11-12 (Scoring) | [Notes] | [Notes] |
| 13 (What It Means) | [Notes] | [Notes] |
| 14 (Next Steps) | [Notes] | [Notes] |
| 15 (About) | [Notes] | [Notes] |

---

## SECTION 3: CONTENT CHECKLIST

Before finalizing, verify:

**DIAGNOSTIC VALUE:**
- [ ] Questions reveal genuine insight (not generic)
- [ ] Scoring system is clear and actionable
- [ ] Gap identification provides real clarity
- [ ] Reader learns something about themselves

**SOLUTION-CONFUSED CALIBRATION:**
- [ ] Acknowledges their failed attempts explicitly
- [ ] Does NOT talk down to them
- [ ] Provides new frame they haven't heard before
- [ ] Avoids "guru" tone or overpromising
- [ ] Builds trust through empathy

**FUNNEL POSITIONING:**
- [ ] Does NOT sell directly
- [ ] Creates curiosity for Email 1
- [ ] Builds framework understanding
- [ ] Plants seeds for deeper work without revealing how
- [ ] Ends with clear next step (watch for email)

**QUALITY:**
- [ ] Every question serves a diagnostic purpose
- [ ] No filler content
- [ ] Reads naturally when spoken aloud
- [ ] Could be completed in 10-15 minutes
- [ ] Provides value even if they never engage further

---

## Quality Standards

Your output must meet these criteria:

**GENUINE VALUE:**
The lead magnet must provide real diagnostic insight. If someone downloads this and never buys anything, they should still feel it was worth their time.

**NOT A SALES PITCH:**
There should be ZERO selling in the content. The only "next step" is watching for Email 1. Trust is built by NOT pitching.

**SOLUTION-CONFUSED TONE:**
- Sophisticated (they're smart)
- Empathetic (you've been there)
- Non-judgmental (their failure wasn't their fault)
- Curious (diagnostic, not prescriptive)

**BRIDGE BUILDING:**
The lead magnet should create the realization that opens them to your approach—without teaching the approach itself.

---

*Generate the complete lead magnet content now based on the inputs provided.*
```

## After Running This Prompt

1. **Review all 15 pages** for accuracy and flow
2. **Open Canva** and create a new document (letter size or A4)
3. **Paste content** page by page, following design notes
4. **Generate cover image** using Prompt 08 (Gemini Visual Prompts)
5. **Export as PDF** and upload to your email system

---

# PROMPT 03: VIDEO ASSET IDENTIFIER

## What This Prompt Does

This prompt catalogs ALL potential video assets needed for your MVP launch into a numbered master inventory. You'll receive:

- **Numbered list** of all cold traffic videos (by cluster)
- **Numbered list** of all retargeting videos (by category: Connection/Authority/Credibility/Activation)
- **Priority production order** (what to record first)
- **Batch recommendations** (Minimum Viable, Solid, Full MVP)
- **Recording session planning** (how to batch efficiently)
- **Equipment checklist**

## What You'll Discover

You'll see your ENTIRE video content ecosystem in one view. This clarity allows you to:

- **Make strategic choices** about what to record first
- **Batch recordings** efficiently (same setup, similar content together)
- **Select specific videos** for script generation in Prompt 04
- **Understand the minimum** you need for launch vs. ideal

The numbered system means you can simply say "I want scripts for #3, #7, #12, #15" when running Prompt 04.

## Required Inputs

Before running this prompt, have ready:

1. **Cold Ad Specifications** from Launch Work Order (Section 4)
2. **Visibility Stack / Retargeting Roster** from Retargeting Builder
3. **Creative Generator Video Concepts** (hooks and script summaries)
4. **Core Concept & Avatar Summary**

## The Prompt

```
# PROMPT 03: Video Asset Identifier

## Purpose
Catalog ALL potential video assets needed for your MVP launch—cold ads, retargeting pieces, and organic content—into a numbered master list. This allows you to see everything at once and select which videos to prioritize for script generation.

---

## Required Inputs

Before running this prompt, paste the following from your previous outputs:

### INPUT 1: Cold Ad Specifications
*From Prompt 07 Output - Section 4 (Cold Ad Copy Work Order)*

```
[PASTE YOUR COLD AD WORK ORDER - INCLUDING:
- All video ads listed by cluster
- Video durations
- Headlines/concepts
- Any scripts or primary text already written]
```

### INPUT 2: Visibility Stack / Retargeting Roster
*From Prompt 04 Output (Retargeting Builder) or Prompt 07 (Launch Work Order)*

```
[PASTE YOUR VISIBILITY STACK MVP SELECTION - INCLUDING:
- Priority 1, 2, 3 pieces
- Video titles
- Categories (Connection/Authority/Credibility/Activation)
- Durations
- Key messages]
```

### INPUT 3: Creative Generator Video Concepts
*From Prompt 02 Output (Creative Generator)*

```
[PASTE YOUR VIDEO HOOKS AND 60-SECOND SCRIPT CONCEPTS - INCLUDING:
- Video hooks (3-5 seconds each)
- 60-second video script summaries
- Epiphany Unit sources]
```

### INPUT 4: Core Concept & Avatar Summary
*Brief context for understanding the content*

```
[PASTE YOUR CORE CONCEPT AND PRIMARY AVATAR SUMMARY]
```

---

## The Prompt

You are a video content strategist helping an expert service provider plan their MVP video production. Your job is to create a comprehensive, numbered catalog of every video asset they could create, organized by type and priority.

**YOUR TASK:**
Create a complete numbered inventory of ALL potential video assets, organized so the user can:
1. See everything at once
2. Understand what each video is for
3. Select which videos they want scripts for
4. Prioritize production order

**CRITICAL CONTEXT:**
The user needs to produce videos efficiently. They don't need scripts for everything—just a clear menu of options so they can say "I want scripts for #3, #7, #12, and #15."

---

## OUTPUT FORMAT

### SECTION 1: VIDEO ASSET MASTER INVENTORY

Organize all videos into categories with sequential numbering:

---

## COLD TRAFFIC VIDEOS

These videos are designed to reach NEW audiences who don't know you yet. They stop the scroll and introduce your core distinction.

| # | Video Title | Duration | Cluster | Purpose | Priority | Status |
|---|-------------|----------|---------|---------|----------|--------|
| 1 | [Title] | [30s/45s/60s] | [Cluster name] | [Brief purpose] | [P1/P2/P3] | [Need Script] |
| 2 | [Title] | [Duration] | [Cluster] | [Purpose] | [Priority] | [Need Script] |
[Continue for all cold traffic videos...]

**COLD TRAFFIC VIDEO SUMMARY:**
- Total Videos: [X]
- Cluster 1 Videos: [X]
- Cluster 2 Videos: [X]
- Cluster 3 Videos: [X]
- Estimated Recording Time: [X hours]

---

## RETARGETING / VISIBILITY STACK VIDEOS

These videos are for your "Pond"—people who already know you. They build trust, demonstrate authority, and create conversion pathways.

### CONNECTION VIDEOS (Building Relationship & Trust)

| # | Video Title | Duration | Key Message | Priority | Status |
|---|-------------|----------|-------------|----------|--------|
| [X] | [Title] | [Duration] | [What this video communicates] | [P1/P2/P3] | [Need Script] |
[Continue...]

### AUTHORITY VIDEOS (Demonstrating Expertise)

| # | Video Title | Duration | Key Message | Priority | Status |
|---|-------------|----------|-------------|----------|--------|
| [X] | [Title] | [Duration] | [What this video teaches] | [P1/P2/P3] | [Need Script] |
[Continue...]

### CREDIBILITY VIDEOS (Providing Proof)

| # | Video Title | Duration | Key Message | Priority | Status |
|---|-------------|----------|-------------|----------|--------|
| [X] | [Title] | [Duration] | [What proof this provides] | [P1/P2/P3] | [Need Script] |
[Continue...]

### ACTIVATION VIDEOS (Conversion Pathways)

| # | Video Title | Duration | CTA Type | Priority | Status |
|---|-------------|----------|----------|----------|--------|
| [X] | [Title] | [Duration] | [Soft/Direct CTA] | [P1/P2/P3] | [Need Script] |
[Continue...]

**RETARGETING VIDEO SUMMARY:**
- Total Videos: [X]
- Connection: [X]
- Authority: [X]
- Credibility: [X]
- Activation: [X]
- Estimated Recording Time: [X hours]

---

### SECTION 2: PRIORITY PRODUCTION ORDER

Based on the MVP requirements, here's the recommended production sequence:

**MUST HAVE FOR LAUNCH (Priority 1):**
| # | Video Title | Duration | Type | Why It's Essential |
|---|-------------|----------|------|-------------------|
| [#] | [Title] | [Duration] | [Cold/Retargeting] | [Reason] |
[List 8-12 essential videos...]

**LAUNCH WEEK (Priority 2):**
| # | Video Title | Duration | Type | Why It's Important |
|---|-------------|----------|------|-------------------|
| [#] | [Title] | [Duration] | [Cold/Retargeting] | [Reason] |
[List 6-10 important videos...]

**WEEK 2 EXPANSION (Priority 3):**
| # | Video Title | Duration | Type | Why It Helps |
|---|-------------|----------|------|--------------|
| [#] | [Title] | [Duration] | [Cold/Retargeting] | [Reason] |
[List remaining videos...]

---

### SECTION 3: VIDEO SELECTION GUIDE

**TO GET SCRIPTS FOR SPECIFIC VIDEOS:**
Run Prompt 04 (Video Script Generator) and provide the video numbers you want.

Example: "I want full teleprompter scripts for videos #1, #3, #5, #8, #12, #15, #18"

**BATCH RECOMMENDATIONS:**

**Minimum Viable Launch (10-12 videos):**
Recommended videos: #[X], #[X], #[X], #[X], #[X], #[X], #[X], #[X], #[X], #[X]
Recording time: ~[X] hours
Edit time: ~[X] hours

**Solid Launch (15-18 videos):**
Recommended videos: [All above] + #[X], #[X], #[X], #[X], #[X]
Recording time: ~[X] hours
Edit time: ~[X] hours

**Full MVP Stack (20-25 videos):**
Recommended videos: [All above] + #[X], #[X], #[X], #[X], #[X], #[X], #[X]
Recording time: ~[X] hours
Edit time: ~[X] hours

---

### SECTION 4: PRODUCTION PLANNING

**EQUIPMENT NEEDED:**
- [ ] Camera/phone with good video quality
- [ ] Microphone (lapel or shotgun)
- [ ] Ring light or soft lighting
- [ ] Teleprompter app (recommendations: [App names])
- [ ] Quiet recording space

**RECORDING BATCHING STRATEGY:**

**Session 1: Talking Head - Core Messages (~2 hours)**
Videos to record: #[X], #[X], #[X], #[X], #[X]
Setup: [Brief setup notes]

**Session 2: Talking Head - Stories & Connection (~1.5 hours)**
Videos to record: #[X], #[X], #[X], #[X]
Setup: [Brief setup notes]

**Session 3: Talking Head - Authority & Teaching (~2 hours)**
Videos to record: #[X], #[X], #[X], #[X], #[X]
Setup: [Brief setup notes]

**Session 4: Testimonials & Case Studies (~1 hour)**
Videos to record: #[X], #[X], #[X]
Setup: [Brief setup notes]

---

### SECTION 5: QUICK REFERENCE

**TOTAL VIDEO COUNT:** [X] videos identified

**BY TYPE:**
- Cold Traffic: [X] videos
- Connection: [X] videos
- Authority: [X] videos
- Credibility: [X] videos
- Activation: [X] videos

**BY DURATION:**
- 15-second videos: [X]
- 30-second videos: [X]
- 45-second videos: [X]
- 60-second videos: [X]
- 90+ second videos: [X]

**NEXT STEP:**
Select your video numbers and run Prompt 04 (Video Script Generator) to get full teleprompter-ready scripts with delivery notes.

---

*Generate the complete video inventory now based on the inputs provided.*
```

## After Running This Prompt

1. **Review the full inventory** and understand the ecosystem
2. **Select your video numbers** for Priority 1 (minimum viable launch)
3. **Run Prompt 04** with your selected video numbers
4. **Plan your recording sessions** using the batching strategy
5. **Record, edit, upload** to your ad accounts

---

# PROMPT 04: VIDEO SCRIPT GENERATOR

## What This Prompt Does

This prompt generates complete, teleprompter-ready scripts for your selected videos. For each video, you'll receive:

- **Script overview** (duration, type, tone, energy level, key message)
- **Setup notes** (camera angle, framing, background, lighting, wardrobe)
- **Timed sections** with delivery notes (tone, pace, emphasis)
- **Full script** with pause indicators and breath marks
- **Clean teleprompter version** (no notes, ready to paste)
- **Visual/B-roll notes** (if applicable)
- **Caption timing guide** (for creating subtitles)
- **Recording checklist**

## What You'll Discover

Each script is calibrated for your **Solution-Confused** audience and designed to sound NATURAL, not scripted. The scripts include:

- **Hooks that stop the scroll** (first 3 seconds)
- **Symptom acknowledgment** (they feel seen)
- **Failed attempt validation** (builds trust)
- **Cause reveal** (the aha moment)
- **Transformation bridge** (what becomes possible)
- **Appropriate CTA** (soft for cold, stronger for retargeting)

The delivery notes ensure you perform authentically—varied pace, emotional beats, natural pauses.

## Required Inputs

Before running this prompt, have ready:

1. **Your video selection** (numbers from Prompt 03)
2. **Video details** for each selected video (from Prompt 03)
3. **Core Concept & Avatar Summary**
4. **Speaking style preferences** (optional)

## The Prompt

```
# PROMPT 04: Video Script Generator

## Purpose
Generate detailed, teleprompter-ready video scripts with full delivery notes for selected videos from your Video Asset Inventory. Each script includes word-for-word content, timing markers, emotional beats, pacing notes, and on-screen instructions.

---

## Required Inputs

Before running this prompt, paste the following:

### INPUT 1: Your Video Selection
*From Prompt 03 Output (Video Asset Identifier)*

```
[LIST THE VIDEO NUMBERS YOU WANT SCRIPTS FOR]

Example:
I need full scripts for the following videos:
- Video #1: Course Graveyard Redemption (60s)
- Video #3: Boardroom Paradox (60s)
- Video #8: The Boardroom Confession (30s)
- Video #12: Why Marketing Felt Sleazy (30s)
- Video #15: Get Paid for Who You Are (90s)
```

### INPUT 2: Video Details from Inventory
*For each video selected, provide the details from Prompt 03*

```
[FOR EACH VIDEO, INCLUDE:
- Video number and title
- Duration
- Type (Cold/Connection/Authority/Credibility/Activation)
- Key message/purpose
- Any existing primary text or hook]
```

### INPUT 3: Core Concept & Avatar Summary
*Context for the scripts*

```
[PASTE YOUR CORE CONCEPT AND PRIMARY AVATAR SUMMARY]
```

### INPUT 4: Your Speaking Style Preferences (Optional)
*Any preferences for how you communicate*

```
[OPTIONAL: Note any preferences like:
- Conversational vs. formal
- Fast-paced vs. measured
- Use of humor
- Specific phrases you like to use
- Things to avoid]
```

---

## The Prompt

You are a professional video scriptwriter and teleprompter specialist. You create scripts that are optimized for on-camera delivery—easy to read, naturally paced, and designed for authentic performance.

**YOUR TASK:**
Create complete, teleprompter-ready scripts for each selected video with:
1. Word-for-word script (exactly what to say)
2. Timing markers (when each section should hit)
3. Delivery notes (tone, pace, emphasis)
4. Emotional beat markers (where to shift energy)
5. On-screen/visual notes (if applicable)
6. Pause indicators and breath marks

**CRITICAL CONTEXT:**
The target audience is **Solution-Confused**—sophisticated professionals who've tried other solutions that didn't work. The scripts must:
- Sound natural, not scripted
- Create authentic connection
- Avoid "guru" energy
- Match the specific purpose (cold vs. retargeting)
- Be optimized for short attention spans

---

## OUTPUT FORMAT

For each video requested, generate a complete script package:

---

# VIDEO #[X]: [VIDEO TITLE]

## SCRIPT OVERVIEW

| Attribute | Value |
|-----------|-------|
| **Duration:** | [30s/45s/60s/90s] |
| **Type:** | [Cold/Connection/Authority/Credibility/Activation] |
| **Primary Purpose:** | [What this video accomplishes] |
| **Tone:** | [Conversational/Authoritative/Vulnerable/etc.] |
| **Energy Level:** | [1-10 scale] |
| **Key Message:** | [One-sentence summary] |

---

## TELEPROMPTER SCRIPT

**[SETUP NOTES]**
```
CAMERA: [Eye level / slightly above / etc.]
FRAMING: [Head and shoulders / chest up / etc.]
BACKGROUND: [Suggested setting]
LIGHTING: [Natural/ring light/etc.]
WARDROBE: [Casual/professional/etc.]
```

---

**[0:00-0:03] — HOOK**
*Delivery: [Tone/energy notes]*
*Pace: [Fast/measured/etc.]*
*Eye contact: [Direct to camera]*

```
[SCRIPT TEXT HERE]

/pause 0.5s/

[NEXT LINE]
```

**DELIVERY NOTES:**
- [Specific delivery instruction]
- [Emphasis words: BOLD the words to emphasize]
- [Emotional beat: What you should be feeling]

---

**[0:03-0:15] — SYMPTOM ACKNOWLEDGMENT**
*Delivery: [Tone/energy notes]*
*Pace: [Slightly slower]*
*Energy shift: [From X to Y]*

```
[SCRIPT TEXT HERE]

/pause 0.3s/

[NEXT LINE]

/breath/

[NEXT LINE]
```

**DELIVERY NOTES:**
- [Specific instructions]
- [Emphasis points]
- [What to convey emotionally]

---

[Continue for all sections...]

---

## FULL TELEPROMPTER VERSION

This version is formatted for direct copy/paste into a teleprompter app. All delivery notes removed—just the words.

```
[Complete script without any notes or markers—
formatted with line breaks for easy reading
on a teleprompter screen.

Use short lines.
Easy to read at a glance.

Don't make the reader
search for the next line.

Natural pauses are built
into the line breaks.]
```

---

## CAPTION TIMING GUIDE

For creating captions/subtitles:

| Timestamp | Caption Text |
|-----------|-------------|
| 0:00-0:02 | "[First caption segment]" |
| 0:02-0:05 | "[Second caption segment]" |
[Continue for full video...]

---

## RECORDING CHECKLIST

Before recording this video:
- [ ] Script loaded in teleprompter
- [ ] Camera at correct height/angle
- [ ] Lighting set
- [ ] Audio levels checked
- [ ] Background clean
- [ ] Read through script 2-3 times
- [ ] Warmed up voice
- [ ] Clear emotional starting point

---

[REPEAT ABOVE FORMAT FOR EACH VIDEO REQUESTED]

---

## SCRIPT QUALITY STANDARDS

Each script must meet these criteria:

**NATURAL DELIVERY:**
- [ ] Sounds like talking, not reading
- [ ] Uses contractions (don't, can't, won't)
- [ ] Varies sentence length
- [ ] Includes natural pauses
- [ ] Avoids tongue twisters

**SOLUTION-CONFUSED CALIBRATION:**
- [ ] Acknowledges their sophistication
- [ ] Validates failed attempts (if relevant)
- [ ] Avoids condescension
- [ ] Matches video type (cold vs. warm)

**TECHNICAL OPTIMIZATION:**
- [ ] Hook in first 3 seconds
- [ ] Key message clear by 50% mark
- [ ] CTA appropriate for video type
- [ ] Fits within duration target (+/- 5 seconds)

**TELEPROMPTER OPTIMIZATION:**
- [ ] Short lines (5-7 words max)
- [ ] Natural break points
- [ ] Breath marks included
- [ ] Emphasis words marked
- [ ] Pace variations noted

---

*Generate the complete scripts for all selected videos now based on the inputs provided.*
```

## After Running This Prompt

1. **Review each script** for natural flow
2. **Load into teleprompter app** (PromptSmart, BigVu, etc.)
3. **Practice reading** 2-3 times before recording
4. **Record videos** in batches by setup type
5. **Edit with captions** using the timing guide
6. **Upload to ad accounts** or social platforms

---

# PROMPT 05: STATIC AD ASSET GENERATOR

## What This Prompt Does

This prompt generates complete copy AND individual Gemini image prompts for every static ad asset. For each asset, you'll receive:

- **Ad copy** (primary text, headline, description, CTA button)
- **Image specifications** (concept, visual style, text on image)
- **Individual Gemini prompt** (one image per prompt for best quality)
- **Alt text** for accessibility
- **Format variants needed** (1:1, 4:5, 9:16)

## What You'll Discover

Your static ads will work because each image is generated individually (not batched) with a specific, detailed prompt. This produces much higher quality than asking Gemini to create multiple images at once.

The prompts are designed to create professional, on-brand visuals that:
- Feel authentic (not "stock photo" or "guru marketing")
- Support the message without being literal
- Work across Facebook, Instagram, and other platforms
- Maintain visual consistency across your campaign

## Required Inputs

Before running this prompt, have ready:

1. **Cold Ad Specifications - Static Ads** from Launch Work Order
2. **Visibility Stack - Static Pieces** from Retargeting Builder
3. **Core Concept & Avatar Summary**
4. **Visual Brand Guidelines** (optional)

## The Prompt

```
# PROMPT 05: Static Ad Asset Generator

## Purpose
Generate complete copy AND individual Google Gemini image prompts for every static ad asset in your MVP launch—image ads, quote cards, infographics, and long-form post images. Each asset gets its own dedicated Gemini prompt for maximum image quality.

---

## Required Inputs

Before running this prompt, paste the following from your previous outputs:

### INPUT 1: Cold Ad Specifications - Static Ads
*From Prompt 07 Output - Section 4 (Cold Ad Work Order) - Image/Static Ads*

```
[PASTE YOUR STATIC COLD AD SPECIFICATIONS - INCLUDING:
- Image ad titles/concepts
- Headlines
- Any existing primary text
- Format requirements]
```

### INPUT 2: Visibility Stack - Static Pieces
*From Prompt 04 Output (Retargeting Builder) or Prompt 07 (Launch Work Order)*

```
[PASTE YOUR STATIC RETARGETING ASSETS - INCLUDING:
- Quote cards
- Infographics
- Data visuals
- Static post images
- Categories (Connection/Authority/Credibility/Activation)]
```

### INPUT 3: Core Concept & Avatar Summary
*Context for the visuals*

```
[PASTE YOUR CORE CONCEPT AND PRIMARY AVATAR SUMMARY]
```

### INPUT 4: Visual Brand Guidelines (Optional)
*Any existing brand preferences*

```
[OPTIONAL: Include any brand guidelines:
- Primary colors (hex codes if available)
- Secondary colors
- Font preferences
- Visual style (minimal/bold/professional/etc.)
- Logo usage
- Any imagery to avoid]
```

---

## The Prompt

You are an advertising creative director and AI image prompt specialist. You create compelling ad copy AND precise image generation prompts that produce high-quality, on-brand visuals using Google Gemini.

**YOUR TASK:**
For each static ad asset, create:
1. Complete ad copy (primary text, headline, description)
2. Individual Google Gemini prompt for the image (one prompt per image)
3. Design specifications
4. Alt text for accessibility

**CRITICAL CONTEXT:**
- Each image prompt must be SEPARATE (Gemini produces lower quality when generating multiple images)
- Target audience is Solution-Confused (sophisticated, skeptical)
- Images should feel professional, not "stock photo" or "guru marketing"
- Visuals should support the message without being literal

---

## OUTPUT FORMAT

### SECTION 1: COLD TRAFFIC STATIC ADS

---

## AD [#]: [AD TITLE]

**AD TYPE:** Cold Traffic - [Image/Quote Card/Long Post]
**CLUSTER:** [Which cluster this targets]
**FORMAT:** [1:1 / 4:5 / 9:16]

### AD COPY

**PRIMARY TEXT:**
```
[Complete primary text - what appears above the image in the feed]
```

**HEADLINE:** (40 characters max)
```
[Headline text]
```

**DESCRIPTION:** (Optional - appears below headline)
```
[Description text if applicable]
```

**CTA BUTTON:** [Learn More / Get Free Assessment / Download / etc.]

### IMAGE SPECIFICATIONS

**CONCEPT:**
[Brief description of what the image should convey]

**VISUAL STYLE:**
[Clean/Bold/Minimal/Professional/etc.]

**TEXT ON IMAGE:** (if any)
```
[Exact text that should appear on the image]
```

**GOOGLE GEMINI PROMPT:**
```
[Complete, detailed prompt for generating this specific image. Include:
- Image type (photo, illustration, graphic design, etc.)
- Subject matter
- Composition
- Color palette
- Mood/tone
- Style references
- Text placement (if any)
- Aspect ratio
- What to avoid]
```

**ALT TEXT:**
```
[Accessibility description of the image for screen readers]
```

**FORMAT VARIANTS NEEDED:**
- [ ] 1:1 (Square - Feed)
- [ ] 4:5 (Portrait - Feed)
- [ ] 9:16 (Stories/Reels)

---

[REPEAT FOR EACH COLD TRAFFIC STATIC AD]

---

### SECTION 2: RETARGETING STATIC ADS

[Organized by category: Connection, Authority, Credibility, Activation]

---

### SECTION 3: INFOGRAPHIC SPECIFICATIONS

[For more complex visual assets]

---

### SECTION 4: QUOTE CARD TEMPLATES

[For testimonial and quote-based ads]

---

### SECTION 5: MASTER GEMINI PROMPT LIST

All Gemini prompts in sequence for easy reference:

| # | Asset Name | Type | Gemini Prompt Preview |
|---|------------|------|----------------------|
| 1 | [Name] | [Type] | "[First 50 chars of prompt...]" |
[Continue for all assets...]

---

### SECTION 6: PRODUCTION CHECKLIST

**COLD TRAFFIC STATIC ADS:**
- [ ] Ad #[X] - Image generated
[List all...]

**RETARGETING STATIC ADS:**
- [ ] Ad #[X] - Image generated
[List all...]

---

### SECTION 7: GEMINI BEST PRACTICES

**FOR BEST RESULTS WITH GOOGLE GEMINI:**

1. **One image per prompt** - Don't ask for multiple images at once
2. **Be specific** - Include style, mood, colors, composition details
3. **Specify what to avoid** - "Do not include text" / "Avoid stock photo look"
4. **Use style references** - "In the style of Apple marketing" / "Clean like Notion's design"
5. **Regenerate if needed** - First attempt may not be perfect; iterate
6. **Aspect ratio matters** - Specify 1:1, 4:5, or 9:16 explicitly

---

*Generate the complete static ad assets with all Gemini prompts now based on the inputs provided.*
```

## After Running This Prompt

1. **Open Google Gemini** (gemini.google.com)
2. **Run prompts ONE AT A TIME** (not batched)
3. **Save images** with consistent naming (Ad01_Title_v1.png)
4. **Regenerate** if needed (first try isn't always best)
5. **Add any text overlays** in Canva
6. **Upload to ad accounts** with corresponding copy

---

# PROMPT 06: PILLAR CONTENT ARCHITECT

## What This Prompt Does

This prompt creates the complete ARCHITECTURE for your manifesto-style pillar content piece. You'll receive:

- **Working title options** with recommendations
- **Core argument and paradigm shift** (one-sentence thesis)
- **Section-by-section breakdown** (10-15 sections)
- **Quotable moments map** (8-12 shareable lines)
- **Proprietary language map** (terms to introduce)
- **Story arc and tension management**
- **Competitive positioning** (how you differ from others)
- **Distribution strategy** (where to publish)
- **Writing brief** for Prompt 07

## What You'll Discover

This is not a blog post—it's your **Internet Business Manifesto moment**. Think Rich Schefren's IBB: a piece that:

- Defines the problem deeper than anyone has before
- Introduces new language/frames that spread
- Gets shared, quoted, and referenced
- Positions you as THE authority
- Converts readers by shifting their entire worldview

The architecture ensures your manifesto has the right structure, emotional arc, and strategic positioning before you write a single word.

## Required Inputs

Before running this prompt, have ready:

1. **Core Concept & Full Avatar Analysis**
2. **The Reframe/Distinction** your approach is built on
3. **Your Story** (full journey with the problem)
4. **Key Frameworks/Methodologies** (proprietary elements)
5. **Target Industry/Market Context**

## The Prompt

```
# PROMPT 06: Pillar Content Architect

## Purpose
Create the complete architecture for your "Internet Business Manifesto" style pillar content piece—a comprehensive, definitive statement of your worldview that makes the deep case for transformation. This prompt builds the structure; Prompt 07 writes the full draft.

---

## Required Inputs

Before running this prompt, paste the following from your previous outputs:

### INPUT 1: Core Concept & Full Avatar Analysis
*From your Avatar Deep Dive and Core Concept work*

```
[PASTE YOUR COMPLETE CORE CONCEPT AND AVATAR ANALYSIS - INCLUDING:
- Core Concept statement
- Primary avatar description
- Key pain points
- Gateway beliefs
- Belief Path Map (if available)
- Epiphany Units (if available)
- The transformation you facilitate]
```

### INPUT 2: The Reframe/Distinction
*The core distinction that defines your approach*

```
[PASTE THE KEY DISTINCTION YOUR APPROACH IS BUILT ON
Example: "Marketing vs. Positioning - different variables"
Example: "Tactics vs. Strategy - symptoms vs. cause"
Include any metaphors you use]
```

### INPUT 3: Your Story
*Your journey with this problem*

```
[PASTE YOUR STORY - INCLUDING:
- Your "Course Graveyard" / failed attempts
- The turning point/discovery
- How you came to understand the distinction
- Results since the shift
- Why you do this work now]
```

### INPUT 4: Key Frameworks/Methodologies
*The proprietary elements of your approach*

```
[PASTE ANY FRAMEWORKS, MODELS, OR PROPRIETARY ELEMENTS - INCLUDING:
- Named frameworks (e.g., P.R.I.M.E.™, S.P.A.R.K.™)
- Key concepts
- Unique terminology
- Any models that differentiate your approach]
```

### INPUT 5: Target Industry/Market Context
*The landscape your avatar operates in*

```
[PASTE CONTEXT ABOUT THE INDUSTRY/MARKET:
- Current state of the industry
- Common advice being given
- Why that advice fails
- The gap in the market
- Cultural/timing factors]
```

---

## The Prompt

You are a strategic content architect specializing in manifesto-style thought leadership pieces. You help experts create definitive statements of their worldview that position them as the go-to authority on their core distinction.

**YOUR TASK:**
Create the complete architecture for a pillar content piece (3,000-5,000 words when written) that:
1. Makes the deep case for why the reader has been stuck
2. Introduces the paradigm shift they need
3. Positions the expert's approach as the solution
4. Creates a line in the sand (you either get this or you don't)
5. Becomes THE definitive resource on this topic

**WHAT THIS IS:**
Think "Internet Business Manifesto" by Rich Schefren—a piece that:
- Defines the problem at a deeper level than anyone has before
- Introduces new language/frames that spread
- Gets shared, quoted, and referenced
- Positions the author as THE authority
- Converts readers by shifting their entire worldview

**WHAT THIS IS NOT:**
- A how-to guide
- A tactical resource
- A sales pitch (though it naturally positions the offer)
- Generic thought leadership

---

## OUTPUT FORMAT

### SECTION 1: MANIFESTO OVERVIEW

**WORKING TITLE OPTIONS:**
1. [Title Option 1] — [Why this works]
2. [Title Option 2] — [Why this works]
3. [Title Option 3] — [Why this works]
4. [Title Option 4] — [Why this works]
5. [Title Option 5] — [Why this works]

**RECOMMENDED TITLE:** [Your recommendation and why]

**SUBTITLE:**
[A clarifying subtitle that speaks to the avatar]

**THE CORE ARGUMENT (One Sentence):**
[The central thesis of the entire piece]

**THE PARADIGM SHIFT:**
- **FROM:** [What they currently believe]
- **TO:** [What they need to believe]

**TARGET READER STATE:**
- **Before reading:** [How they feel/what they believe]
- **After reading:** [How they feel/what they believe]

**SUCCESS CRITERIA:**
After reading this, the reader should:
1. [Outcome 1]
2. [Outcome 2]
3. [Outcome 3]
4. [Outcome 4]
5. [Outcome 5]

---

### SECTION 2: STRUCTURAL ARCHITECTURE

**TOTAL SECTIONS:** [Number]
**ESTIMATED LENGTH:** [Word count range]
**READING TIME:** [Minutes]

---

## SECTION-BY-SECTION BREAKDOWN

### SECTION 1: [SECTION TITLE]
*Purpose: [What this section accomplishes]*
*Estimated Length: [Word count]*

**OPENING HOOK:**
[The first line or concept that draws them in]

**KEY POINTS TO COVER:**
1. [Point 1]
2. [Point 2]
3. [Point 3]

**CORE ASSERTION:**
[The main claim this section makes]

**EVIDENCE/STORY TO INCLUDE:**
[What proof or narrative supports this section]

**TRANSITION TO NEXT SECTION:**
[How this section leads to the next]

---

[CONTINUE FOR ALL SECTIONS - Typically 10-15 sections]

---

### SECTION 3: QUOTABLE MOMENTS

Identify 8-12 passages that should be written as "quotable moments"—lines designed to be screenshotted, shared, and referenced.

| Location | Quotable Concept | Why It's Shareable |
|----------|------------------|-------------------|
| Section 2 | [Concept/line idea] | [Why people will share this] |
[Continue...]

---

### SECTION 4: PROPRIETARY LANGUAGE MAP

New terms or frames to introduce and define:

| Term/Frame | Definition | Section Introduced | How It's Used |
|------------|------------|-------------------|---------------|
| [Term 1] | [Definition] | Section [X] | [How it recurs] |
[Continue...]

---

### SECTION 5: STORY ARC

**THE EMOTIONAL JOURNEY:**

```
Reader starts: [Emotional state - frustrated, skeptical, curious]
     ↓
Section 1-3: [Building recognition - "this is my situation"]
     ↓
Section 4-6: [The reframe - "I've been looking at this wrong"]
     ↓
Section 7-9: [New possibility - "there's another way"]
     ↓
Section 10-12: [Resolution - "I see the path now"]
     ↓
Reader ends: [Emotional state - hopeful, determined, clear]
```

---

### SECTION 6: COMPETITIVE POSITIONING

**HOW THIS DIFFERS FROM EXISTING CONTENT:**

| Common Content | This Manifesto |
|----------------|----------------|
| [What others say] | [What you say differently] |
[Continue...]

**THE LINE IN THE SAND:**
[The clear statement that separates believers from non-believers]

---

### SECTION 7: DISTRIBUTION STRATEGY

**RECOMMENDED APPROACH:**
[Your recommendation for where and how to publish]

**REPURPOSING OPPORTUNITIES:**
1. [Opportunity 1]
2. [Opportunity 2]
[Continue...]

---

### SECTION 8: WRITING BRIEF FOR PROMPT 07

**VOICE/TONE:**
- [Descriptor 1] - not [Opposite]
- [Descriptor 2] - not [Opposite]

**STYLE NOTES:**
- [Style instruction 1]
- [Style instruction 2]

**THINGS TO AVOID:**
- [Avoid 1]
- [Avoid 2]

---

### SECTION 9: ARCHITECTURE CHECKLIST

Before moving to Prompt 07 (writing), verify:

**STRUCTURE:**
- [ ] Clear beginning, middle, end arc
- [ ] Each section has distinct purpose
- [ ] Transitions flow logically
- [ ] Total length appropriate (3,000-5,000 words)

**ARGUMENT:**
- [ ] Core thesis is clear and bold
- [ ] Supporting points build the case
- [ ] Counter-arguments addressed
- [ ] Line in the sand is clear

---

*Generate the complete pillar content architecture now based on the inputs provided.*
```

## After Running This Prompt

1. **Review the architecture** for logical flow
2. **Approve or modify** title and section structure
3. **Note the quotable moments** you want to nail
4. **Run Prompt 07** with this architecture as input

---

# PROMPT 07: PILLAR CONTENT WRITER

## What This Prompt Does

This prompt writes the complete, polished draft of your manifesto based on the architecture from Prompt 06. You'll receive:

- **Full written draft** (3,000-5,000 words)
- **Section-by-section content** with word counts
- **Quotable moments** marked for easy identification
- **Proprietary terms** bolded on first introduction
- **Word count summary** by section
- **Editing recommendations** for your refinement pass
- **Quality checklist**

## What You'll Discover

This is publication-ready content that you'll refine with your own voice. The draft is:

- **Confident but not arrogant** (authoritative without guru energy)
- **Structured for reading AND scanning** (subheadings every 300-400 words)
- **Optimized for shareability** (quotable moments throughout)
- **Naturally positioned toward your offer** (without being salesy)

The manifesto creates the paradigm shift that makes people WANT what you offer—before you even pitch it.

## Required Inputs

Before running this prompt, have ready:

1. **Complete Architecture** from Prompt 06
2. **Your Story (Expanded)** - full narrative with details
3. **Voice/Style Examples** (optional)
4. **Specific Stories/Examples** to include

## The Prompt

```
# PROMPT 07: Pillar Content Writer

## Purpose
Write the complete, polished draft of your pillar content manifesto based on the architecture from Prompt 06. This creates a publication-ready piece (3,000-5,000 words) that students can refine with their own voice.

---

## Required Inputs

Before running this prompt, paste the following:

### INPUT 1: Complete Architecture from Prompt 06
*The full output from Pillar Content Architect*

```
[PASTE YOUR COMPLETE ARCHITECTURE OUTPUT - INCLUDING:
- Title and subtitle
- Core argument
- Section-by-section breakdown
- All key points, assertions, and transitions
- Quotable moments
- Proprietary language map
- Story arc
- Writing brief]
```

### INPUT 2: Your Story (Expanded)
*Your full narrative for the piece*

```
[PASTE YOUR EXPANDED STORY - INCLUDING:
- Detailed "Course Graveyard" / failed attempts narrative
- The specific moment of discovery
- Before/after contrast
- Emotional beats
- Any specific numbers, details, anecdotes
- Client stories (with permission) to include]
```

### INPUT 3: Voice/Style Examples (Optional)
*Examples of writing you want to emulate*

```
[OPTIONAL: Paste 1-2 paragraphs of writing that represents the voice/style you want]
```

### INPUT 4: Specific Stories/Examples to Include
*Any case studies or examples*

```
[PASTE ANY SPECIFIC STORIES OR EXAMPLES YOU WANT INCLUDED:
- Client transformations
- Data points
- Industry examples
- Analogies or metaphors]
```

---

## The Prompt

You are a world-class ghostwriter specializing in thought leadership content for expert service providers. You write manifesto-style pieces that establish authors as the definitive authority on their topic.

**YOUR TASK:**
Write the complete, polished draft of a pillar content piece (3,000-5,000 words) based on the provided architecture. The piece should be:
1. Publication-ready (though the author will add their refinements)
2. Written in a voice that's authoritative but accessible
3. Structured for both reading and scanning
4. Optimized for shareability (quotable moments throughout)
5. Naturally positioned toward the author's offer (without being salesy)

**CRITICAL CONTEXT:**
This is a MANIFESTO—not a how-to guide. It should:
- Define the problem at a deeper level than anyone has before
- Introduce new language and frames
- Take a clear position (line in the sand)
- Create the paradigm shift necessary to buy
- Feel like a definitive, comprehensive treatment

---

## OUTPUT FORMAT

### THE MANIFESTO

---

# [TITLE]

## [SUBTITLE]

---

### SECTION 1: [SECTION TITLE]

[Write the complete section - typically 200-400 words]

---

[CONTINUE FOR ALL SECTIONS FROM THE ARCHITECTURE]

---

## POST-WRITING ANALYSIS

### WORD COUNT SUMMARY

| Section | Title | Word Count |
|---------|-------|------------|
| 1 | [Title] | [Count] |
| **TOTAL** | — | **[Total]** |

### QUOTABLE MOMENTS COMPILED

All quotable lines from the piece:

1. "[Quotable 1]" - Section [X]
2. "[Quotable 2]" - Section [X]
[Continue...]

### EDITING RECOMMENDATIONS

**SECTIONS THAT MAY NEED YOUR VOICE:**
- Section [X]: [Why]

**PLACES TO ADD YOUR OWN EXAMPLES:**
- Section [X]: [What kind of example]

**POTENTIAL CUTS (if length is an issue):**
- Section [X]: [Why it's cuttable]

---

## QUALITY CHECKLIST

Before delivering, verify:

**STRUCTURE:**
- [ ] Follows architecture section by section
- [ ] All key points covered
- [ ] Transitions smooth
- [ ] Length within 3,000-5,000 words

**CONTENT:**
- [ ] Core argument clear throughout
- [ ] Paradigm shift achieved
- [ ] Line in the sand is clear
- [ ] Stories integrated naturally

**STYLE:**
- [ ] Voice consistent throughout
- [ ] No jargon without explanation
- [ ] Sentences vary in length
- [ ] Reads well aloud

**SHAREABILITY:**
- [ ] 8-12 quotable moments included
- [ ] Key frames/terms are memorable
- [ ] Subheadings work as standalone ideas

---

*Write the complete pillar content manifesto now based on the architecture and inputs provided.*
```

## After Running This Prompt

1. **Read the full draft** aloud to check flow
2. **Add your personal voice** where noted in recommendations
3. **Insert your own examples** where suggested
4. **Edit for length** if needed
5. **Publish** to your blog, newsletter, or create PDF
6. **Repurpose** into social posts, email series, videos

---

# PROMPT 08: GEMINI VISUAL PROMPT GENERATOR

## What This Prompt Does

This prompt generates individual Gemini prompts for EVERY visual asset in your launch—not just ads, but everything. You'll receive:

- **Brand visual system** (colors, style, consistency notes)
- **Landing page visuals** (hero, lead magnet mockup, about section)
- **Lead magnet interior visuals** (headers, framework diagrams, decorative elements)
- **Social media profile visuals** (Facebook cover, LinkedIn banner, Instagram highlights)
- **Email visuals** (header graphic, signature)
- **Miscellaneous** (thank you page, webinar registration)
- **Master prompt reference list**
- **Generation workflow** (batching order)
- **Gemini tips** for best results

## What You'll Discover

Every visual asset in your launch can be generated with AI, but quality depends on:

- **One image per prompt** (batching reduces quality)
- **Consistent style language** (same colors, mood, references across prompts)
- **Specific instructions** (what to include AND what to avoid)

This prompt creates a complete visual asset library where everything looks cohesive and professional.

## Required Inputs

Before running this prompt, have ready:

1. **All Visual Asset Needs** (compiled from all outputs)
2. **Brand Guidelines** (colors, typography, style)
3. **Core Concept & Avatar Summary**
4. **Lead Magnet & Offer Details**

## The Prompt

```
# PROMPT 08: Gemini Visual Prompt Generator

## Purpose
Generate individual Google Gemini prompts for EVERY visual asset in your MVP launch—not just ads, but also lead magnet graphics, landing page hero images, email headers, social profile assets, and any other visuals needed. Each prompt is optimized for one image at a time (Gemini's highest quality).

---

## Required Inputs

Before running this prompt, paste the following:

### INPUT 1: All Visual Asset Needs
*Compile from all your outputs*

```
[LIST ALL VISUAL ASSETS YOU NEED - INCLUDING:

FROM LANDING PAGE:
- Hero image/graphic
- Lead magnet mockup/cover
- About section photo or graphic
- Trust badges or icons

FROM LEAD MAGNET:
- Cover page design
- Section header graphics
- Framework diagrams
- Decorative elements

FROM ADS (if not already covered in Prompt 05):
- Any remaining static ad images
- Any additional formats needed

FROM SOCIAL:
- Profile cover images
- Post templates
- Story templates

OTHER:
- Email header graphics
- Thank you page graphics
- Any other visuals needed]
```

### INPUT 2: Brand Guidelines
*Visual brand elements*

```
[PASTE YOUR VISUAL BRAND GUIDELINES - INCLUDING:
- Primary colors (hex codes if available)
- Secondary colors
- Typography preferences
- Visual style
- Imagery style
- Things to avoid visually
- Reference brands/styles you admire]
```

### INPUT 3: Core Concept & Avatar Summary
*For visual messaging alignment*

```
[PASTE YOUR CORE CONCEPT AND AVATAR SUMMARY]
```

### INPUT 4: Lead Magnet & Offer Details
*For mockup and cover designs*

```
[PASTE YOUR LEAD MAGNET DETAILS:
- Title
- Subtitle
- Key visual elements needed
- Format]
```

---

## The Prompt

You are a visual design strategist and AI image prompt specialist. You create comprehensive visual asset libraries using Google Gemini, ensuring every image is generated with its own optimized prompt for maximum quality.

**YOUR TASK:**
Create individual Google Gemini prompts for every visual asset needed across the entire MVP launch. Each prompt should:
1. Be standalone (one image per prompt)
2. Include all necessary specifications
3. Maintain brand consistency across all assets
4. Be optimized for Gemini's capabilities
5. Include usage notes for implementation

**CRITICAL CONTEXT:**
- ONE image per Gemini prompt (batch requests reduce quality)
- Target audience is Solution-Confused professionals
- Visuals should feel professional and trustworthy, not "guru marketing" or stock photo
- All assets should feel cohesive as part of one brand

---

## OUTPUT FORMAT

### SECTION 1: BRAND VISUAL SYSTEM

**COLOR PALETTE:**
- Primary: [Color name + hex]
- Secondary: [Color name + hex]
- Accent: [Color name + hex]
- Background: [Color name + hex]
- Text: [Color name + hex]

**VISUAL STYLE:**
[2-3 sentences describing the overall visual style]

**CONSISTENCY NOTES:**
[What elements should remain consistent across all assets]

---

### SECTION 2: LANDING PAGE VISUALS

## VISUAL LP-01: Hero Image/Background

**PURPOSE:** Main visual on landing page above the fold
**DIMENSIONS:** 1920x1080 (desktop) + 1080x1920 (mobile version)

**GOOGLE GEMINI PROMPT:**
```
[Complete, detailed prompt]
```

**IMPLEMENTATION NOTES:**
[How to use this image]

---

[Continue for all landing page visuals...]

---

### SECTION 3: LEAD MAGNET INTERIOR VISUALS

[Individual prompts for all lead magnet graphics]

---

### SECTION 4: SOCIAL MEDIA PROFILE VISUALS

[Facebook cover, LinkedIn banner, Instagram highlights, etc.]

---

### SECTION 5: EMAIL VISUALS

[Header graphic, signature graphic]

---

### SECTION 6: MISCELLANEOUS VISUALS

[Thank you page, webinar registration, etc.]

---

### SECTION 7: MASTER PROMPT REFERENCE LIST

| # | Asset Code | Asset Name | Dimensions | Preview of Prompt |
|---|------------|------------|------------|-------------------|
| 1 | LP-01 | Hero Image | 1920x1080 | "Create a professional..." |
[Continue for ALL visuals...]

**TOTAL VISUALS:** [X] images to generate

---

### SECTION 8: GEMINI GENERATION WORKFLOW

**RECOMMENDED ORDER:**

**Batch 1: Core Brand Visuals (Do First)**
- [ ] LP-01: Hero Image
- [ ] LP-02: Lead Magnet Cover
- [ ] SM-01: Facebook Cover
- [ ] SM-02: LinkedIn Banner

**Batch 2: Lead Magnet Visuals**
- [ ] LM-01 through LM-XX

**Batch 3: Email & Miscellaneous**
- [ ] EM-01, EM-02
- [ ] MISC-01, MISC-02

---

### SECTION 9: GEMINI TIPS FOR BEST RESULTS

**GETTING CONSISTENT STYLE:**
- Same color palette description in every prompt
- Same style references
- Same mood descriptors

**ITERATING ON RESULTS:**
1. Regenerate with same prompt (often gives different result)
2. Add more specific descriptors
3. Include "Do not include [problematic element]"
4. Reference specific styles

**HANDLING TEXT IN IMAGES:**
- Generally, ask Gemini to NOT include text
- Add text afterward in Canva for full control

---

### SECTION 10: PRODUCTION CHECKLIST

**LANDING PAGE VISUALS:**
- [ ] LP-01: Hero Image - Generated ☐ Approved ☐
- [ ] LP-02: Lead Magnet Cover - Generated ☐ Approved ☐
[Continue...]

**LEAD MAGNET VISUALS:**
- [ ] LM-01: [Name] - Generated ☐ Approved ☐
[Continue...]

---

*Generate all Gemini visual prompts now based on the inputs provided.*
```

## After Running This Prompt

1. **Follow the generation workflow** (core visuals first)
2. **Open Gemini** and run prompts one at a time
3. **Save consistently** (AssetCode_Description_v1.png)
4. **Regenerate** if needed (don't settle for first result)
5. **Add text overlays** in Canva where needed
6. **Check for consistency** across all assets

---

# PRODUCTION CHECKLIST

## Foundation Layer
- [ ] Prompt 01: Landing Page Copy - GENERATED
- [ ] Prompt 02: Lead Magnet Content - GENERATED
- [ ] Landing page built and live
- [ ] Lead magnet designed in Canva
- [ ] Lead magnet uploaded to email system

## Traffic Layer
- [ ] Prompt 03: Video Inventory - GENERATED
- [ ] Videos selected for scripting (#__)
- [ ] Prompt 04: Video Scripts - GENERATED
- [ ] Videos recorded
- [ ] Videos edited with captions
- [ ] Prompt 05: Static Ads - GENERATED
- [ ] Static ad images generated in Gemini
- [ ] Ads uploaded to ad accounts

## Authority Layer
- [ ] Prompt 06: Pillar Architecture - GENERATED
- [ ] Architecture reviewed and approved
- [ ] Prompt 07: Pillar Content - GENERATED
- [ ] Content edited with your voice
- [ ] Content published

## Visual Layer
- [ ] Prompt 08: Visual Prompts - GENERATED
- [ ] All visuals generated in Gemini
- [ ] Visuals implemented across all assets

---

*Workbook Complete — December 2025*
*Zenith Pro Lesson 8: Asset Production*
