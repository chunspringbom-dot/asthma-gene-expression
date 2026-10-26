# DECISION — Guided Paper Reading and SAT-Adjusted Capstone Schedule

**Decision date:** 2026-10-26  
**Decision ID:** DECISION-2026-10-26-reading-workflow-and-sat-schedule  
**Status:** Adopted as a project workflow and planning change; **not** a new scientific result or an approved change of dataset/comparison.  
**Provenance:** Student-reported reading progress, student learning preferences and SAT date, existing project records, and public original-paper/GEO documentation.

## Background and evidence

- The original Oct 13 roadmap assumed an early Methods/Results review, mapped samples by Oct 25, and proceeded to data analysis in November.
- On Oct 26, the student confirmed that they had independently read **only part of the Abstract** and could explain part of the article's objective/methods, but did not yet understand all its results.
- A discussion showed confusion about **cohort** and **airway epithelium**, and suggested that guided conceptual explanation before source comparison would work better.
- The student's SAT date changed from **2026-11-07 to 2026-12-05**. Student also reported constrained computer access; priority should remain on SAT until that test.
- Previous schedule exit criteria for original-paper review, sample mapping and dataset feasibility **were not satisfied**. No GEO2R analysis output has been verified.

## Decision A — Learning workflow (adopted)

Replace an expectation of full independent technical reading before help with:

1. Assistant prepares a **brief, clearly attributed** explanation of the next relevant concept/section.
2. Student checks statements against the **original paper or GEO record** and identifies a precise source section or paragraph.
3. Student writes a short explanation **in their own words**, including at least one open question and any critique.
4. Student records source locator and commits notes to `research/paper-notes/`.

**Reason:** Smaller, auditable understanding checks fit the student's current biomedical/statistical background and limited study time. The workflow preserves independent verification rather than presenting assistant-generated summaries as student-authored work.

## Decision B — Timeline and capacity (adopted)

- **Until the December 5 SAT:** research **60–90 minutes/week** (one or two brief sessions), prioritizing small Abstract/Methods/GEO tasks. The Dec 5 test day is a rest/no-capstone day.
- **December 6:** optional reset; if recovery is needed, no project work required.
- **Starting December 7:** target **3–4 hours/week** if school workload allows. Begin metadata verification; do not jump to analysis solely to meet a calendar date.
- **Research completion target:** **2027-02-28** remains an aspiration, not a claim of guaranteed completion. Prioritize one credible comparison, transparent evidence, and honest limitations; reduce optional figures/secondary analyses if delayed.
- Replace the active Roadmap v1.0 with **v1.1**; preserve v1.0 at `docs/archive/PROJECT_ROADMAP_v1.0_2026-10-13.md`. Document missed original milestones rather than backdating work.

## Decision C — Study scope (unchanged)

- Provisional candidate **GSE67472**; provisional contrast asthma vs healthy airway epithelial expression.
- **Not** an analysis of the original paper's complete COPD cohorts or GLUCOLD treatment experiment.
- No claim of independent replication, clinical steroid-response prediction, or causation.
- Steroid biomarker study remains [an optional future direction](../../research/future-directions/treatment-response-biomarker-study.md), requiring different verified data and a new decision before any scope change.

## What changes in GitHub

- Active `docs/PROJECT_ROADMAP.md` → v1.1 with realistic date-scoped activities and revised exit gates.
- New reference explanation at `research/literature/christenson-2015-paper-structure.md`.
- Student's actual partial Abstract notes at `research/paper-notes/2026-10-26-abstract-reading-feedback.md`.
- Original reading-notebook status set to **In progress (Abstract partial)** instead of “not started”; blank sections remain blank.
- New chronological `docs/PROJECT_CHANGELOG.md` records what changed and why.
- New dated handoff points to these records and lists exact next tasks.

## Scientific checks motivating the reading change

- **Paper:** Christenson et al., PMID 25611785, reports several asthma/COPD cohorts and a randomized placebo-controlled GLUCOLD treatment study.
- **Dataset:** GEO [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472) contains 62 asthma + 43 healthy airway epithelial samples; it does not contain the paper's full COPD clinical treatment data.
- **TGM** (POSTN, SERPINB2, CLCA1) and **T2S** (100-gene Th2 signature) are distinct. Avoid merging concepts.
- Previous discussion of a missing untreated comparison was a general design lesson; **it is not a validated criticism of GLUCOLD**, which has a placebo comparison.

**Sources:** [Original paper full text](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/), [PubMed abstract](https://pubmed.ncbi.nlm.nih.gov/25611785/), [GEO record](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472).

## Review conditions

Revisit by **2026-12-13** after SAT, or earlier only if the student explicitly requests it. If sample labels/analysis feasibility fail, make a new dated dataset/analysis decision rather than silently substituting another study.
