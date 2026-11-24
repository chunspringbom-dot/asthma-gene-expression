# Project Charter

## Project identity

- **Repository:** [chunspringbom-dot/asthma-gene-expression](https://github.com/chunspringbom-dot/asthma-gene-expression)
- **Working period:** October 2026 – February 2027
- **Research area:** Gene expression / airway inflammation / asthma
- **Project type:** Student-led analysis of public research data
- **Status (2026-11-24):** Guided Abstract discussion and asthma-specific Methods begun; full sample audit and verified analysis incomplete. See [active roadmap v1.2](PROJECT_ROADMAP.md) and [workflow decision](decisions/DECISION-2026-11-24-ai-assisted-analysis-student-investigation.md).

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
5. The project can produce a small set of interpretable tables/figures within the conditional revised timeline.
6. Limitations and potential confounders can be documented.

If these conditions are not met, select a better documented GEO dataset while keeping the broad molecular-biology interest.

## Proposed analysis plan

1. Assistant prepares source-linked paper explanations and a descriptive literature matrix; student verifies important claims.
2. Audit sample metadata, processing, platform and comparison eligibility before any analysis.
3. Document a primary asthma vs healthy contrast (provisional); run an AI-assisted educational pilot only if feasible, saving code/settings and actual output.
4. Student interprets selected results, raises questions and investigates relevant genes, pathways or limitations using original sources.
5. Evaluate the literature gap together; student chooses and justifies a feasible follow-up question and protocol, or an educational reanalysis endpoint.
6. Analyze if appropriate; report effect sizes, adjusted p-values where relevant, reproducibility, null results and limitations. Pilot-derived findings remain exploratory.
7. Write English report separating published evidence, AI-assisted work and student-owned contributions. Do not pool incomparable literature statistics or represent published values as new calculations.

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

## Active provisional timeline (v1.2; SAT on December 5)

- **Nov 24–Dec 6:** SAT priority, optional briefing only, no mandatory work.
- **Dec 7–20:** Briefing, initial literature matrix and full metadata/processing audit; go/no-go decision.
- **Dec 21–Jan 3:** Educational pilot if feasible, actual outputs and student questions; otherwise document blocker.
- **Jan 4–31:** Student follow-up investigation, literature gap assessment, scope decision and any justified follow-up analysis.
- **Feb 1–28:** Verification, English report and portfolio; deadline conditional.

See [active roadmap](PROJECT_ROADMAP.md), [archived v1.1](archive/PROJECT_ROADMAP_v1.1_2026-10-26.md) and [changelog](PROJECT_CHANGELOG.md). No missed work is retroactively marked complete.

## Immediate next actions

1. Assistant explains Christenson et al. (2015) and GSE67472 using primary source links, then prepares an initial literature evidence matrix.
2. Student chooses a question or interesting pattern and verifies key claims; no full-paper translation requirement.
3. After SAT, finish sample and processing audit; run only if the contrast and data are suitable.
4. Present actual saved results if produced and invite student-led follow-up investigation. No fabricated results or student statements.
