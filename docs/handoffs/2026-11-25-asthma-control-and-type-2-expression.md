# Session handoff · November 25, 2026

## Session and current state

The student adopted a within-asthma research question. The project is at dataset feasibility review.

Among patients with asthma, how closely does asthma control (ACQ) track a predefined type 2 gene-expression score in airway epithelial cells? How much does the expression score vary among patients with similar ACQ scores?

## Work completed and decision

Recorded the student's classification question, the reason for moving beyond the asthma–control comparison, and the candidate dataset. The question is selected. Dataset eligibility, score definition and independent replication remain provisional. No patient-level association has been calculated.

## Evidence reviewed November 25

- [GSE89809](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE89809) includes multiple tissues. Individual epithelial samples from [mild](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM2389887), [moderate](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM2389919) and [severe](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM2389951) asthma include ACQ values.
- A [prior analysis](https://doi.org/10.1186/s12920-021-00892-4) related coexpression modules to ACQ in this dataset. Check overlap with the proposed score before claiming novelty.

## Open questions and next actions

1. Audit GSE89809 bronchial epithelial brushing records. Build one row per eligible patient with sample ID, ACQ, available treatment information and reasons for exclusions. Check duplicate IDs, missing values, questionnaire version and expression preprocessing.
2. Report the eligible count. Verify that the genes for a published type 2 score can be mapped. Document the scoring rule, association measure and uncertainty estimate before inspecting the association.
3. If feasible, plot one point per patient and examine the spread at similar ACQ values. Interpret ACQ according to the verified questionnaire version. Physician accuracy would require a separate study.

## Files and Git state

This documentation update links the [decision](../decisions/DECISION-2026-11-25-asthma-control.md), [changelog](../PROJECT_CHANGELOG.md), [active roadmap](../PROJECT_ROADMAP.md), [archived roadmap](../archive/PROJECT_ROADMAP_v1.2_2026-11-24.md), [investigation note](../../research/student-investigations/2026-11-25-classification-question.md) and [README](../../README.md). See the [repository history](https://github.com/chunspringbom-dot/asthma-gene-expression/commits/main/) for the commits.

## Resume prompt

> Read the November 25 handoff. Audit GSE89809 and show me the patient-level eligibility counts, exclusions, available ACQ information and any unresolved linkage before calculating expression scores.
