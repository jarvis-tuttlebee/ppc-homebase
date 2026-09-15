# Content layers + intentional pipeline — plan

Status: **building** — taxonomy locked 2026-09-14; **weekly cadence locked 2026-09-15**. Mix chips live on the calendar (Marketing **0.12.94** local). Branding PDF volume table is outdated. Build only inside existing Marketing (calendar + pipeline) — no side pages.

Live baseline: Marketing **0.12.91**.

---

## Problem

Content is often found as “looks good → make → post” without a clear job. That weakens motivation and the content itself. Feedback asked for intention early: every piece should know **why** it exists and which **layer** it serves.

### Team feedback (Louis) — why this matters
- Tell people what they are looking at / what it is saying.
- Everything has intention.
- Random aesthetic posts can be fine as world/identity — but a shop button flips the job to **conversion** and needs more consideration.
- Context matters (e.g. CTA after a fit-check vs the same frame alone).
- Comes back to the branding doc: purpose / intention / category (world build, conversion, etc.) — layers carry inherent intention; the **Why** field spells the specific post’s job.

---

## Locked: content layers (2026-09-14)

Confirmed with Jarvis. Adjust later if needed; do not invent parallel names in the product.

| # | Layer | Job (plain English) | Deck primary → secondary |
|---|---|---|---|
| 1 | **Audience acquisition** | Stop a stranger mid-scroll; introduce Press Play | Brand discovery → Aesthetic recognition |
| 2 | **Brand identity** | Prove craft + deepen bond for people already watching | Trust building → Cultural positioning |
| 3 | **Conversion** | Help someone decide to buy | Sale → Purchase activation |

**Considered and not used (for now):** Prep columns named World building / Conversion / Retention. “World building” is real work but mostly sits under **Brand identity** (and sometimes acquisition aesthetics). **Retention** is not in the branding deck — revisit later if needed.

**Clarifications:**
- Acquisition ≠ all marketing — it means *new eyes* only.
- Aesthetic recognition vs identity can feel similar (both “world-ish”); the split is **who it’s for** (cold vs already following), not whether it looks branded.
- Deck Week 1–4 reel/carousel quotas = reference only; weekly mix stays editable.

---

## Weekly targets (planning 2026-09-15)

Capacity still: **Mon/Tue/Thu/Fri × ~1.5h**, IG + TikTok, 1 considered Post/Reel is realistic. Those are **how**. The week scoreboard is **why** (layers). Numbers are **editable per week** — not frozen constants.

### Primary — layer mix (the week’s job)

Each week has three **counts**, not typed percentages. % is just what the counts add up to.

| | Acquisition | Identity | Conversion |
|---|---|---|---|
| **Steady default** | **2** | **2** | **1** |
| **Selling / drop week** | 1–2 | 1–2 (never 0) | **1–2** (you raise this) |

Steady ≈ 40% Acquisition / 40% Identity / 20% Conversion. We do **not** type percentages in the UI — they are just what 2 / 2 / 1 add up to.

**UI (calendar, above the grid)**  
Replace Make today / Post today with three chips for the **focused week**:

`This week · 14–20 Sep`  `[Acquisition 0/2]` `[Identity 0/2]` `[Conversion 0/1]`  `[Needs · 7d]`

- Default every week: **2 / 2 / 1** until you edit that week.
- Click the **target** (the number after `/`) to change this week only.
- Week view: chips follow Prev/Next.
- Month view: click a week row (empty space) to focus it; that week gets a light highlight so you know which mix you are editing.
- No % on the chips. The work is: make pieces that actually meet each layer (Layer + Why on the card).

**What fills a layer**
- Any **dated** calendar card with that layer (Story, Post, Reel, TikTok)
- Empty Need with a layer counts as **planned**
- No layer → counts toward nothing (that’s the leftover to assign)
- Same video as Reel + TikTok = **one** piece (don’t double the mix)

Stories have to carry layer. One Post/Reel cannot be 50/50/20 on its own.

### Secondary — how (formats) — not the scoreboard

Decide **after** the mix is set, per card: Story vs Post vs Reel (TikTok = usually the Reel file).

Quiet constraint to keep (not the headline): **at least one Post or Reel** in the week if you can — that’s the considered piece. Stories do the volume. We’ll add format hints later so the strip doesn’t become Stories/Post/Reel quotas again.

### Time-out
1. Assign layers so the three counts are honest  
2. Keep one Post or Reel if you can  
3. Cut stories toward 2 before you drop the mix to blank

---

---

## Product decisions (agreed direction)

