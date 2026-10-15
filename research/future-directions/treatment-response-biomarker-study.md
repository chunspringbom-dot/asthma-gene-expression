# Future Direction — Treatment-Response Biomarkers (Concept Only)

**Status:** Optional future research question, **not part of the approved GSE67472 analysis plan**.  
**Origin:** Discussion on 2026-10-14 about prognostic vs predictive biomarkers and why an untreated/comparator group matters.

## Proposed question

Can a baseline airway gene-expression marker identify patients who benefit *more from a specified anti-inflammatory treatment than from an appropriate comparator*?

This differs from the capstone's provisional primary question (asthma vs healthy gene-expression differences).

## Scientific distinction

- **Prognostic:** marker associated with disease outcome or course.
- **Predictive:** marker associated with how treatment benefit *differs relative to a comparison treatment or control*.
- A treatment-only before/after study cannot clearly separate these possibilities.
- A biomarker-by-treatment interaction can test whether the relative treatment effect differs by baseline biomarker value or group. Statistical support, clinical validity, and replication would all require substantial additional work.

## What an appropriate dataset would need

1. Baseline, pre-treatment biomarker or gene-expression measurements.
2. Well-defined treatment and comparator groups.
3. Reliable treatment assignment and confounder information; randomization is preferable for treatment-effect inference when ethical and feasible.
4. A prespecified clinical outcome and follow-up time.
5. Adequate sample size to test the interaction, not just overall improvement.
6. Independent validation before any clinical predictive claim.

## Why not claim this using GSE67472?

The candidate GEO series documents asthma and healthy airway-expression samples and asthma Th2 grouping; it is **not presently verified as a longitudinal randomized corticosteroid-response dataset**. A treatment-response analysis would require another dataset and a new feasibility review. The original publication discusses wider COPD/asthma research, which must not be conflated with the GSE67472 series' particular samples.

## Decision for now

**Park this as a conceptual extension**. Continue the existing roadmap: read Methods/Results, audit GEO sample metadata, define asthma-vs-healthy comparison if feasible, then conduct a cautious reanalysis. Revisit this proposal only after finishing the foundational project or if new verified data justify a formally documented scope change.

## Possible portfolio value

A carefully reasoned negative conclusion — “this dataset cannot answer a predictive-treatment-effect question” — demonstrates study-design understanding. It is not equivalent to identifying or validating a treatment-response biomarker.

## References to inspect

- [GSE67472 GEO series](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472)
- [Associated paper (PMC4407484)](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/)
- [Learning session record](../paper-notes/2026-10-14-copd-asthma-biomarkers-learning.md)
