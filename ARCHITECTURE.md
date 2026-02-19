# Track 1 — Merge Progression Architecture

## Run Metadata
- Run ID: `trun_04740bf111ed4e89b66fff3d9721e0cd`
- Status: `completed`
- Source: Parallel MCP deep research + Perplexity evidence
- Last Checked: `2026-02-19T16:15:20Z`

## Executive Snapshot
Completed run recommends a scalable progression stack that starts linear for onboarding and shifts into DAG cross-links for late-game depth. The central design goal is to avoid both dead-end merges and endless linear grind.

## Core Recommendations

- Start players in **linear chains** (easy onboarding, predictable growth).
- Introduce **hub-and-spoke / DAG cross-crafting** in mid-game.
- Keep progression mathematically coherent by tracking item-to-tier growth and sink pressure.
- Include explicit fallback paths so no player is ever soft-locked.

## Key Findings from completed research

### 1) Merge graph structure
- **Linear ladders** are best for first-hour retention because they are easy to understand and teach.
- **Cross-chain links** (DAG-style recipes) create depth and reduce stale repetition in late game.
- Branching/radial forms should be introduced only after fundamentals are stable to avoid confusion.

### 2) Merge math constraints
- Standard merge-3 and merge-2 chains grow exponentially, so tier targets need careful calibration.
- Rare chains can feel long even with fewer tiers when drop rates are controlled.
- Use a **hardcoded safe cap** on expected time-to-tier growth to prevent burnout.

### 3) Safety-first gating
- Include universal fallback actions so board never freezes (trading, selling, or trashing path for every item class).
- Use free/low-cost generators as safety valves.
- Protect high-value/low-frequency pieces from accidental consumption by using harvest locks or conversion controls.

### 4) Anti-dead-end design
- Every chain must terminate into one of: sell, consume, convert, or prestige destination.
- Add temporary conversion channels when board clutter is high.
- Prevent infinite overflow exploits from becoming permanent by defining conversion or decay windows.

### 5) Pacing and retention implications
- Keep early-session progression fast enough for 3-5 meaningful completions/day.
- Stretch late-stage pacing through optional event channels or side-quest dependencies to avoid hard stalls.

## Suggested baseline template

- **Stage 1 (Hours 0-12):** 8 linear ladders, deterministic teaching path.
- **Stage 2 (Days 2-7):** Introduce 1 hub generator + 1 cross-chain recipe.
- **Stage 3 (Days 7+):** Expand to 2 cross-chains and specialist builders with mild unlock gates.
- **Universal rule:** every new high-tier object must have a sink/exit route.

## Implementation To-Dos
- Convert this summary into a full graph document (node types, edge rules, recipe table).
- Add tier-by-tier tuning matrix with expected energy and slot pressure.
- Define analytics for softlock risk and long-tail progression speed.