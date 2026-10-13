# Initial Dataset Feasibility Review

**Review date:** 2026-10-13  
**Status:** Preliminary desk review; no GEO2R analysis has been run yet.

## 1. Candidate dataset

**GSE67472 — Airway epithelial gene expression in asthma versus healthy controls**

Official record: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472

The GEO record states:
- Organism: *Homo sapiens*
- Experiment type: expression profiling by array (microarray)
- 62 subjects with mild-to-moderate asthma not on inhaled steroids and 43 healthy controls
- Asthma samples were stratified into Th2-high and Th2-low groups based on POSTN, SERPINB2, and CLCA1
- The stated study design includes asthma-versus-healthy and Th2-high-versus-Th2-low/healthy comparisons

**Interpretation:** The topic fits the project's molecular-biology interest and provides processed sample-level data. It remains necessary to confirm the group labels, data availability, and intended comparison before committing to the dataset.

## 2. Original paper lead

The GEO record links PMID 25611785:

Christenson SA et al. “Asthma-COPD overlap. Clinical relevance of genomic signatures of type 2 inflammation in chronic obstructive pulmonary disease.” *American Journal of Respiratory and Critical Care Medicine* (2015). DOI: https://doi.org/10.1164/rccm.201408-1458OC

PubMed record: https://pubmed.ncbi.nlm.nih.gov/25611785/  
PMC full-text record: https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/

**Not yet completed:** Full-text methods/results review and a careful mapping of the original paper's comparisons to the sample labels in GEO.

## 3. GEO2R suitability

Official GEO2R guide: https://www.ncbi.nlm.nih.gov/geo/info/geo2r.html

The NCBI guide states that GEO2R can compare groups within a GEO Series. For microarray studies, it uses submitter-supplied processed data and the limma package. It provides result tables, plots, adjusted p-values, log-fold changes, and an R script describing the analysis.

The guide also warns that users must inspect the original study design and data-processing fields; not every GEO series is automatically suitable for every comparison, and results may differ from the original publication.

**Preliminary conclusion:** GEO2R is a plausible low-code starting tool because GSE67472 is a microarray series. This is not yet proof that the planned comparison is configured correctly. The next session should inspect the actual GEO2R sample list and metadata before running or interpreting the analysis.

## 4. Main risks to check

1. **Group assignment:** The study has more than two biologically relevant groups. Avoid combining Th2-high and Th2-low samples without a reason.
2. **Interpretation:** A gene-expression difference is an association, not proof of a causal mechanism.
3. **Multiple testing:** Thousands of genes are tested; adjusted p-values should be prioritized over raw p-values.
4. **Reanalysis versus replication:** Using the same dataset as the original paper is a reanalysis, not independent replication.
5. **Candidate-gene circularity:** POSTN, SERPINB2, and CLCA1 were used in the original study's Th2 signature. If analyzing these genes in the same data, do not present that as an independent discovery.

## 5. Recommended next step

Read the paper's methods and relevant results, then create a sample-group mapping table with one row per GEO sample and fields for accession, title, source, group assignment, and evidence for assignment. Only then run a first GEO2R feasibility test.

## 6. Sources consulted

- NCBI GEO GSE67472: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472
- NCBI GEO2R guide: https://www.ncbi.nlm.nih.gov/geo/info/geo2r.html
- PubMed PMID 25611785: https://pubmed.ncbi.nlm.nih.gov/25611785/
- PMC full text: https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/

Accessed 2026-10-13.
