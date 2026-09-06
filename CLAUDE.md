# Content Bank

A running capture system for content ideas, format patterns, and timely angles — fed by inputs (saves, trends, news, personal frictions) and turned into a weekly filming plan.

## Niche

**Phygital & Spatial Design Strategy** — bridging physical architectural principles with digital UX/3D experiences, documented in real time while building an independent design studio in Asia.

- **Core focus:** multi-disciplinary spatial design — where physical spaces, 3D web environments, and digital product UX intersect.
- **Audience:** emerging designers, tech/design founders, spatial enthusiasts, and creative peers who value architectural rigor and independent studio culture.
- **Unique angle:** 6 years combining spatial architecture and UX design, told through candid, high-energy storytelling from Hong Kong rather than corporate formality.
- **Primary output:** the Portfolio Triad (Local Bakery Rebrand, 3D Product Website, FIELD Phygital App) shown alongside fast, high-value 3D/UI micro-tutorials.

## Content style

Candid, high-energy voiceovers about moving from the West to Asia to build an independent studio, paired with bright, minimal visuals that show physical spatial design, digital UX, and subtle tactile micro-animations.

## Tags

Every entry is tagged as exactly one of:

- **idea** — a specific, filmable post concept
- **pattern** — a format/structure that's working (repeatable mechanic, not a one-off topic)
- **angle** — a timely take or point of view tied to a trend/news/moment

## Commands

### `log this: <raw input>`

Capture the input as a single tagged entry. Extract:

- **Tag**: idea / pattern / angle
- **Friction**: the specific tension, problem, or observation driving this (why it's worth saying)
- **Hook**: a first-3-seconds line, written in the candid/high-energy voice
- **Format**: how it gets filmed (e.g. talking-head voiceover, 3D screen-record micro-tutorial, before/after B-roll, studio-build vlog beat)
- **Audience**: who this specific entry is for, within the broader niche audience

Append the entry to `entries.md` under today's date (create the date heading if it doesn't exist), using the entry template in that file. Then **reply with the tagged entry only** — no extra commentary.

### `weekly review`

Read all entries logged in `entries.md` from the last 7 days. Organize into:

1. **Ideas** — up to 5 filmable posts, ranked by urgency. For each: cover line, hook (first 3 seconds), why now.
2. **Patterns** — 2 formats currently working, with evidence from the week's logged entries.
3. **Angles** — 3 timely takes for the niche (phygital/spatial design strategy), tied to what's actually trending or was logged this week.

Write the result to `reviews/YYYY-MM-DD.md` (using the review date) and also present it in chat.

## Files

- `entries.md` — append-only log, newest date on top. Source of truth for weekly reviews.
- `reviews/` — one file per completed weekly review.
