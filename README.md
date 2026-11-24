# Asthma Gene Expression Capstone

A student-led, AI-assisted bioinformatics capstone investigating airway epithelial gene-expression differences in asthma using publicly available data.

> **Status (2026-11-24):** Initial four-paper evidence matrix and guided paper review completed (Q1–Q8: 8/8; independent mastery not established). The student proposed a hypothesis and comparison in Q9. The outcome measure is pending. GSE67472 remains a candidate; full metadata/processing audit, verified analysis, literature-gap review and final independent question are incomplete. No original result tables or figures are established.

## Start here

- [Active roadmap v1.2](docs/PROJECT_ROADMAP.md) — evidence-first workflow, schedule and verification gates.
- [Latest research handoff — Nov 24](docs/handoffs/2026-11-24-guided-paper-review-to-student-investigation.md) — guided review history.
- [Q9 student investigation](research/student-investigations/2026-11-24-q9-th2-low-asthma.md) — tentative hypothesis, proposed comparison, and next checkpoint.
- [Initial literature evidence matrix](research/literature/2026-11-24-initial-evidence-matrix.md) · [Guided learning checkpoint](research/paper-notes/2026-11-24-guided-methods-results-discussion.md)
- [Earlier workflow handoff](docs/handoffs/2026-11-24-ai-assisted-research-workflow.md) · [Initial literature handoff](docs/handoffs/2026-11-24-initial-literature-evidence.md)
- [Nov 24 workflow decision](docs/decisions/DECISION-2026-11-24-ai-assisted-analysis-student-investigation.md) — division of labor and research integrity.
- [Nov 3 midpoint report](docs/reports/2026-11-03-classroom-midpoint-progress-report.md) — historical progress evidence.
- [Project charter](docs/PROJECT_CHARTER.md) · [Changelog](docs/PROJECT_CHANGELOG.md) · [Handoff rules](docs/SESSION_HANDOFF_RULES.md)
- [Archived v1.0](docs/archive/PROJECT_ROADMAP_v1.0_2026-10-13.md) · [Archived v1.1](docs/archive/PROJECT_ROADMAP_v1.1_2026-10-26.md) · [Nov 4 revision snapshot](docs/archive/ASTHMA_ROADMAP_REVISION_2026-11-04.md)

## Working research question

Which genes differ between asthma and healthy airway epithelial samples in [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472), and how do selected patterns compare with the original study? This is a provisional educational question, not a claim of novelty. The source describes 62 asthma and 43 control subjects; individual sample labels and processing must be audited before analysis. The [Christenson et al. (2015) paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/) includes other COPD and GLUCOLD cohorts, which GSE67472 does not contain.

## Research workflow

| Stage | AI assistance | Student-led contribution |
|---|---|---|
| 1. Evidence briefing | Explain relevant papers with source locations; build a comparison matrix (start 2–3, expand toward 5–10) | Verify key claims, understand design, ask questions |
| 2. Educational pilot | Audit metadata, prepare reproducible analysis and explain actual output if feasible | Verify representative sample labels and understand group comparison |
| 3. Investigation | Help interpret patterns, locate relevant sources and alternatives | Select a pattern, propose a focused question, investigate genes/pathways or limitations, write own evidence-linked interpretation |
| 4. Scope decision | Assess literature comparability and feasibility | Decide and justify a research question or educational reanalysis endpoint |
| 5. Follow-up | Run justified, documented analyses if possible | Critique results, assess alternatives and explain findings |
| 6. Report | Assist organization, clarity and reproducibility | Own scientific decisions and clearly attributed student interpretation |

No stage is marked complete by adopting this plan. Published findings are distinct from AI-assisted computed results and student investigation. Pilot-derived questions remain exploratory; same-dataset follow-up is not independent validation. Compare published statistics descriptively unless a defensible synthesis method and comparable data exist.

## Expected outputs

- Cited literature evidence matrix and source-linked paper explanations.
- Verified sample manifest, data/processing documentation, analysis protocol.
- Actual analysis code/settings, raw outputs, interpreted tables and figures if feasible.
- Student investigation notes, question rationale and limitations.
- English report with contributions and reproducibility statement.

## Repository structure

- `docs/`: roadmap, charter, changelog, decisions, archives, handoffs, reports and templates.
- `research/paper-notes/`: historical reading notes; [student Abstract interpretation](research/paper-notes/2026-10-26-abstract-reading-feedback.md).
- `research/literature/`: source-linked explanations and evidence matrix when produced; [paper structure guide](research/literature/christenson-2015-paper-structure.md).
- `research/student-investigations/`: planned location for authentic student follow-up notes.
- `research/`: dataset audit and analysis protocol.
- `scripts/` and `results/`: actual executable methods and saved outputs when available, not proof of completed analysis by directory existence.

## Integrity and timeline

Record source URLs, sample IDs, preprocessing, comparison direction, exclusions, settings/code, and results. Report null findings, multiple-testing adjustments where relevant, and limitations. Do not invent values, student authorship or analysis runs; no diagnostic, causal or treatment-prediction claims. Cite AI assistance and comply with applicable school/admission requirements. Check reuse terms before redistributing data; no license has been selected.

SAT December 5 remains the priority. No mandatory work before the exam; aim for 3–4 hours/week afterwards if feasible. February 28, 2027 is a conditional portfolio target. A bounded educational reanalysis is acceptable if a distinct contribution cannot be supported.
