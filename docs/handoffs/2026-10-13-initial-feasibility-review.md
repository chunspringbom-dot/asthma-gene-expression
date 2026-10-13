# Handoff — Initial Dataset Feasibility Review

## 1. Session metadata

- **Date:** 2026-10-13
- **Session goal:** Complete an initial source-based feasibility review after project setup.
- **Status:** Desk review recorded; no differential-expression analysis has been run.

## 2. Current project state

- **Repository:** https://github.com/chunspringbom-dot/asthma-gene-expression
- **Phase:** Dataset feasibility review.
- **Provisional question:** In a public gene-expression dataset, which genes differ between airway epithelial samples from people with asthma and healthy controls, and are selected inflammation-related gene-expression patterns consistent with the original study?
- **Candidate dataset:** GSE67472, not yet finally approved.

## 3. Work completed

- Reviewed the official NCBI GEO series record.
- Identified the original paper linked from GEO (PMID 25611785).
- Reviewed the official GEO2R guide to understand capabilities and caveats.
- Added `research/initial-dataset-feasibility-review.md` to the repository.

## 4. Evidence and sources

- **GEO GSE67472:** https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472
  - Official record describes a human airway epithelial microarray study with 62 mild-to-moderate asthma subjects not on inhaled steroids and 43 healthy controls.
  - The record says asthma samples were stratified as Th2-high and Th2-low using POSTN, SERPINB2, and CLCA1.
- **Original paper lead:** Christenson SA et al. (2015), “Asthma-COPD overlap. Clinical relevance of genomic signatures of type 2 inflammation in chronic obstructive pulmonary disease.”
  - PubMed: https://pubmed.ncbi.nlm.nih.gov/25611785/
  - Full text: https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/
  - The full-text methods and results have **not yet been reviewed in detail**.
- **NCBI GEO2R guide:** https://www.ncbi.nlm.nih.gov/geo/info/geo2r.html
  - GEO2R can compare sample groups within a GEO Series and provides tables/plots and adjusted p-values.
  - NCBI warns users to check the original design and processed-data comparability; a tool's ability to run an analysis does not itself prove the comparison is scientifically appropriate.

## 5. Decisions made

- GSE67472 remains a promising **provisional candidate** because it matches the topic and uses microarray data.
- GEO2R is the leading low-code analysis candidate, pending direct inspection of the series' samples and groups.
- Use adjusted p-values for genome-wide significance interpretation where appropriate.
- Do not call analysis of GSE67472 independent replication of the original study.
- Treat POSTN, SERPINB2, and CLCA1 carefully: they are part of the original study's Th2 signature, so examining them in the same dataset is not independent validation.

## 6. Files and Git state

- Added `research/initial-dataset-feasibility-review.md`
- Reported commit SHA: `69b9731e67159f34a0612d049508f7c5519fe112`
- Earlier kickoff files remain in the default branch; see the previous handoff `docs/handoffs/2026-10-13-kickoff.md`.

## 7. Open questions / blockers

- What exactly did the original paper do with the GSE67472 data?
- Which sample metadata fields reliably identify asthma, healthy control, Th2-high, and Th2-low groups?
- Can GEO2R be configured to reproduce the planned asthma-versus-healthy comparison without incorrectly mixing subgroups?
- Is the primary research question best kept as a broad asthma-versus-control comparison or narrowed to a more specific, defensible contrast?

## 8. Next actions

1. Review the full-text paper's Methods and Results sections.
2. Open the GSE67472 GEO2R page and inspect its sample table and metadata.
3. Create a sample-group mapping table with evidence for each assignment.
4. Decide the primary comparison before interpreting results.
5. Run a feasibility analysis only after group mapping is checked, and document settings and outputs.

## 9. Resume prompt

> Continue the asthma gene-expression capstone at https://github.com/chunspringbom-dot/asthma-gene-expression. Read README.md, docs/SESSION_HANDOFF_RULES.md, docs/PROJECT_CHARTER.md, and the latest handoff. The latest work is recorded in research/initial-dataset-feasibility-review.md. GSE67472 is still provisional. The official GEO record describes 62 mild-to-moderate asthma subjects and 43 healthy controls, with Th2-high/Th2-low asthma subgroups defined using POSTN, SERPINB2, and CLCA1. GEO2R is plausible but group assignment has not been checked directly and no analysis has been run. Next, review the original paper's methods/results and inspect GEO sample metadata; build a group-mapping table before analyzing. Do not overstate reanalysis as independent replication or gene-expression association as causation. Add a handoff at the end of the session.
