# PROMPT 05: Static Ad Asset Generator

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
