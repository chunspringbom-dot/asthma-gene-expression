# Decision — AI-assisted analysis and student-led follow-up investigation

**Date:** 2026-11-24  
**Status:** Adopted workflow; scientific question and dataset remain provisional.

## Rationale

The student reported insufficient time for the capstone and requested the previously discussed approach: the assistant explains papers and presents source-linked data/analysis tables, then the student identifies interesting patterns, questions and limitations and investigates them further. The November 3 report records guided Abstract discussion and beginning asthma-specific Methods; the November 4 handoff records planning only. The latest prior commit was November 4. No verified sample manifest, original analysis, result table or figure has been established. Repeated planning and linear paper reading have become bottlenecks, particularly before the December 5 SAT.

## Decision

Replace v1.1's reading-first execution schedule with evidence-first, AI-assisted workflow v1.2. Retain the asthma-only scope, original candidate GSE67472 and the conditional February 28 target. Preserve v1.0, v1.1 and November 4 snapshot. Do not require full-paper mastery before inspecting data.

- Assistant: find relevant primary papers, explain their question/methods/findings and limitations in accessible language; create a cited evidence matrix of approximately 5–10 related papers (start with 2–3); inspect metadata and processed data, propose valid comparisons, execute supported analyses when data/tools are actually available, save code/settings and outputs, and explain tables and figures.
- Student: check important source claims and selected sample labels, explain key concepts and results in own words, choose interesting patterns, propose questions, investigate selected genes/pathways or discrepancies in original sources, assess alternative explanations/confounders, decide scope and interpret results. Student-owned contributions must be recorded separately; no fabricated student statements.
- Both: discuss a feasible question, verify analysis design, review uncertainty, decide next investigation. Pilot analyses and hypotheses generated from them are exploratory. Pre-specify any subsequent analysis; same-data follow-up is not independent validation.
- Published data tables are literature extraction, not new analysis. Do not pool p-values, fold changes or incomparable cohorts as though they were patient-level observations. Compare studies descriptively unless harmonization and a justified synthesis method are documented. Actual calculations require accessible data and a reproducible method.
- Attribute AI support and student contributions. Save source locators, accession IDs, sample manifest, exclusions, processing, code/tool settings, software versions where available, raw output and interpreted tables. Report effect sizes, multiple-testing-adjusted p-values where relevant, null findings and limitations. No causal, diagnostic or treatment prediction claim from GSE67472 alone.

## Consequences

Before SAT, no compulsory work; optionally review a short briefing and identify a question. After SAT, prioritize source-linked evidence and a verified pilot rather than more administrative documents. If data access or metadata prevents a valid comparison, report the blocker and continue descriptive literature comparison; no invented results. A well-documented educational reanalysis is sufficient if independent novelty cannot be supported.

See [active roadmap](../PROJECT_ROADMAP.md), [November 3 report](../reports/2026-11-03-classroom-midpoint-progress-report.md), [November 4 handoff](../handoffs/2026-11-04-asthma-only-roadmap-correction.md).
