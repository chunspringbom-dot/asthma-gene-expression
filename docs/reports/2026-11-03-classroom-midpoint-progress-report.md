# Asthma Gene Expression Capstone
## Classroom Midpoint Progress Report

**Student:** Chanyoung Kang  
**Date:** November 3, 2026  
**Purpose:** Classroom midpoint progress check  
**Repository:** [Asthma Gene Expression Capstone](https://github.com/chunspringbom-dot/asthma-gene-expression)

## Research interest and motivation

I am exploring how gene-expression data can help researchers understand airway inflammation in asthma and chronic obstructive pulmonary disease (COPD). I became interested in whether people with COPD may have biological features similar to those found in asthma, even when their clinical histories differ.

My current goal is to learn how an existing study used gene-expression data and then investigate whether a carefully scoped reanalysis of public asthma data is feasible. Later, I hope to identify an independently testable question by comparing related studies and their limitations.

## Provisional research question

> In GSE67472, which genes show different expression patterns in airway epithelial samples from people with asthma and healthy controls, and how do selected inflammation-related patterns compare with the original study?

This question is provisional. I will refine it after checking the sample labels, data processing, and suitability of the available analysis tools. The initial comparison is an educational reanalysis of previously studied data, not a claim of a new discovery.

## Progress so far

### Reading the original paper

I selected Christenson et al. (2015) as the starting point for the project and studied its Abstract with guided explanations and discussion. I understand the study's general approach: identify asthma-associated gene-expression patterns, examine related patterns in separate COPD cohorts, and investigate associations with clinical features and corticosteroid response.

The paper reports that higher type 2 signature (T2S) scores were associated with lower lung function in the COPD cohorts and with certain asthma-like features. It also reports an association between baseline T2S and improvement in hyperinflation with corticosteroid treatment compared with placebo in the GLUCOLD study. These are **the published researchers' findings**, not results from my own analysis.

I learned that a cohort is a defined group of research participants and that an association does not by itself establish causation. I also discussed how a p-value is interpreted under a null hypothesis and why it does not describe the size of an effect.

### Beginning the Methods section

With guidance, I began studying the paper's section **Methods → Subjects and Sample Preparation → Asthma dataset—asthma and control subjects**. The paper describes previously collected airway epithelial brushing data from 62 people with mild-to-moderate asthma who were steroid-naive and 43 controls without asthma. It reports microarray and quantitative PCR gene-expression measurements.

The paper also describes dividing the 62 asthma participants into Th2-high (40) and Th2-low (22) groups using a three-gene mean based on POSTN, SERPINB2, and CLCA1. I am still reviewing the methods; I have not completed the full Methods section.

### Identifying the dataset and its scope

I identified [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472) as a candidate dataset. It contains the asthma and healthy-control airway epithelial series. The broader paper also used separate COPD datasets and the GLUCOLD treatment study. Therefore, GSE67472 alone cannot be used to directly analyze COPD treatment response.

### Organizing the project

I created a GitHub repository with a project roadmap, reading notes, decision records, and handoff documents. The seven-step plan moves from understanding the original paper and learning the dataset to comparing literature, identifying limitations, defining a feasible question, analyzing data, and writing an English report. Source-based explanations and my own understanding will be distinguished in the notes.

## Current status and limitations

The project is in **Step 1: understanding the original paper**. I have discussed the Abstract and begun the asthma-specific Methods with assistance. I have not verified all 105 individual sample labels or assessed the processed data and analysis settings in full.

**No verified GEO2R analysis, independent validation, original result table, or figure has been produced.** An educational reanalysis would help develop practical skills and assess reproducibility, but it would not automatically constitute a novel finding. Whether a distinct contribution is feasible will depend on the literature and available data.

## Next steps

1. Continue the asthma-specific Methods, focusing on participants, tissue, measurements, and group definitions.
2. Inspect the GEO record and verify sample metadata, group labels, processing, and the suitability of GEO2R before any analysis.
3. After the December 5 SAT, continue the sample audit and, if the data and comparison are suitable, perform a documented educational reanalysis.
4. Compare approximately 5–10 related papers and identify limitations or unanswered questions.
5. Decide whether a feasible independent question can be supported; prepare an English report that accurately distinguishes existing findings from any work I perform.

Before the SAT, the current plan is approximately 60–90 minutes per week for this project. The pace and final scope will depend on school workload and verification of the data.

## Sources

1. Christenson SA, et al. Asthma-COPD overlap: Clinical relevance of genomic signatures of type 2 inflammation in chronic obstructive pulmonary disease. *American Journal of Respiratory and Critical Care Medicine*. 2015;191:758–766. [PubMed](https://pubmed.ncbi.nlm.nih.gov/25611785/) · [Full text](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/).
2. NCBI GEO. [GSE67472: Airway epithelial gene expression in asthma versus healthy controls](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472).
3. [Project roadmap](../PROJECT_ROADMAP.md) and [research direction handoff](../handoffs/2026-10-27-seven-step-research-direction.md).
