---
name: executive-intelligence-brief
description: Produces a concise, source-cited C-suite competitive-intelligence brief from verified events, materiality decisions, entrant assessments, and strategic implications. Use for board updates, market snapshots, leadership emails, or recurring product-intelligence reports.
license: MIT
compatibility: Requires structured evidence and analysis from upstream skills; no research should be invented during drafting.
metadata:
  category: competitive-intelligence
  role: reporting
---

# Executive Intelligence Brief

## Objective

Create a short report that leads with decisions and preserves evidence quality.

## Required structure

Use exactly these sections unless the user specifies another format:

**BOTTOM LINE** — Two or three sentences stating what changed for the focal product. If nothing material changed, say so.

**BOARD-LEVEL (act or decide now)**

For each item:

- **Headline:** Specific and quantified where possible
- **Who:** Company or entity
- **What happened:** One or two factual sentences with dates, amounts, endpoints, versions, geography, or decision status
- **Evidence status:** Confirmed, corroborated, or company-announced
- **So what for {{PRODUCT}}:** One or two sentences tied to share, access, positioning, economics, or timing
- **Recommended action:** Concrete next step and owner when available
- **Source:** Publisher, exact title, publication date, direct URL

**WATCH (monitor, no action yet)**

Use the same fields, replacing Recommended action with:

- **Trigger to escalate:** Observable milestone that moves the event to Board-level

**PARTNERS**

Create one subsection for each configured partner, including `No material partner events.` when applicable. State whether implications are favorable, adverse, or mixed.

**POSSIBLE NEW ENTRANTS**

For each entrant include identity, asset or mechanism, current stage, latest dated milestone, evidence status, threat credibility, rationale, and source. If none qualify, write `None detected this period.`

**WHAT I COULD NOT CONFIRM**

State what was referenced, where, what evidence was missing or conflicting, and why it was excluded. If empty, write `Nothing.`

## Writing rules

- Every factual claim receives an inline citation or adjacent source field.
- Include publication dates.
- Label pre-period facts `[BACKGROUND]`.
- Do not turn company claims into verified facts.
- State source conflicts and cite both.
- Do not repeat the same event across sections.
- Do not include Exclude items.
- Write `No material events.` for an empty Board or Watch section.
- Do not pad the report.

## Style

Lead with conclusions. Use plain, precise language suitable for senior leaders. Avoid market clichés, unsupported adjectives, generic recommendations, and vague phrases such as “could impact the market.”

## Final check

Compare the draft against `assets/executive-brief-template.md`. Verify the date range, section completeness, source metadata, evidence labels, partner coverage, entrant coverage, and uncertainty disclosure.