### 1. Idea + Why (coexist)
- Keep **Idea** text box as today.
- Directly under it: **Why / Intention** — what this post is meant to say or do.
- Visible on Ideas, Prep, Exec; on Calendar under the pipeline idea summary; shown in Review context.

### 2. Layer on the card (Category + Format stay)
- **Category/Pillar** and **Format** stay (channel / shape).
- New **Layer** prop under Format: Audience acquisition / Brand identity / Conversion.
- Editable on Ideas (before Prepare), Prep, Exec, Review, Calendar — same field everywhere.
- Prepare requires a Layer.

### 3. Prep columns = layers
- Preparation board columns are **Audience acquisition | Brand identity | Conversion** (replacing Instagram / TikTok / Pinterest / Email / Ads / Website columns).
- Dragging between Prep columns sets `contentLayer`.
- Platform/format remain on the card for calendar Needs and publish logistics.

### 4. Optional Hook (pill) — later
- Same pattern as Execution’s Products / Location / Requirements: `+ Hook` → text field → removable.
- **Mainly for Reels and TikToks** — not in this pass.

Open design detail when building:
- Where do Email / Ads / Website cards live if Prep is layer-first? Options: (a) still tag format+pillar on the card and filter; (b) keep a thin “Other channels” area; (c) layer columns only for Organic feed/stories work first. Prefer (a) unless it gets noisy.

### 5. Weekly layer targets (settings above calendar)
- Per week: editable **Acquisition / Identity / Conversion** counts in the triage chips (where Make today / Post today were). See **Weekly targets** above.
- Format (Story / Post / Reel) is how, not the scoreboard. Do not bring back Stories/Post-Reel quotas as the headline.

### 6. Idea-finding guided by deficit
- Discover / Ideas workflow: surface **what this week is short on**.
- Short Acquisition → visual/motion/aesthetic that introduces cold.
- Short Identity → fabric, sew, pattern, studio, community.
- Short Conversion → garment breakdown, fit, stock, product-led lifestyle.

### 7. Two clocks (don’t conflate)
- Stories = presence on content days. Feed make = **1 IG Post or Reel** (TikTok = same Reel when possible).
- Existing Mon/Thu grid days can host the Post/Reel; stories on Mon/Tue/Thu/Fri. Layers answer *why* for that make only.

---

## Suggested build phases

### Phase A — Card fields (smallest useful)
1. Add **Layer** + **Intention/Why** on idea → prep → calendar (sync like other body fields).
2. Add optional **`+ Hook`** pill (Reel/TikTok-oriented).
3. Show layer on calendar chips / prep cards (subtle badge or colour — keep existing format colour language).

### Phase B — Week targets
1. Editable per-week layer counts (Acquisition / Identity / Conversion), inherit steady 2 / 2 / 1.
2. Count dated layered cards (stories included); Reel+TikTok deduped.
3. Format quotas later. Mix lives in the chips above the calendar, not a per-week caption in the grid.

### Phase C — Prep board by layer
1. Re-column Preparation to layers.
2. Keep format/pillar on card; Need menus / calendar slots unchanged at first.
3. Migrate UX carefully so existing cards don’t feel “lost.”

### Phase D — Polish (later)
- Hook pill auto-suggest for Reel/TikTok only.
- Phase presets from branding monthly table.
- Deficit-driven prompts in Discover.
- Tune defaults after real near-daily weeks.

---

## Explicit non-goals (for now)
- Hardcoding the deck’s old “3 reels / 2 carousels” week quotas as immutable rules.
- Painting every calendar day a single layer colour as the primary UX.
- Deploy from cloud agents (still Mac/PC `wrangler deploy` when ready).

---

## Open questions (resolve when building)
1. Exact label: **Intention** vs **Why**?
2. Layer short names on chips: Acquisition / Identity / Conversion — or longer deck names?
3. Week targets count **one make** (IG Post or Reel). Same-file TikTok is not a second layer hit. Stories separate. Locked 2026-09-15.
4. Prep-by-layer vs Email/Ads/Website (see §3).
5. Should event/release anchors **auto-suggest** week mixes when lead-up is active?

---

## Starting defaults (locked 2026-09-15)

**Must-hit every week:** 1 IG Post **or** Reel. If it’s a Reel, post the same file to TikTok.  
**Steady week:** 4 IG stories (Mon/Tue/Thu/Fri) + that 1 Post/Reel. Layer rotates Identity / Acquisition. Conversion off unless selling.  
**Struggling week:** 2 stories + still the 1 Post/Reel (do not skip IG feed).  
**Stretch week:** 4 stories + Post/Reel + a second unique piece.  
**Release week:** pick up later — not the current default.
