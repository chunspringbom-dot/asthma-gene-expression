# Session Handoff — Seven-Step Research Direction and README Integration

## 1. Session metadata

- **Date:** 2026-10-27
- **Repository / branch:** [chunspringbom-dot/asthma-gene-expression](https://github.com/chunspringbom-dot/asthma-gene-expression), `main`
- **Goal:** Translate the student's proposed seven-step progression into an accessible README roadmap and document the major strategic decision for a future session.
- **Status:** Documentation updates committed; **no dataset analysis or independent validation conducted**.
- **Authorship:** Assistant-drafted handoff reflecting the student's explicit requested stages, questions, and research decision. This is not presented as student-written scientific analysis.

## 2. Current project state

- **Broad field:** Asthma/COPD inflammation and airway epithelial gene expression.
- **Candidate dataset:** [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472), **provisional**.
- **Current operational research question:** In a public gene-expression dataset, which genes differ between airway epithelial samples from people with asthma and healthy controls, and are selected inflammation-related patterns consistent with the original paper? **Provisional / educational reproduction.**
- **Long-term direction:** Evaluate reproducibility and methodological limitations, review literature, and only then define a defensible distinct research question **if feasible**.
- **Research phase:** Step 1 of the long-term seven-step progression (paper understanding), **in progress**. No verified GEO2R run or original analysis exists.
- **Calendar:** The existing [SAT-adjusted v1.1 roadmap](../PROJECT_ROADMAP.md) remains the weekly execution schedule. SAT December 5, 2026; short reading sessions beforehand, sample audit/possible analysis afterward. The seven-step roadmap is **conceptual, not a replacement deadline schedule**.

## 3. Work completed this session

1. Read the live repository README, roadmap v1.1, changelog, handoff rules, prior session handoff, project charter, and October 27 strategy decision.
2. Added the student's requested **seven-stage research roadmap** to the [README](../../README.md#seven-step-research-roadmap-long-term-direction):
   1. Understand the existing asthma/COPD paper (biological foundation).
   2. Learn GSE67472 structure and analysis (data-analysis skills).
   3. Compare roughly 5–10 related papers (existing knowledge).
   4. Identify limitations (research gap).
   5. Finalize an original, feasible question (distinct contribution).
   6. Perform data analysis (hypothesis evaluation).
   7. Write an English research paper (transparent scientific report).
3. Linked the decision record and this handoff from the README's project-control navigation.
4. Logged this README-roadmap/handoff step in the [PROJECT_CHANGELOG](../PROJECT_CHANGELOG.md).
5. Preserved the prior roadmap v1.1, existing files, and explicit 'not completed' status.

**These are documentation and strategy outputs, not research results.**

## 4. Evidence and sources

- [Christenson et al. (2015), PubMed](https://pubmed.ncbi.nlm.nih.gov/25611785/) — existing scientific paper under guided study; no claim of completed full-paper reading.
- [NCBI GEO GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472) — provisional public study series requiring sample-group and platform verification before analysis.
- [Prior October 27 research-direction decision](../decisions/DECISION-2026-10-27-reproduction-to-independent-research.md) — assistant-drafted synthesis of student's questions about originality, replication, and plagiarism; explains why this roadmap was adopted.
- [Roadmap v1.1](../PROJECT_ROADMAP.md) and [project charter](../PROJECT_CHARTER.md) — existing capacity, timing, gates, and provisional analysis scope.
- **Evidence type:** The seven stages are the student's proposed **plan**, not findings sourced from a paper. Links to scientific sources are study references, not evidence that analysis has occurred.

## 5. Decisions made

- **Adopted:** Expose the requested seven-step **long-term research direction in README**, separate from the weekly roadmap.
- **Adopted:** Write a dated handoff because the change affects research strategy and files, per [handoff rules](../SESSION_HANDOFF_RULES.md).
- **Unchanged:** SAT-adjusted weekly execution roadmap v1.1 and evidence gates; GSE67472 only as a candidate; no claim of a new biomarker or treatment prediction.
- **Provisional:** A genuinely independent question or external validation will be pursued **only if** literature review, data availability, and methodological feasibility justify it.
- **Integrity:** Reproduction alone is not plagiarism when properly credited, but repeating prior work does not demonstrate novelty; distinguish reproducibility, validation, and causal claims.
- **Instruction:** Do not continue with quiz questions until the student asks.

## 6. Files and Git state

**Files updated and verified by successful GitHub write responses (main branch):**

- `README.md` — added the seven-step table, explicit status and references; commit [`b50bed0872ed9704d38f5a985844604f83bf6b8a`](https://github.com/chunspringbom-dot/asthma-gene-expression/commit/b50bed0872ed9704d38f5a985844604f83bf6b8a).
- `docs/PROJECT_CHANGELOG.md` — added timeline entry, links and clarified project status; commit [`844a27e556643ba2be3321d9f794d9d43709e23f`](https://github.com/chunspringbom-dot/asthma-gene-expression/commit/844a27e556643ba2be3321d9f794d9d43709e23f).
- `docs/handoffs/2026-10-27-seven-step-research-direction.md` — **this new handoff**; verify file creation SHA from GitHub response after writing.

**Related earlier commits:**
- Strategic decision note: [`cf01c04e537b14d0bf9ef9a245d2b2fe4fe17543`](https://github.com/chunspringbom-dot/asthma-gene-expression/commit/cf01c04e537b14d0bf9ef9a245d2b2fe4fe17543).
- Earlier changelog record of that decision: [`fd35b1e66951bc42e4b2e8f5ca3acc199ea8a1f5`](https://github.com/chunspringbom-dot/asthma-gene-expression/commit/fd35b1e66951bc42e4b2e8f5ca3acc199ea8a1f5).

All changes use GitHub's file-write API rather than a local `git push` command; successful writes update the default branch directly.

## 7. Open questions and blockers

1. Student has not independently completed a full reading of the Christenson paper; detailed asthma methods still need review.
2. GSE67472 individual sample mapping, preprocessing, and GEO2R suitability remain unverified; no result tables or plots.
3. Need a genuinely source-checked comparison of 5–10 related papers to establish whether a meaningful independent question remains unanswered.
4. Independent datasets for any extension have not been chosen, validated, or checked for overlapping participants.
5. Student's SAT December 5 and limited computer time constrain near-term work.
6. The final paper might be a transparent educational reanalysis if feasible original novelty cannot be established.

## 8. Next actions

1. **Next short research block (pre-SAT):** Continue the original Christenson paper, emphasizing asthma-specific Methods and the distinction among asthma, COPD, and GLUCOLD cohorts.
2. Write **3–5 source-linked sentences in the student's own words** and at least one open question; save under the existing paper-notes workflow with accurate authorship.
3. When time allows, start a literature comparison matrix with verified paper/dataset links; do not pretend it has been completed.
4. After SAT, verify GSE67472 sample groups and processed data availability before running any GEO2R workflow.
5. Only after reviewing prior analyses and feasible data, decide whether an independently testable question can be defined. Document any change in a dated decision and changelog.

## 9. Resume prompt

> Continue the Asthma Gene Expression Capstone at https://github.com/chunspringbom-dot/asthma-gene-expression. Read the README seven-step research roadmap, `docs/handoffs/2026-10-27-seven-step-research-direction.md`, `docs/PROJECT_ROADMAP.md` v1.1, `docs/PROJECT_CHANGELOG.md`, and `docs/decisions/DECISION-2026-10-27-reproduction-to-independent-research.md`. The seven-step plan is long-term scientific direction, while the weekly SAT-adjusted roadmap remains active. We are in Step 1 (understanding the original paper), not finished with Methods, and no GEO2R analysis or independent validation has occurred. The working GSE67472 question is educational and provisional. Continue guided reading of the asthma-specific Methods, then student-authored source-linked notes. Keep research documentation in English, explanations to me in Korean, do not overclaim originality, and do not quiz me unless I ask.
