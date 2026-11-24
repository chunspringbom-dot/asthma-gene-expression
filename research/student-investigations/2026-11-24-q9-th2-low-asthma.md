# Q9 student investigation — Th2-low asthma and a COPD-associated expression pattern

**Date:** 2026-11-24  
**Status:** Tentative student hypothesis and comparison proposed. Student proposed FEV₁ as a candidate clinical outcome. Expression measure, expected direction, and full metadata audit pending.

## Student response (English translation)

The student hypothesized that patients with Th2-low asthma may be less likely to show the type 2 inflammation-related features observed in COPD. The student proposed comparing their type 2 inflammation score or gene expression with that of asthma patients whose type 2 expression is high.

## Assistant feedback and source checks

- Christenson et al. evaluated an asthma-derived 100-gene T2S score in separate COPD cohorts. Lower expression of the three asthma subgroup markers does not establish that COPD-associated features are absent. See the [abstract and Figure 3](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/).
- The [GSE67472 series record](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472) lists asthma and healthy control samples. Its asthma subgroup labels use POSTN, SERPINB2, and CLCA1. Representative indexed GEO records show explicit subgroup fields for [GSM1647628 (low)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM1647628) and [GSM1647669 (high)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM1647669). Full sample mapping and processing audit remain pending.
- Comparing those three markers between the subgroups would describe the definition of the groups. Comparing a prespecified expression measure that excludes the defining markers could assess additional differences between the asthma subgroups. If the measure was derived from these same samples or labels, the comparison is exploratory. Directly assessing similarity to COPD would require a comparable COPD cohort and a defined outcome.

## Student follow-up (English translation)

The student proposed relating the expression of additional genes to a lung-function measurement such as FEV₁ in the same patients. The student would consider a small difference between Th2-high and Th2-low on a different score as evidence that weakens the hypothesis. The student did not specify the exact expression score, the expected direction of the relationship with FEV₁, or a threshold for a small difference.

## Assistant feedback and feasibility

- The subgroup comparison asks whether an additional gene-expression score differs between Th2-low and Th2-high asthma. A small, precisely estimated difference would weaken the prediction for that score. An imprecise estimate could be compatible with both small and substantial differences.
- The clinical association asks whether that score tracks lung function across individual patients. An analysis would require paired expression and spirometry records for the same participants. FEV₁ % predicted is one possible version of this outcome, subject to data availability and consistent measurement conditions. The published association in the COPD cohorts provides context. See [Christenson et al.](https://pubmed.ncbi.nlm.nih.gov/25611785/).
- The [series summary](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472) and the checked [Th2-low](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM1647628) and [Th2-high](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM1647669) sample records did not establish a source of patient-level FEV₁ values that can be linked to expression. Availability remains unverified. Group summaries would not support a patient-level association analysis.

**Next checkpoint:** The student predicts the direction of the proposed association between the additional expression score and FEV₁. The expression comparison remains a possible first step after the metadata audit. No original analysis was run.
