# Anti-Ai-Slop-SKill-for-agents

A skill that detects and eliminates "AI slop" aesthetics from frontend UI — websites, landing pages, dashboards, components, and any web interface.

## What is AI slop?

AI slop in UI is **distributional convergence**: models trained on millions of "modern SaaS" sites collapse to the statistical average — purple gradients, rounded-2xl cards, Inter at 64px, three-feature grids. The output is technically polished but has no opinion, no friction, no specificity. Real products have weird corners that betray actual users. AI output is smooth because it's averaged.

This skill resists the average. Every default the model wants to reach for is suspect.

---

## What this skill does

- Runs a pre-flight slop checklist before generating any HTML, CSS, React, or Tailwind code
- Scores existing UI on a 10-dimension, 30-point rubric and surfaces the highest-leverage fixes
- Commits to a deliberate aesthetic direction per project (brutalist, editorial, Swiss, terminal, maximalist, photographic, documentary) — and holds to it
- Eliminates banned copy patterns ("Seamlessly," "Unleash," "Transform your workflow") and replaces them with specific, opinionated language
- Enforces full state coverage: empty, loading, error, edge, zero states — not just the happy path

---

## The 4 root causes of slop

Every slop tell traces back to one of these:

1. **No hierarchy** — everything is the same weight, so nothing leads the eye
2. **No specificity** — generic copy, generic visuals, no concrete numbers or named entities
3. **No restraint** — gradients + glassmorphism + neon + emoji + 3D + animation, all at once
4. **No opinion** — the design could belong to any company; no aesthetic risk taken

If a fix doesn't address one of these four, it's cosmetic.

---

## Slop scoring rubric

Score each dimension 0–3 (0 = clean, 3 = pure slop):

| # | Dimension |
|---|-----------|
| 1 | Visual signature — gradients, glassmorphism, default Tailwind palette |
| 2 | Typography — single font, no hierarchy, walls of body text |
| 3 | Hero pattern — centered headline, two buttons, vague subtitle |
| 4 | Feature blocks — three-card grid with parallel headlines and emoji icons |
| 5 | Copy register — buzzwords, no numbers, no named entities |
| 6 | Structural skeleton — generic SaaS page anatomy in default order |
| 7 | Social proof — fake testimonials, placeholder logos |
| 8 | State coverage — only happy path, generic spinners |
| 9 | Specificity — would this design fit any company in any industry? |
| 10 | Aesthetic commitment — clear direction, or a blend of trends? |

**0–7** = strong · **8–15** = workable · **16–23** = slop · **24–30** = pure AI slop

---

## Usage triggers

Load this skill when the user says things like:

- "make this not look AI-made"
- "remove the v0 vibes"
- "looks like ChatGPT built it"
- "feels too generic"
- "build a landing page / dashboard / hero section"
- "review my UI"
- "de-slop this"

Also triggers automatically before any frontend code generation, even without an explicit request.

---

## How to use

Using this skill is incredibly simple. You don't need any special extensions or plugins. 

If you are using the standard Claude.ai web interface, ChatGPT, Cursor, or any other AI tool, simply open the **`SKILL.md`** file in this repository, copy all the text, and paste it directly into your "Project Instructions", "Custom Instructions", or "Rules for AI".
---

## The meta-rule

> Before shipping any frontend output, ask: **"What did I do here that another AI wouldn't have done by default?"** If the answer is nothing, restart.

---

**Created by Krishivag**
