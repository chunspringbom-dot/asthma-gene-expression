# Project Charter

## Project identity

- **Repository:** [chunspringbom-dot/asthma-gene-expression](https://github.com/chunspringbom-dot/asthma-gene-expression)
- **Working period:** October 2026 – February 2027
- **Research area:** Gene expression / airway inflammation / asthma
- **Project type:** Student-led analysis of public research data
- **Status:** Kickoff; dataset feasibility not yet fully checked

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

## Provisional timeline

- **October 2026:** Learn core terms, review the GEO record and paper, assess feasibility.
- **November 2026:** Finalize the dataset and primary comparison; produce the first result table/figure.
- **December 2026:** Complete the main analysis and compare with the original study.
- **January 2027:** Interpret biological meaning, examine limitations, and draft the report.
- **February 2027:** Finalize report, figures, references, README, and repository review.

## Immediate next actions

1. Open the GEO record and record its study design, platform, and data-processing details.
2. Find and read the original paper associated with the GEO record.
3. Confirm whether GEO2R supports the intended comparison and how sample groups should be selected.
4. Write a one-page feasibility note before starting the main analysis.
