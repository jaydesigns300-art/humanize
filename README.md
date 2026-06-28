# Humanize

A Claude skill that makes AI-written text sound like a person wrote it.

## The problem

AI writing has tells. Not just "delve" and em dashes — those are the obvious ones. The real signals are subtler: uniform sentence rhythm, copula replacement ("serves as" instead of "is"), significance inflation sentences that say nothing, era-specific vocabulary that shifts every 6-12 months as new models drop.

Recruiters notice. Hiring managers notice. Anyone who reads a lot of LinkedIn notices.

## What this does

Paste any text into Claude. Humanize strips the tells and rebuilds the prose the way a person actually writes it — with variable rhythm, specific numbers instead of vague quantities, and the small imperfections that make writing feel real.

Works on: cold emails, LinkedIn posts, cover letters, portfolio copy, case study narratives, thank-you notes, recruiter outreach, anything a human will read and judge.

## How to install

1. Download `humanize.skill` from this repo
2. Open Claude at claude.ai (requires a Claude account)
3. Go to Settings > Skills
4. Drag the file in

## How to use

Write or paste your text in Claude and say "humanize this" or "rewrite this." The skill fires automatically on any writing task.

## What it strips

- Era-specific AI vocabulary (the list changes as models evolve — current version covers GPT-4 through GPT-5 era tells)
- Em dashes and double hyphens (hard ban, zero exceptions)
- Copula replacement ("serves as", "stands as", "boasts")
- Significance inflation ("pivotal", "testament to", "evolving landscape")
- Negative parallelism ("not just X, but Y")
- Rule-of-three structural lock
- Weasel attributions ("experts argue", "observers note")
- Uniform sentence rhythm

## What it rebuilds

- Sentence burstiness (short next to long)
- Concrete specifics instead of vague quantities
- Controlled imperfection
- Endings that land on a fact, not a lesson

## Built by

Jay Hari Nair — Senior Product Designer, ADPList Top 50 Mentor, Figma community contributor.

## Updates

When AI vocabulary patterns shift, the skill gets updated here. Watch the repo to get notified.
