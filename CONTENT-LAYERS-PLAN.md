# Content layers + intentional pipeline — plan

Status: **planning** — taxonomy locked 2026-09-14; product changes **not** started. Branding PDF is a starting point; its fixed 4-week volume table is outdated. Cadence will get more complex (near-daily posting). Do not implement until Jarvis is ready to build inside existing Marketing (calendar + pipeline) — no side pages.

Live baseline: Marketing **0.12.82**.

---

## Problem

Content is often found as “looks good → make → post” without a clear job. That weakens motivation and the content itself. Feedback asked for intention early: every piece should know **why** it exists and which **layer** it serves.

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

## Product decisions (agreed direction)

### 1. Required fields on ideas / prep / calendar cards
- **Layer** — Acquisition / Identity / Conversion (required once an idea is serious enough to prep).
- **Intention / Why** — short free-text: what this piece is meant to do (directs the idea beyond the layer label).
- These sit *above* format/platform. Format still exists; it is not the primary organising axis for prep.

### 2. Optional Hook (pill)
- Same pattern as Execution’s Products / Location / Requirements: `+ Hook` → text field → removable.
- **Mainly for Reels and TikToks** — do not force on carousels/stills/stories.
- Optional UX later: only show the Hook pill when format is Reel/TikTok (still allow manual add elsewhere if useful).

### 3. Prep board organised by layer (not media platforms)
- Today Prep columns/boards lean on pillars/formats (Organic IG/TikTok, Email, Ads, Website…).
- **Proposed:** Preparation columns = **Acquisition | Identity | Conversion**.
- Platform/format remains a property on the card (and still drives calendar Need slots / publish logistics).
- Rationale: prep time is when intention matters most; platform is a delivery choice, not the thinking frame.

Open design detail when building:
- Where do Email / Ads / Website cards live if Prep is layer-first? Options: (a) still tag format+pillar on the card and filter; (b) keep a thin “Other channels” area; (c) layer columns only for Organic feed/stories work first. Prefer (a) unless it gets noisy.

### 4. Weekly layer targets (settings above calendar)
- Per week: set **how many pieces needed per layer** (editable).
- Default steady-state mix (starting point, not law):

| Layer | Share of feed posts | Example ~7 feed pieces/week |
|---|---|---|
| Identity | ~45% | ~3 |
| Acquisition | ~35% | ~2–3 |
| Conversion | ~20% | ~1–2 |

- **Release / event weeks:** raise Conversion, keep Acquisition steady, **never zero Identity**.
- Stories / light daily presence can lean Identity + Acquisition, with Conversion near drops.
- UI: week strip or settings box — counts + progress (“Identity 1/3 · Acquisition 2/2 · Conversion 0/1”).
- Optional later: week **phase** preset (Release / Post-release / Culture / Pre-launch) that loads a suggested mix from the deck’s priority table, then user tweaks.

### 5. Idea-finding guided by deficit
- Discover / Ideas workflow: surface **what this week is short on**.
- Short Acquisition → visual/motion/aesthetic that introduces cold.
- Short Identity → fabric, sew, pattern, studio, community.
- Short Conversion → garment breakdown, fit, stock, product-led lifestyle.

### 6. Two clocks (don’t conflate)
- **Near-daily presence** (stories / light) vs **feed pieces** (reels/carousels) — targets should primarily count feed (or count separately if we need both).
- Existing format cadence (Mon/Thu grid, etc.) stays as *when/how often by format*; layers answer *why*.

---

## Suggested build phases

### Phase A — Card fields (smallest useful)
1. Add **Layer** + **Intention/Why** on idea → prep → calendar (sync like other body fields).
2. Add optional **`+ Hook`** pill (Reel/TikTok-oriented).
3. Show layer on calendar chips / prep cards (subtle badge or colour — keep existing format colour language).

### Phase B — Week targets
1. Persist `weekLayerTargets` (or extend `weekGoals`) per week key.
2. Calendar header: set Acquisition / Identity / Conversion counts; show filled vs needed.
3. Defaults from steady mix; presets for release/event weeks.

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
3. Do week targets count **scheduled feed posts only**, or prep cards too?
4. Prep-by-layer vs Email/Ads/Website (see §3).
5. Should event/release anchors **auto-suggest** week mixes when lead-up is active?

---

## Starting defaults to try in real life (before/while building)

**Steady week:** Identity-heavy, Acquisition regular, Conversion light.  
**Release week:** Conversion up; Identity floor maintained.  
**Feed rhythm example:** `A → I → A → I → C → I → A` (swap freely; don’t start from blank).

Rest, then pick Phase A when ready to implement.
