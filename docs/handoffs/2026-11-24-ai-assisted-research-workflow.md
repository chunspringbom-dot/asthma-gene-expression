# Session Handoff — AI-assisted analysis and student-led investigation

**Date:** 2026-11-24 | **Status:** Planning revision only; no analysis run.

## Current state

[November 3 midpoint report](../reports/2026-11-03-classroom-midpoint-progress-report.md) documents guided Abstract discussion and initial asthma-specific Methods. [November 4 handoff](2026-11-04-asthma-only-roadmap-correction.md) was documentation only; last prior commit `23c9749`. Student reported insufficient time. Full metadata/processing verification, actual computed results, literature comparison, and final independent question are not established. Candidate GSE67472; provisional asthma vs healthy comparison, not COPD treatment response.

## Decision and work completed

Adopted [v1.2](../PROJECT_ROADMAP.md): assistant explains papers, builds cited literature comparison tables, checks metadata and runs reproducible analysis only if valid and feasible; student chooses questions/patterns, verifies key claims, investigates further, critiques evidence and determines direction. Keep student's own contributions separate from AI-generated text. No mandatory work before December 5 SAT. Published statistics are not newly computed results; pilot-derived questions are exploratory, not independent validation.

## Files and Git state

- [v1.1 archive](../archive/PROJECT_ROADMAP_v1.1_2026-10-26.md): `586c9684a71543e32941e58095808577bd451f51`
- [decision](../decisions/DECISION-2026-11-24-ai-assisted-analysis-student-investigation.md): `cb7e73ae5ffe1616c4874b734f57dab758673778`
- [active roadmap](../PROJECT_ROADMAP.md): `e38898dc1e7fda895afc05ea1a096eea03c99e35`
- [README](../../README.md): `0c37d6ed21976b65f8a148c39a6316fcd545d666`
- [charter](../PROJECT_CHARTER.md): `3525f8a9e1e455f603c729714e833092bfcc83ea`
- [changelog](../PROJECT_CHANGELOG.md): `9a38e88f241d53c3f70bf64e118ebd22d22fffec`
- This handoff: see its Git file history for its own commit.
- No data files, code execution, result table or figure created during this planning session.

## Evidence and next actions

1. AI prepares concise, source-linked briefing using [Christenson et al. (2015)](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/) and [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472): question, participants/tissue, methods, published findings, limitations, dataset boundaries.
2. Find 2–3 relevant primary papers, create initial evidence matrix; expand toward 5–10 if helpful. Include dataset, contrast, method, reported effect/statistic, source locator and limitations; do not pool incompatible values.
3. Student chooses one question or pattern, verifies source claims and writes own interpretation; optional before SAT, otherwise after Dec 7.
4. Audit full eligible sample manifest, processing and comparison before computation; if suitable, run documented educational pilot, save raw outputs, code/settings, tables/plots and explain actual results. If blocked, log why and use literature evidence only.
5. Student investigates selected gene/pathway/discrepancy; together decide feasible follow-up, prespecify protocol or conclude educational reanalysis. Record student/AI roles.

## Resume prompt

Continue the Asthma Gene Expression capstone using roadmap v1.2 and this handoff. Start by explaining the original paper with primary-source locators and producing a cited initial literature evidence table; then ask me which pattern I want to investigate. Verify metadata and data availability before any original analysis; show only verifiable outputs and distinguish published findings, AI assistance and my own contributions. Keep SAT December 5 as the priority.
