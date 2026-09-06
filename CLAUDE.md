# Content Bank

A running capture system for content ideas, format patterns, and timely angles — fed by inputs (saves, trends, news, personal frictions) and turned into a weekly filming plan.

**Storage: Notion only.** This repo holds the spec, not the data. All logging and reviews happen in Notion via the Notion MCP tools — do not write to local files for this workflow.

## Notion locations

- **Content Bank** (parent page): https://app.notion.com/p/3d3cf370751281d694c1edf9c39ec4bd
- **Entries** (database — log all entries here): https://app.notion.com/p/938e6d1465964771a063a5c04449aa2b
  - Data source id: `collection://842632b5-e4b8-45a9-b35f-1d2e61b99c20`
  - Schema: `Name` (title), `Tag` (select: Idea/Pattern/Angle), `Friction` (text), `Hook` (text), `Format` (text), `Audience` (text), `Urgency` (select: High/Medium/Low), `Status` (status), `Date Logged` (date)
- **Weekly Reviews** (sub-page, one child page per review): https://app.notion.com/p/3d3cf370751281fabca9d2dc6e3df483

If the Notion MCP connector isn't available in a session, say so rather than falling back to a local file.

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

- **Tag**: Idea / Pattern / Angle
- **Friction**: the specific tension, problem, or observation driving this (why it's worth saying)
- **Hook**: a first-3-seconds line, written in the candid/high-energy voice
- **Format**: how it gets filmed (e.g. talking-head voiceover, 3D screen-record micro-tutorial, before/after B-roll, studio-build vlog beat)
- **Audience**: who this specific entry is for, within the broader niche audience
- **Urgency**: High / Medium / Low (for weekly ranking)
- **Date Logged**: today
- **Status**: Not started

Create the page as a new row in the Entries data source above. Then **reply with the tagged entry only** — no extra commentary.

### `weekly review`

Query the Entries data source for rows with `Date Logged` in the last 7 days. Organize into:

1. **Ideas** — up to 5 filmable posts, ranked by urgency. For each: cover line, hook (first 3 seconds), why now.
2. **Patterns** — 2 formats currently working, with evidence from the week's logged entries.
3. **Angles** — 3 timely takes for the niche (phygital/spatial design strategy), tied to what's actually trending or was logged this week.

Create the result as a new sub-page under **Weekly Reviews**, titled with the review date, and also present it in chat.
