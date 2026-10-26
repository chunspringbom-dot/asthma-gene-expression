# Asthma Gene Expression Capstone

A student-led bioinformatics research project investigating gene-expression differences in airway epithelial samples from people with asthma and healthy controls, using publicly available data.

> **Project status (2026-10-26):** Planning and guided paper reading; student read part of the Abstract. GSE67472 sample audit and statistical analysis **not yet completed**.  
> **Working period:** October 2026 – February 2027  
> **Primary data candidate:** NCBI Gene Expression Omnibus (GEO), accession [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472)  
> **SAT scheduling:** Student exam **2026-12-05**; project time ~60–90 min/week before the exam, intended ~3–4 hours/week afterwards if feasible. The [active v1.1 roadmap](docs/PROJECT_ROADMAP.md) supersedes [archived v1.0](docs/archive/PROJECT_ROADMAP_v1.0_2026-10-13.md).  
> **Important:** The dataset and final research question remain provisional; no verifiable GEO2R analysis has been run.

## Project control center

- **[Week-by-week roadmap v1.1](docs/PROJECT_ROADMAP.md)** — SAT-adjusted schedule, weekly tasks, evidence gates and versioning.
- **[Chronological project change log](docs/PROJECT_CHANGELOG.md)** — dated progress, corrections, learning-method changes and delays.
- **[Oct 26 decision: learning method and SAT scheduling](docs/decisions/DECISION-2026-10-26-reading-workflow-and-sat-schedule.md)** — why the workflow and calendar changed.
- **[Latest handoff (Oct 26)](docs/handoffs/2026-10-26-paper-reading-sat-adjustment.md)** — resume point for new conversations.
- **[Original paper: structure reference](research/literature/christenson-2015-paper-structure.md)** — source-checked overview, labeled as assistant support.
- **[Student's partial Abstract interpretation](research/paper-notes/2026-10-26-abstract-reading-feedback.md)** — initial comprehension and corrections.
- [Project charter](docs/PROJECT_CHARTER.md) — scope, research question, and decision rules.
- [Session handoff rules](docs/SESSION_HANDOFF_RULES.md) — rules for continuing work across sessions.
- [Dated handoffs](docs/handoffs/) — current state, evidence, decisions, and next actions.

The roadmap is the planning baseline. At the end of each meaningful session, create a handoff; at the end of each week, record whether the week's exit criteria were met. Any major change to scope, dataset, comparison, or method must be justified in a dated decision note.

## Working research question

In a public gene-expression dataset, which genes differ between airway epithelial samples from people with asthma and healthy controls, and are selected inflammation-related gene-expression patterns consistent with the original study?

The question may be narrowed after reviewing the dataset design, available processed data, group labels, and analysis tools.

## Why this project?

Asthma is a complex disease involving airway inflammation. Gene-expression data can help researchers investigate biological patterns associated with disease, while careful reanalysis can teach how scientific claims depend on data selection, statistical methods, and study limitations.

This project is an educational reanalysis of public data. It is not a clinical test, does not diagnose anyone, and will not claim that gene-expression differences prove causation.

## Proposed approach

1. Review the GEO record and the original paper.
2. Confirm sample groups, sample counts, platform, processed data availability, and limitations.
3. Test whether GEO2R or another accessible method can answer the research question reproducibly.
4. Define a small, pre-specified set of analyses before interpreting results.
5. Compare findings with the original study and explain similarities, differences, and limitations.
6. Publish the research question, methods, results, references, and session handoffs in this repository.

## Planned deliverables

- Research proposal and a dated decision log
- Dataset-selection and feasibility notes
- Reproducible analysis steps and data-source links
- Clearly labelled tables and figures
- Final report with discussion and limitations
- Session handoff notes that allow work to continue across ChatGPT sessions

## Repository structure

- docs/PROJECT_ROADMAP.md — active v1.1 SAT-adjusted schedule and evidence gates
- docs/PROJECT_CHANGELOG.md — chronological history
- docs/decisions/ — documented research/workflow decisions
- docs/archive/ — preserved superseded plans
- research/paper-notes/ — dated reading notes with source-linked student annotations
- research/literature/ — assistant-prepared source-based study orientations
- docs/PROJECT_CHARTER.md — project scope and decision rules
- docs/SESSION_HANDOFF_RULES.md — session continuity
- docs/handoffs/ — dated handoff notes
- research/ — research plan, literature notes, and methods
- results/ — reviewed tables and figures
- scripts/ — code added when needed

## Research integrity

- Cite the original dataset, papers, software, and external sources.
- Distinguish observations from interpretations and hypotheses.
- Report null, unexpected, or inconsistent findings rather than hiding them.
- Do not infer causation from observational gene-expression differences.
- Do not present exploratory results as independent validation.
- Do not upload personal, sensitive, or restricted data.
- Keep a record of tool settings, comparison groups, date of analysis, and relevant software versions.

## Session continuity

Before continuing work, read the roadmap, project charter, session handoff rules, and latest handoff. At the end of every meaningful work session, update the handoff with completed work, evidence, decisions, unresolved questions, changed files, and the next concrete action.

## Original paper vs data boundary

The [Christenson et al. (2015) article](https://pubmed.ncbi.nlm.nih.gov/25611785/) compares gene signatures across asthma and COPD data, including a separate randomized placebo-controlled treatment study. **GSE67472 contains only the asthma/healthy airway epithelial series (62 + 43 subjects)**, not all COPD datasets or the treatment trial. The first capstone analysis, if feasible, will stay within its available sample groups. We do not claim independent clinical treatment prediction.

## Primary source

- NCBI GEO: [GSE67472 — Airway epithelial gene expression in asthma versus healthy controls](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472)

## License and data

No project license has been selected yet. Dataset reuse and redistribution terms must be checked before any third-party data are copied into this repository. Prefer citing and linking to source data rather than duplicating it.
