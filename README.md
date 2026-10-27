# Asthma Gene Expression Capstone

A student-led bioinformatics research project investigating gene-expression differences in airway epithelial samples from people with asthma and healthy controls, using publicly available data.

> **Project status (2026-10-27):** Planning and guided paper reading; student read part of the Abstract. The seven-step long-term research direction has been documented, but is not yet an executed analysis. GSE67472 sample audit and statistical analysis **not yet completed**.  
> **Working period:** October 2026 – February 2027  
> **Primary data candidate:** NCBI Gene Expression Omnibus (GEO), accession [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472)  
> **SAT scheduling:** Student exam **2026-12-05**; project time ~60–90 min/week before the exam, intended ~3–4 hours/week afterwards if feasible. The [active v1.1 roadmap](docs/PROJECT_ROADMAP.md) supersedes [archived v1.0](docs/archive/PROJECT_ROADMAP_v1.0_2026-10-13.md).  
> **Important:** The dataset and final research question remain provisional; no verifiable GEO2R analysis has been run.

## Project control center

- **[Week-by-week roadmap v1.1](docs/PROJECT_ROADMAP.md)** — SAT-adjusted schedule, weekly tasks, evidence gates and versioning.
- **[Chronological project change log](docs/PROJECT_CHANGELOG.md)** — dated progress, corrections, learning-method changes and delays.
- **[Oct 26 decision: learning method and SAT scheduling](docs/decisions/DECISION-2026-10-26-reading-workflow-and-sat-schedule.md)** — why the workflow and calendar changed.
- **[Latest handoff (Oct 27)](docs/handoffs/2026-10-27-seven-step-research-direction.md)** — resume point following the research-direction decision and README roadmap update.
- **[Oct 27 decision: from reproduction toward independent research](docs/decisions/DECISION-2026-10-27-reproduction-to-independent-research.md)** — rationale and boundaries for originality and reproducibility.
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

## Seven-step research roadmap (long-term direction)

This roadmap records the student's intended **scientific progression**, not a claim that the stages have been completed. The detailed **weekly execution schedule and evidence gates** remain in [Project Roadmap v1.1](docs/PROJECT_ROADMAP.md), which prioritizes the December 5, 2026 SAT. The reasoning behind this strategy is documented in the [October 27 decision record](docs/decisions/DECISION-2026-10-27-reproduction-to-independent-research.md).

| Step | What we plan to do | Why it matters |
|---|---|---|
| **1. Understand the current asthma/COPD paper** | Carefully read and explain Christenson et al. (2015), especially the asthma-relevant methods and the distinction from COPD and GLUCOLD cohorts. | Build the biological and study-design foundation. |
| **2. Learn GSE67472 and its analysis workflow** | Examine GEO metadata, study groups, microarray measurements, processing, and suitable analysis tools; conduct a small educational reproduction only after verification. | Develop practical data-analysis skills. |
| **3. Compare 5–10 related papers** | Build a literature matrix of questions, datasets, methods, findings, and limitations; expand the reading list if needed. | Identify what has already been studied. |
| **4. Investigate limitations in prior research** | Compare evidence, unresolved uncertainties, replication claims, and methodological weaknesses. | Identify a credible **research gap**, if one exists. |
| **5. Finalize a new research question** | Select a testable, feasible question with a clearly distinct contribution; document the decision before the main analysis. | Define the potential original contribution without claiming novelty prematurely. |
| **6. Analyze public data** | Test the pre-specified question using verified sample groups and reproducible methods; report both confirming and conflicting evidence. | Evaluate the hypothesis with data. |
| **7. Write an English research paper** | Present background, literature review, methods, results, limitations, and references; distinguish reproduction from any original extension. | Communicate the work transparently. |

**Status as of 2026-10-27:** Step 1 is **in progress**; Step 2 remains a **planned, unverified dataset-analysis activity**; Steps 3–7 are **not completed**. GSE67472 and the final research question remain provisional; no verified GEO2R results exist. An independently novel extension is **conditional on identifying a real gap and suitable data**. If that condition is not met, the final deliverable may be an honestly labeled educational reanalysis/report rather than a claim of discovery.

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
- docs/templates/ — reusable paper review and research session log templates
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
