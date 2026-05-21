# Ad Copy Writer — Complete Meta Ad Copy Sets with Engineered CTAs

**Write 8–12 scored Meta ad copy sets through a 6-step research-to-copy pipeline — with CTA engineering as a first-class creative step, not an afterthought.**

The Ad Copy Writer takes a product and builds a complete ad copy library: primary text (with the 125-character fold marked), headlines, descriptions, verbal CTAs, CTA button recommendations, and a testing matrix. Every copy set traces back to real conversion research, and every CTA is deliberately engineered using one of 8 frameworks. This is skill 5 of 10 in the AI Skills for Media Buyers series.

## Install

**Claude Desktop (Cowork):**
Download the `.skill` file from [Releases](https://github.com/the-baweja/ad-copy-writer/releases) → Open Claude Desktop → Settings → Skills → Drop the file in.

**Claude Code:**
```bash
git clone https://github.com/the-baweja/ad-copy-writer.git ~/.claude/skills/ad-copy-writer
```

**Manual:**
Clone into any directory your Claude skills configuration points to.

## What It Does

The skill follows a 6-step pipeline where each step feeds the next:

1. 📋 **Brief & Hook Import** — Organize the product, audience, offer, and working hooks into a copy-ready brief
2. 🔍 **Offer & Conversion Research** — Mine reviews, Reddit, and social comments to map purchase triggers, objections, and trust signals
3. 🏗️ **Body Copy Architecture** — Assign body frameworks (PAS, Storytelling, Educational, UGC-style, Premium, Comparison, Urgency, Social Proof Stack) based on the conversion map
4. 🎯 **CTA Engineering** — Design 3-layer CTAs: verbal CTA in the copy, Meta button selection, and urgency mechanism — using 8 CTA frameworks (Benefit-forward, Curiosity, Risk-reversal, Social proof, Specificity, Urgency, Challenge, Education)
5. ✍️ **Copy Generation** — Write 8–12 complete copy sets with primary text (125-char fold marked), headline (<40 chars), description (<30 chars), and architecture trace
6. 📊 **Scoring & Testing Matrix** — Score each set on a 6-factor rubric (Hook-to-Body Flow, Proof Strength, Objection Handling, CTA Strength, Specificity, Emotional Trajectory) and build a testing plan with isolated variable comparisons

## Output

Branded DOCX report containing:

- Step 1: Creative Brief with product, audience, offer, and working hooks
- Step 2: Conversion Map table (purchase triggers, objections, trust signals, copy implications)
- Step 3: Body Copy Architecture table (framework assignments for all sets)
- Step 4: CTA Engineering table (8 CTA frameworks mapped to sets with rationale)
- Step 5: Copy Sets — top-scoring first, then full library with 125-char marks, headlines, descriptions, verbal CTAs, and score breakdowns
- Step 6: Testing Matrix with isolated variable comparisons (which sets test framework, which test CTA, which test tone)
- CTA Testing Guide for post-launch optimization

## Customize Your Branding

Edit `references/branding.md` to replace the default brand colors, typography, and document structure with your agency's or client's branding. The DOCX generation follows whatever branding reference you provide.

## Example

**Prompt:** "Write ad copy for Liquid Death"

**Output:** 10 scored copy sets across 8 body frameworks and 8 CTA frameworks. Top set scored 4.5/5.0. Includes isolated variable comparisons: Sets 1 vs 7 test PAS vs Comparison on the same hook. Sets 4 vs 9 test Challenge vs Risk-reversal CTA on UGC-style copy. Full testing matrix with Wave 1/2/3 priorities.

## Who This Is For

Media buyers, creative strategists, brand owners, and performance marketers who want complete ad copy packages — not just headlines, but static image creative and video scripts — built through a systematic pipeline.

This is skill 5 of 10 in the **AI Skills for Media Buyers** series by [Baweja Media](https://bawejamedia.com).
## Want Baweja Media to audit your ad account and explore opportunities to work together?

[→ Book a free strategy call](https://webinar.sannidhyabaweja.com/vsl-lp-ind)

---

Built by [Baweja Media](https://bawejamedia.com) · MIT License
