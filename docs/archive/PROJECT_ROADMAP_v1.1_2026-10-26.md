# Project Roadmap — v1.1 (SAT-Adjusted, Evidence-Gated)

**Repository:** https://github.com/chunspringbom-dot/asthma-gene-expression  
**Date revised:** 2026-10-26  
**Working period:** 2026-10-13 through 2027-02-28  
**Version:** **1.1 — current**  
**Earlier plan:** [v1.0 archived intact](archive/PROJECT_ROADMAP_v1.0_2026-10-13.md)  
**Decision:** [2026-10-26 reading workflow + SAT schedule](decisions/DECISION-2026-10-26-reading-workflow-and-sat-schedule.md)  
**Change history:** [PROJECT_CHANGELOG.md](PROJECT_CHANGELOG.md)

## 1. Objective and honest current status

Produce a **small, credible, reproducible student reanalysis** of asthma-related airway epithelial expression, with a clearly scoped question, verified sample selection, analysis settings, original and assistant sources attributed, interpretable plots/tables, limitations, and transparent GitHub history.

**Actual work as of Oct 26:** repository planning/notes exist; the student has independently read **only part of the original paper's Abstract**; a supported structural orientation has been prepared. The candidate GEO dataset **GSE67472 is not yet fully verified**, sample mapping is incomplete, and **no GEO2R analysis has been run or verified**. The prior Oct/Nov milestones should **not** be reported as completed.

**Provisional question (unchanged):** Which genes differ between asthma and healthy airway-epithelial samples in GSE67472, and how do carefully selected inflammation-related expression patterns compare with the original report?

## 2. Capacity rule, including SAT postponed to December 5

The student reported the SAT examination is now on **Saturday, 2026-12-05** (previously planned Nov 7). Access to a computer is constrained.

- **Through Dec 4:** target **60–90 minutes/week** on the capstone, with a maximum of two short sessions. Keep SAT as the priority and do not require lengthy computer-based analyses.
- **Dec 5:** SAT — no scheduled research tasks.
- **Dec 6:** optional rest/reset, not a completion gate.
- **From Dec 7:** aim for **3–4 hours/week if feasible**, adjusting for other school duties. Use available computer time for metadata review and GEO2R; reading notes can be done with minimal computer time.
- **Feb 28 final portfolio remains a target, not guaranteed.** If a gate fails, narrow scope (one primary contrast, limited figures) or openly mark the analysis incomplete, rather than fabricate results or rush invalid comparisons.

## 3. Reading and research workflow

1. **Orient:** check README, this roadmap, latest handoff, recent change log.
2. **Explain (attributed):** assistant briefly outlines necessary terminology/article structure.
3. **Verify:** student reads the exact source subsection and compares each claim with the original.
4. **Explain independently:** student writes 3–5 sentences and at least one question, identifying original section/figure/sample ID.
5. **Commit:** save a small, honest paper note or dataset inspection with evidence and clear authorship.
6. **Review exit gate:** do not proceed until the evidence requirement is satisfied.
7. **Handoff:** log work, unanswered questions, file/commit links, next action.

**Evidence status labels:** Verified source fact / Student interpretation / Assistant explanation / Provisional plan / Analysis output. None should be silently substituted for another.

## 4. Weekly plan — October 26, 2026 to February 28, 2027

The v1.0 schedule for **Weeks 1–2 (Oct 13–25)** was missed in part. The corresponding deadlines are superseded below, not retroactively checked off.

