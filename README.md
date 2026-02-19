# Merge Menagerie Research

## Project Overview
Merge Menagerie is a proposed merge-game system study focused on building a modern, durable mobile game loop around inventory-based merges, progression economies, event-driven engagement, and sustainable monetization. This repository organizes ongoing deep research to convert research findings directly into design and implementation guidance for gameplay, balance, and live-ops systems.

## Purpose
The repository exists to produce evidence-backed guidance across six deep-research tracks:

- Merge progression architecture
- Resource economy and habitat/inventory scaling
- Event trigger and board-loop design
- Retention and session cadence
- Competition and benchmark positioning
- Monetization strategy and GDD integration

## Methodology
- Research providers: `Perplexity` + `Parallel MCP` deep research
- Execution model: each track is a dedicated task run (`trun_*`) with periodic polling
- Quality gates: every update includes status, evidence source list, and pending findings when tasks are incomplete
- Collaboration loop: status table updated continuously with current task state
- Refresh cadence used this stage: ~30-second status checks via `parallel-task_getStatus`

## Progress Tracker

| Track | Run ID | File | Status | Last Checked |
|---|---|---|---|---|
| Track 1 — Merge Progression | `trun_04740bf111ed4e89b66fff3d9721e0cd` | `ARCHITECTURE.md` | running | 2026-02-19T00:00:00Z |
| Track 2 — Resource Economy | `trun_04740bf111ed4e89bb24715ae59bf310` | `ECONOMICS.md` | completed | 2026-02-19T00:00:00Z |
| Track 3 — Event Trigger Design | `trun_04740bf111ed4e89a42f00b95c1c5703` | `EVENTS.md` | running | 2026-02-19T00:00:00Z |
| Track 4 — Retention and Sessions | `trun_04740bf111ed4e89bd9f1765498f5325` | `DOCUMENTATION.md` | completed | 2026-02-19T00:00:00Z |
| Track 5 — Competition Benchmark | `trun_04740bf111ed4e89a37f2b70e6a4003e` | `COMPETITION.md` | running | 2026-02-19T00:00:00Z |
| Track 6 — Monetization + GDD | `trun_04740bf111ed4e89a52a1616642bdd8` | `MONETIZATION.md`, `GDD.md` | unknown | 2026-02-19T00:00:00Z |

## Current Repository Layout
- `README.md`: overview, purpose, and tracker
- `ARCHITECTURE.md`: Track 1 progress architecture
- `ECONOMICS.md`: Track 2 resource and growth economics
- `EVENTS.md`: Track 3 event and trigger model
- `DOCUMENTATION.md`: Track 4 retention and session framework
- `RETENTION.md`: future retention artifact placeholder for additional longitudinal studies
- `COMPETITION.md`: Track 5 competitive benchmark analysis
- `MONETIZATION.md`: Track 6 monetization and conversion plan
- `GDD.md`: game design document draft from Track 6 synthesis
- `RESULTS.md`: aggregate final report (kept intentionally blank for merge-ready summary updates)
- `STATUS.md`: current run-state table with latest outputs and partial findings

## Repo URL
`https://github.com/ralph-goop/merge-mania-research`

## Notes
- Screenshots cannot be captured directly from this interface in a deterministic manner. The repository link above is the source-of-truth endpoint for review and screenshot capture in your browser.
- All completed tracks currently include direct findings extracts; in-progress tracks include structured placeholders for later insertion.