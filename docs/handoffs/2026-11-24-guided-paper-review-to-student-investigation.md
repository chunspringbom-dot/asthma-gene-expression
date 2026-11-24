# Session Handoff — Guided paper review to student investigation

**Date:** 2026-11-24  
**Roadmap:** [v1.2](../PROJECT_ROADMAP.md)  
**Status:** Initial literature review and guided conceptual checkpoint completed; student-led investigation and original data analysis pending.

## 1. Current project and scope

The capstone investigates airway epithelial gene-expression heterogeneity in asthma. The provisional learning question is which genes differ between asthma and healthy controls in GSE67472 and how selected expression patterns compare with published findings. The dataset is a candidate, not a fully audited analysis cohort. It does not contain the original paper's separate COPD or GLUCOLD treatment cohorts.

## 2. Work actually completed

- Adopted AI-assisted evidence review and student-led follow-up under [v1.2](../PROJECT_ROADMAP.md); the preceding [workflow handoff](2026-11-24-ai-assisted-research-workflow.md) records the planning decision.
- Prepared an [initial literature evidence matrix](../../research/literature/2026-11-24-initial-evidence-matrix.md) comparing Christenson (2015), Woodruff (2007), Woodruff (2009), and Kuo (2017). It records published values, study designs, comparability and cohort-overlap cautions, and candidate follow-up questions. This is assistant-supported literature extraction, not capstone-computed output. See the [initial literature handoff](2026-11-24-initial-literature-evidence.md).
- Explained the original paper's Abstract, background and objectives, Methods (asthma, BAEC, SAEC, GLUCOLD), Statistical Analysis (normalization, differential expression, log2 fold change, multiple-testing adjustment, GSEA, PCA-based T2S), Results and Discussion/Limitations.
- Student answered all eight multiple-choice checkpoints correctly: Q1 B, Q2 B, Q3 A, Q4 C, Q5 B, Q6 A, Q7 C, Q8 B. See [guided learning checkpoint](../../research/paper-notes/2026-11-24-guided-methods-results-discussion.md). These responses establish guided recognition of concepts, not independent mastery, practical analytical competence or an independently authored interpretation.
- Discussed possible research directions: expression heterogeneity, Th2-low asthma, additional biomarker limitations, and treatment response. No student selection or rationale has yet been recorded.

## 3. Evidence and scientific boundaries

- [Christenson et al. (2015)](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/) — asthma-related signatures in COPD, clinical associations and endpoint-specific treatment response; no established clinical prediction tool. The earlier session relied on indexed primary text/abstracts because direct article opens encountered verification; full text and supplements still need further checking where necessary.
- [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472) — source describes 62 asthma and 43 control subjects, airway epithelial expression and platform GPL16311. Full individual sample labels, subgroup assignments, processing and analysis suitability are not yet verified.
- Th2-high/low labels based on POSTN, SERPINB2 and CLCA1 are not independently validated by comparing those same defining genes. A low signature does not establish a particular alternative mechanism.
- Published findings and illustrative graphs presented in the chat are not original capstone results. No analysis run, original result table, figure, independent validation or novel research contribution is established.

## 4. Decisions and exact resume point

Continue the evidence-first v1.2 workflow without restarting the paper explanation or redesigning the roadmap. Assistant recommended first exploring individual expression distributions (direction C), then investigating Th2-low asthma (direction A), subject to metadata and literature checks. The recommendation is not a student decision or a final research question.

**Unanswered student checkpoint — Q9:**

> If Th2-low patients still have asthma even though POSTN, SERPINB2 and CLCA1 expression is not high, what other biological features or mechanisms might be associated with their asthma? What data would you examine to investigate your hypothesis?

Accept a tentative answer in Korean or English. Ask the student to distinguish a hypothesis from evidence. Record the student's actual reasoning, not an AI-written substitute. Explain and evaluate it with source-linked evidence; do not infer a causal mechanism from gene expression alone.

## 5. Next actions and exit criteria

1. Ask Q9 and record the student's own answer and rationale. Exit: at least one testable or investigable idea and a proposed data type, with uncertainties stated.
2. Help verify one relevant source claim and check prior studies before claiming a research gap. Decide whether the question is feasible with GSE67472 or needs separate data.
3. Expand the literature matrix from four papers toward 5–10 as useful; audit representative GEO records, then the full eligible sample manifest, processing, contrast and analysis suitability.
4. Only after the audit passes, run a reproducible educational pilot if the data and tools are available. Save code/settings and actual outputs; explain effects, adjusted p-values and distributions. Label pilot-derived follow-up exploratory.
5. Student selects and investigates an interesting pattern and records a source-linked interpretation. No invented results or student contributions.

December 5 SAT remains the priority; no compulsory research output before the exam. After December 7, target 3–4 hours/week if feasible. February 28, 2027 remains conditional.

## 6. Files and Git state

- Initial literature matrix: commit `005c265a4c73c554cd5c1b1a143c1d61d078e879`.
- Initial literature handoff: commit `03b4ba32bb4eb561b476db1515bf22d3b5dc331b`.
- Guided learning checkpoint: commit `10e8fb0f7d26ab41114e1f7cbc37fd77cdf8e558`.
- This separate cumulative session handoff: see its Git file history. Changelog and README resume link are to be synchronized. No analysis files were created during this handoff session.

## 7. Resume prompt

Continue the Asthma Gene Expression capstone using roadmap v1.2 and this November 24 guided-paper-review-to-student-investigation handoff. The initial four-paper evidence matrix and guided Q1–Q8 checkpoint (8/8) are complete. Do not repeat the entire paper explanation. Start with unanswered Q9 about Th2-low asthma and what data could test my hypothesis. Evaluate my own reasoning, distinguish evidence from speculation, then proceed with source verification and dataset audit before any analysis. Keep documentation in English and discussion in Korean; preserve SAT priority.