| Week / dates | Practical objective | Expected deliverable / honest exit criterion |
|---|---|---|
| W3 · Oct 26–Nov 1 | Finish careful **Abstract orientation**; learn cohort, airway epithelium, overall paper/dataset distinction | Student writes 3–5 source-linked sentences and 1 question; no forced full-paper comprehension |
| W4 · Nov 2–8 | Study asthma-specific **Methods** using guided reading | Explain subjects/tissue/measurement and identify the corresponding Methods section |
| W5 · Nov 9–15 | Study **GEO Summary / Overall design** and distinguish asthma data from COPD treatment cohorts | Short evidence table with 62/43 groups, platform, intended comparison, uncertainties |
| W6 · Nov 16–22 | Inspect a **small pilot** of 5–10 GSM records if computer access permits | Pilot metadata notes with exact GSM links; any ambiguity explicitly recorded |
| W7 · Nov 23–29 | Resolve 1–2 major vocabulary or subgroup questions and review sample label consistency | Vocabulary corrections + list of outstanding metadata questions |
| W8 · Nov 30–Dec 6 | SAT-focused maintenance and exam Dec 5 | Zero or one short notebook commit; no study output or hard deadline required |
| W9 · Dec 7–13 | **Re-entry after SAT**; review notes and inspect complete sample inventory | Clear inventory progress and proposed group mapping, including unresolved samples |
| W10 · Dec 14–20 | Verify **full 105-sample mapping**, define primary contrast and exclusions | Group mapping with citations; decision for eligible contrast; if not verified, record blocker |
| W11 · Dec 21–27 | Test processed data suitability / GEO2R feasibility; run only if W10 gate passes | Recorded tool settings and test output **or** reasoned stop/change decision |
| W12 · Dec 28–Jan 3 | Obtain and audit a **first primary analysis** only if feasible; account for study workload | Versioned output, source, methods and reproducibility notes **or** documented unresolved feasibility |
| W13 · Jan 4–10 | Learn adjusted p-values, log fold change, microarray probe/gene mapping | Plain-English data dictionary and statistical caveats grounded in actual output, if available |
| W14 · Jan 11–17 | QC first results or complete delayed feasible analysis | Documented data/group checks; no unreported re-grouping |
| W15 · Jan 18–24 | Select limited result table and (if justified) 1–2 figures | Result table/plots with labels, sample counts, captions, settings |
| W16 · Jan 25–31 | Examine limited biological context and interpretation | Gene-evidence table with original/independent references and limitations |
| W17 · Feb 1–7 | Reproducibility and reviewer-style critique | Reproduction checklist with issues resolved/flagged |
| W18 · Feb 8–14 | Draft scientific report | Methods/Results/Limitations accurately reflect performed analysis; cite everything |
| W19 · Feb 15–21 | Portfolio readability, README, admission narrative | Accessible repo index, concise research story, individual contribution note |
| W20 · Feb 22–28 | Final QA and retrospective; freeze only supported results | Final commit/handoff, limitations, explicit unresolved items and next-step options |

## 5. Revised evidence gates

- **Gate A — Dec 13:** Can the student state the article/dataset boundary, airway samples and key methods accurately, with source locators?
- **Gate B — Dec 20:** Are individual sample labels, feasible primary contrast, inclusion/exclusion rules, and relevant preprocessing understood and documented? **If not, do not run GEO2R.**
- **Gate C — Dec 27 / Jan 3:** Is GEO2R/other selected workflow usable and is the first primary result verifiable? If not, document blockage and reduce or revise scope.
- **Gate D — Feb 7:** Can another person reproduce every reported result, trace sources, and check statistical limitations?
- **Gate E — Feb 28:** Are the report, repository index, figures, sources, and known limitations consistent? If unfinished, publish only honestly documented work; do not claim completed validation.

Re-check feasibility **on Dec 13**. If a primary gate is missed, write a dated handoff with blocker, impact and revised task; do **not** quietly move on.

## 6. Change control and archive

- `docs/PROJECT_CHANGELOG.md`: chronological record of project events and mistakes/corrections.
- `docs/decisions/DECISION-YYYY-MM-DD-short-title.md`: motivation/evidence behind significant workflow/timing changes and **all** dataset, contrast, methodology changes.
- `docs/archive/PROJECT_ROADMAP_v1.0_2026-10-13.md`: preserved original Oct 13 plan for accountability.
- `docs/handoffs/YYYY-MM-DD-short-topic.md`: session snapshots with current state, evidence, files, Git state, unknowns, and resume instructions.
- Git commits: exact file history. Never confuse a retrospective write date with when the student actually read a paper.
- The primary cohort is currently GSE67472 **only as a candidate**. Future corticosteroid-response prediction would need separate suitable data and an explicit new project decision.

## 7. Useful source and working links

- [Original paper full text, 2015](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/25611785/)
- [GSE67472 official GEO record](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472)
- [GEO2R guide](https://www.ncbi.nlm.nih.gov/geo/info/geo2r.html)
- [Paper structure reference (assistant-prepared)](../research/literature/christenson-2015-paper-structure.md)
- [Student Abstract initial interpretation](../research/paper-notes/2026-10-26-abstract-reading-feedback.md)
- [Source-linked reading notebook](../research/paper-notes/2026-10-13-original-paper-reading.md)
- [Project charter — provisional question and feasibility rules](PROJECT_CHARTER.md)
- [Handoff rules](SESSION_HANDOFF_RULES.md)
