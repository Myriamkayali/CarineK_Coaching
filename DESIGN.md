# DESIGN.md — Carine | Self-Talk Editor

Locked design system for this project. Follow this exactly. Do not substitute
defaults for any value left unspecified here without asking first.

## Direction

Editorial. Manuscript. Quiet authority. This is a page for someone who edits
sentences for a living, not a wellness brand. The reader should feel like
they've opened a well-made notebook, not landed on a SaaS product page.

Explicitly avoided, and why:
- Cream (#F4F1EA) + terracotta accent — the single most common AI-generated
  tell. Banned outright.
- Near-black (#0B0B0B) + neon accent — reads as tech/SaaS, wrong register
  for a calm observer brand.
- Identical rounded cards with soft grey shadows — the generic "SaaS card
  kit." The three pricing tiers must be differentiated by more than color,
  not just three clones of one card component.

## Color

| Name | Hex | Role |
|---|---|---|
| Paper | `#FAF8F4` | Primary background. Warm true white, not cream. |
| Ink | `#1C1B19` | Primary text. Warm near-black, not pure #000 or #0B0B0B. |
| Manuscript Blue | `#35526B` | The ONE accent. CTA buttons and the "Most popular" badge only. Nowhere else. |
| Margin Grey | `#8A8680` | Secondary text, captions, meta. |
| Rule | `#D8D4CC` | Hairline dividers only. 1px, never bolder. |

Rule: if you're reaching for a second accent color anywhere on the page, stop
and use Ink or Margin Grey instead.

## Typography

- **Display / headlines / pull quotes:** a warm literary serif with real
  character — Fraunces, Canela, or Tiempos Headline. Not Georgia, Times, or
  a generic system serif.
- **Body:** a quiet, well-spaced sans — Inter or Söhne. Generous line-height
  (1.6+), max ~70 characters per line.
- One type scale, used with intent. No decorative tracked-out ALL-CAPS
  eyebrow labels above sections. No middle-dot meta strings except the one
  Carine wrote herself in the subline ("Carine — Self-Talk Editor · The Word
  Swap Method") — that one stays, because it's her copy, not template chrome.

## Layout

- Left-aligned by default, not centered. This should read like a manuscript
  page, not a poster.
- Generous margins. Allow asymmetry where it serves content (e.g. the About
  section text column can sit offset against whitespace rather than
  centered).
- ONE corner-radius system for the entire page — pick sharp (0px) or soft
  (small, consistent radius) and hold it everywhere, including buttons,
  cards, and the email capture field.
- Numbered markers (01 / 02 / 03) are earned ONLY by the 3-step Method
  section, because that's an actual sequence. Do not reuse numbering
  anywhere else on the page.
- The three pricing cards should NOT be three identical containers with only
  text swapped. Differentiate the top tier ("Most popular") through the
  accent border + badge specified in the brief, and let card padding/weight
  carry hierarchy, not just color.

## Motion

- One deliberate reveal on page load — the hero headline setting in. That's
  it.
- No fade-and-slide-up on every section as you scroll. No hover-lift on
  every card. Motion answers a person's action (opening the FAQ, hovering
  a button) or marks one considered moment, not a repeated pattern applied
  uniformly.

## Explicitly banned

- Tracked-out ALL-CAPS labels
- Arrows appended to link/button text ("Book a session →")
- More than one accent color anywhere on the page
- Mixed corner-radius systems (sharp buttons + soft cards, etc.)
- Generic system serif (Georgia/Times) standing in for the "warm literary
  serif" requirement

## Voice check for on-page copy

Short sentences. No exclamation points. No "YOU GOT THIS." She notices
patterns before she names them — copy should sound observational, not
motivational. No em dashes (replace with periods or commas).
