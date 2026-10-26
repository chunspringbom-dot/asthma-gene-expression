# Project Charter

## Project identity

- **Repository:** [chunspringbom-dot/asthma-gene-expression](https://github.com/chunspringbom-dot/asthma-gene-expression)
- **Working period:** October 2026 – February 2027
- **Research area:** Gene expression / airway inflammation / asthma
- **Project type:** Student-led analysis of public research data
- **Status (2026-10-26):** Student has read part of the original Abstract; dataset feasibility and sample group audit incomplete, no analysis executed. See [Roadmap v1.1](PROJECT_ROADMAP.md) and [dated learning/schedule decision](decisions/DECISION-2026-10-26-reading-workflow-and-sat-schedule.md).

## Research question (provisional)

In a public gene-expression dataset, which genes differ between airway epithelial samples from people with asthma and healthy controls, and are selected inflammation-related gene-expression patterns consistent with the original study?

## Why this question

It connects molecular biology with a manageable public-data project. The initial plan is to use existing processed data and a guided analysis tool before deciding whether Python or more advanced statistical methods are necessary.

## Initial dataset candidate

**GEO accession GSE67472** — “Airway epithelial gene expression in asthma versus healthy controls.”

The GEO record describes microarray data from airway epithelial brushings collected from 62 people with mild-to-moderate asthma not on inhaled steroids and 43 healthy controls. The asthma group was further stratified into Th2-high and Th2-low subgroups based on a three-gene signature (POSTN, SERPINB2, and CLCA1).

Source: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472

These facts describe the GEO record; they do not yet establish that this dataset is the best choice for the student's final analysis.

## Feasibility gates

Before locking the topic, confirm:

1. The original paper can be accessed and its study design understood.
2. Sample metadata and comparison groups are sufficiently clear.
3. Processed data can be accessed in a format supported by GEO2R or another feasible tool.
4. The intended comparison can be performed without unsupported assumptions about sample labels.
5. The project can produce a small set of interpretable tables/figures by the end of November.
6. Limitations and potential confounders can be documented.

If these conditions are not met, select a better documented GEO dataset while keeping the broad molecular-biology interest.

## Proposed analysis plan

1. Read the GEO record and original paper.
2. Document the platform, data type, group definitions, sample counts, and data processing already applied.
3. Choose one primary comparison (initially asthma vs healthy controls, subject to feasibility).
4. Run a documented exploratory analysis using GEO2R or an appropriate accessible workflow.
5. Report effect direction and statistical evidence, including adjusted p-values when available.
6. Examine a small, pre-specified set of inflammation-related genes and compare the overall pattern with the original paper.
7. Interpret findings cautiously; avoid causal or clinical claims.

## Success criteria

The project is successful if it produces:

- a clearly scoped question and documented rationale;
- a defensible dataset choice;
- a reproducible analysis workflow;
- correctly labelled tables and figures;
- a comparison with the original study;
- an honest discussion of limitations and uncertainty;
- a GitHub history and handoff notes that show how the work developed.

A surprising or non-significant result can still be a valid outcome if the analysis is sound and interpreted honestly.

## Scope boundaries

- No clinical diagnosis or treatment recommendations.
- No claim that association proves causation.
- No claim of independent replication unless a genuinely independent dataset and suitable method are used.
- No requirement to train a machine-learning model.
- No requirement to master Python before starting.
- A second-dataset analysis is optional, not a core deliverable.

## Active provisional timeline (v1.1; SAT on December 5)

- **Oct 26–Dec 4, 2026:** SAT priority; capstone target 60–90 minutes/week for guided Abstract, asthma-specific Methods and GEO design notes; pilot sample checks only if access allows.
- **Dec 5–6:** SAT day and optional recovery; no required research tasks.
- **Dec 7–20:** Re-enter research; sample metadata audit and provisional primary contrast.
- **Dec 21, 2026–Jan 17, 2027:** Feasibility and carefully recorded main analysis *only if metadata supports it*. If not, record blockers and revise.
- **Jan 18–Feb 7:** Figures, interpretation, limitations, and reproducibility if analysis succeeds.
- **Feb 8–28:** Draft report, organize GitHub, check sources, final handoff and portfolio. Feb 28 remains a target, not a guarantee.

The **original Oct 13 schedule missed some exit criteria**; its original version is preserved [here](archive/PROJECT_ROADMAP_v1.0_2026-10-13.md). See [project chronology](PROJECT_CHANGELOG.md). This scheduling revision does **not** change the scientific question, candidate dataset, or success criteria.

## Immediate next actions

1. Complete a short source-linked Abstract explanation in the student's own words and clarify cohort/airway epithelial terms.
2. Read the asthma-specific Methods and distinguish GSE67472 from the article's COPD and GLUCOLD cohorts.
3. After the December 5 SAT, finish GEO sample-group mapping and check processed data/GEO2R suitability.
4. Only then prerecord the primary contrast and run a documented analysis if feasible.
