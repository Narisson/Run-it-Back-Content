---
name: brand-teardown
description: Analyze another brand's content strategy from Instagram (or any social platform) to learn what makes it work and what Run it Back should steal or avoid. Use when the user shares screenshots of a profile/grid/post, pastes captions, bios, or metrics, gives a creator/brand handle to break down, or asks to study a competitor, teardown a page, or reverse-engineer a content strategy. Keywords: brand teardown, competitor analysis, content strategy, reverse engineer, study this page, analyze this account, what are they doing.
---

# Brand Teardown

Reverse-engineer another brand's content strategy so Run it Back can learn from it. Every teardown runs through the same strategic lens and ends with concrete, Run-it-Back-specific moves.

## Run it Back context (the lens)

Read this before writing recommendations — it grounds the "steal / avoid" section. Update it as the brand solidifies.

- **Spine (the hero):** the **inner game** — discipline strategies, building resilience, mental strength, willpower. This is what Run it Back teaches.
- **Proof-grounds:** health and wealth are the two arenas where the discipline is applied/demonstrated — not co-equal topics.
- **Positioning:** *the inner game of coming back* — whatever happened yesterday, run the play again with more discipline and will.
- **Format (current bet):** semi-faceless, short-form video first, across IG / YouTube / X / TikTok, plus a website. Plan: recorded video overlaid with a Higgsfield-generated character persona.
- **Money model:** affiliate first (niche products), own products later (digital → physical). The real asset is **trust** and an **owned email audience**, because both affiliate clicks and product sales convert on trust.
- **Brand fit test:** does this survive "discipline / resilience / mental strength / willpower"? If a tactic or product wouldn't, flag it as avoid.

## Inputs

There is **no Instagram MCP** connected, and IG pages are login-walled, so don't try to fetch profiles from a URL. Work from what the user provides:

1. **Screenshots** (best) — profile grid, bio, individual posts, reel view counts, story highlights. Read them directly.
2. **Pasted text** — captions, hooks, bio, link-in-bio destinations, follower/engagement numbers.
3. **A handle with no assets** — ask for at least a grid screenshot + 2–3 top posts before analyzing. Do not invent data you can't see.

If given a handle but no visuals, ask for screenshots rather than guessing. Never fabricate metrics, captions, or post counts — analyze only what's observable, and say when something is unknown.

## Two modes

Pick based on the user's ask; default to **quick** unless they say "deep", "full", or "teardown".

- **Quick scan** — a tight one-pager: positioning in a sentence, top 3 content pillars, the hook pattern, cadence/format, how they monetize, and 3 steal/avoid moves. Use for a fast read or when assets are limited.
- **Deep teardown** — the full framework below, every dimension, with specific post examples cited from what was shared.

## The framework (deep mode)

Cover each dimension. Cite specific posts/screenshots as evidence — no generic claims.

1. **Positioning** — Who is this for? What's the core promise? What's the one-line differentiator vs. others in the niche?
2. **Content pillars** — The 3–5 recurring topic buckets, and the rough ratio between them. Which pillar drives the most reach?
3. **Hook formulas** — How do the first 1–2 seconds (video) or first line (caption) grab attention? Name the repeatable patterns (contrarian take, number, callout, curiosity gap, etc.).
4. **Format & cadence** — Reels vs carousels vs static vs stories. Posting rhythm. Any recurring series or franchises. Video length, pacing, editing style, captions/text-on-screen.
5. **Voice & visual system** — Tone (drill-sergeant? calm mentor? hype?). Palette, typography, thumbnail/cover style, logo/watermark usage, overall consistency.
6. **Funnel & monetization** ← *most important.* Bio link + destination, lead magnets, email capture, affiliate patterns (what they push and how), product ladder (digital/physical), sponsorships. Trace the path from a viewer to a dollar.
7. **What's working** — The outlier posts (highest views/engagement relative to their norm) and a hypothesis for *why* they popped. This is the highest-signal part.

## Output

Save every teardown as a markdown file in `teardowns/`:

- Filename: `teardowns/<brand-handle>-<mode>-<yyyy-mm-dd>.md` (e.g. `teardowns/atomicshredding-deep-2026-07-01.md`). Get the date from the environment context; if unknown, ask.
- Start the file with a one-line summary and the source (what assets were analyzed).
- For deep mode, use the seven framework headings above.
- **Always end with the section below**, in every mode.

### Required closing section — "Steal / Avoid for Run it Back"

Translate the analysis into concrete moves. Three buckets, bullet points, specific and actionable:

- **Steal** — tactics to copy directly (they fit the niche and the trust/money model).
- **Adapt** — good ideas that need reshaping to fit faceless format, the discipline spine, or the affiliate/product goal.
- **Avoid** — what not to copy, and why (off-ethos, trust-eroding, platform-dependent, or won't work faceless).

Keep this section decisive — recommendations, not options.

## After saving

1. **Feed the knowledge base** in `knowledge-base/` — this is required, not optional:
   - Add a row to `knowledge-base/pages-index.md` (stats, niche, ownership columns, money model, key lesson).
   - If the teardown shifts the pattern or thesis, update `knowledge-base/monetization-playbook.md` and `knowledge-base/brand-direction.md` (append to its decisions log).
2. Report the file path and give a 3-bullet verbal summary of the biggest takeaways.
3. Commit the teardown **and** the knowledge-base updates to the working branch.
