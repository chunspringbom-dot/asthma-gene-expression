# Initial literature evidence matrix — airway epithelial type 2 inflammation
**Date:** 2026-11-24 | **Workflow:** v1.2 | **Authorship:** AI-assisted source review; student interpretation pending.

## Scope and evidence level

A targeted, non-systematic search for primary human airway expression studies linking asthma, type 2 inflammation and corticosteroid response. Four articles (anchor + three related) were reviewed using indexed primary article text and abstracts retrieved on November 24. Direct PMC/PubMed opens encountered browser verification; full supplements and all tables have not been audited. GEO series record was directly accessible. Published numbers below are extracted, not new calculations. No patient-level data or expression analysis was run. Student contributions must be added separately after discussion.

## 1. Anchor: Christenson et al. (2015)

[Full article](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/) | [PubMed 25611785](https://pubmed.ncbi.nlm.nih.gov/25611785/) | DOI 10.1164/rccm.201408-1458OC

Question: Can asthma-associated expression patterns characterize a biologically relevant COPD subgroup and relate to clinical features and corticosteroid response? The asthma series comprised 62 asthma and 43 controls. Expression patterns were compared with two separate COPD-related cohorts (BAEC 237 and SAEC 171 as reported in Abstract; these include comparison subjects, not exclusively COPD cases), then related to clinical measures in GLUCOLD (89 in the Abstract, randomized placebo-controlled study; endpoint-specific sample sizes may differ). TGM summarizes standardized expression of POSTN, SERPINB2 and CLCA1; T2S summarizes a broader 100-gene signature. GSEA compared ranked genes rather than pooling incompatible platforms and subject groups. See Abstract, Figure 1, Results: GSEA Identifies Gene Expression Similarities between Asthma and COPD, Figures 2–3.

### Selected published results

| Association or comparison | Reported direction / value | Reported P | Source locator |
|---|---|---|---|
| Top 200 asthma differential genes vs COPD-associated expression | Concordance / enrichment | <0.001 | Abstract; Fig. 2 (100 increased and 100 decreased) |
| T2S and lung function | Inverse association | <0.001 | Abstract; Fig. 3 |
| T2S and airway wall eosinophils | Positive | 0.003 | Abstract; GLUCOLD |
| T2S and blood eosinophil percentage | Positive | 0.03 | Abstract; GLUCOLD |
| T2S and bronchodilator reversibility | Positive | 0.01 | Abstract; GLUCOLD |
| T2S and corticosteroid-associated improvement in hyperinflation | Positive | 0.019 | Abstract; GLUCOLD |
| T2S and asthma history | No reported association | Not extracted | Abstract |
| SAEC T2S: nonsmokers without obstruction | −2.19 ± 4.70 (mean ± SD) | <0.001 for comparisons as reported | Fig. 3B |
| SAEC T2S: smokers without obstruction | 0.16 ± 2.39 | see above | Fig. 3B |
| SAEC T2S: smokers with COPD | 3.51 ± 2.89 | see above | Fig. 3B |

P-values refer to different tests/endpoints and are not comparable measures of effect size. A mean ± SD is not a confidence interval or an individual distribution. Clinical association is not causation or proof of diagnostic accuracy. Smoking, tissue site, treatment and cohort composition may matter; the article itself discusses smoking.

## 2. Comparison matrix (published evidence only)

| Paper / source | Participants and tissue | Method / contrast | Main reported finding | Limitation for this capstone |
|---|---|---|---|---|
| Woodruff et al. 2007, [PMID 17898169](https://pubmed.ncbi.nlm.nih.gov/17898169/), [full text](https://pmc.ncbi.nlm.nih.gov/articles/PMC2000427/) | 42 asthma, 28 healthy nonsmokers, 16 current smokers without asthma; airway epithelial brushings | Microarray; PCR follow-up; inhaled fluticasone vs placebo; cell culture experiments | POSTN, CLCA1 and SERPINB2 increased in asthma, not the smoker controls; corticosteroid exposure reduced expression of the three genes | Small selected cohorts; treatment endpoints differ from COPD; check cohort reuse |
| Woodruff et al. 2009, [PMID 19483109](https://pubmed.ncbi.nlm.nih.gov/19483109/), [full text](https://pmc.ncbi.nlm.nih.gov/articles/PMC2742757/) | 42 mild-to-moderate asthma, 28 healthy controls; bronchial epithelial brushings | Microarray/qPCR; clustering based on IL-13-inducible genes | 22 Th2-high, 20 Th2-low; low group resembled controls on the signature; steroid-associated FEV1 improvement differed by subgroup | Reanalysis of earlier epithelial data, not independent confirmation of 2007; classification genes cannot independently validate their own labels |
| Christenson et al. 2015, [PMID 25611785](https://pubmed.ncbi.nlm.nih.gov/25611785/) | Asthma series 105; separate COPD-related cohorts and GLUCOLD (see above) | Microarrays, GSEA, TGM and T2S; clinical associations | Asthma-associated expression patterns occur in COPD; T2S relates to selected inflammatory and clinical features | GSE67472 alone does not contain COPD or GLUCOLD; overlap of earlier asthma cohorts not fully audited |
| Kuo et al. 2017, [PMID 27580351](https://pubmed.ncbi.nlm.nih.gov/27580351/), [DOI](https://doi.org/10.1164/rccm.201512-2452OC) | 107 moderate-to-severe asthma participants; bronchial biopsies and epithelial brushings, U-BIOPRED | Gene set variation analysis of 42 signatures; topological clustering and signature refinement | Two distinct groups with elevated Th2 cytokine expression and reported lack of corticosteroid response; group characteristics differ | More severe population, tissue/medication and method differences; not directly comparable to steroid-naive mild/moderate asthma; no causal contradiction established |

### Quantitative literature extraction

Woodruff 2007, Results (baseline expression and 4-week FEV1 improvement among corticosteroid-treated subjects): CLCA1 r=0.60, P=0.011; POSTN r=0.49, P=0.048; SERPINB2 r=0.53, P=0.027. These are reported correlations, not fold changes; do not compare directly with Christenson T2S scores. Woodruff 2009, Results (lung function response to inhaled corticosteroids): at 4 weeks, 9/10 Th2-high and 1/6 Th2-low treated subjects exceeded 150 mL FEV1 improvement, in the reported subset, not all 42 asthma participants. Kuo 2017 Abstract reports 107 subjects and 42 signatures; no gene-level comparable effect estimate extracted here. Do not synthesize these heterogeneous statistics or treat papers as independent cohorts without checking overlap.

## 3. Dataset orientation (not a full sample audit)

[NCBI GEO GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472), Summary / Overall design / Platforms / Samples: bronchial airway epithelial brushings, 62 mild-to-moderate asthma subjects not on inhaled steroids and 43 controls, Affymetrix HG-U133 Plus 2.0 with Brainarray Entrez CDF 14.0.0 (GPL16311). The 105 sample titles are listed; exact individual characteristics, subgroup assignments, preprocessing, expression matrix and analysis suitability remain to be checked. Do not assign subgroup using assumptions. The three-gene subgroup labels are not independent of the genes that define them.

## 4. Questions for the student (not yet selected)

- A. Why can some asthma patients have a low type 2 expression signature? Investigate non-defining genes in T2-low versus controls if subgroup labels and data permit.
- B. Why does the association between T2 markers and corticosteroid response vary between early asthma studies and moderate/severe asthma in U-BIOPRED? Compare severity, drug exposure, tissue and endpoints. This is literature investigation unless suitable clinical outcome data are located.
- C. How much does an all-asthma versus control comparison conceal heterogeneous expression? Compare distributions of POSTN, CLCA1 and SERPINB2 and preselect additional genes; do not interpret differences between groups defined by these genes as independent validation.
- D. Could smoking affect T2 scores independently of COPD? Literature follow-up only with current dataset.

Existing secondary analysis lead: [PMID 35550122](https://pubmed.ncbi.nlm.nih.gov/35550122/) already reports Th2-high asthma co-expression genes evaluated in GSE67472. [PMID 33791298](https://pubmed.ncbi.nlm.nih.gov/33791298/) uses GSE67472 for Wnt-related comparisons. These are leads for later full review, not a new literature gap claim.

**Suggested starting point:** C as an educational pilot, then A or B as student-selected investigation. No original analysis or novelty claim; no student question has yet been recorded.

## 5. Exit status

Initial evidence matrix created (anchor + 3 papers); source-level GEO orientation done. Full-text/supplement checks, sample manifest, processing and actual analysis still pending. Next: student chooses one question and explains why; check representative original sources and sample metadata. SAT priority preserved.
