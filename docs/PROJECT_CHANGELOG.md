# Project Changelog — Chronological Research and Workflow History

This is an **event timeline**, not a list of claimed scientific achievements. Each entry distinguishes completed documentation, student learning, provisional decisions, and unfinished work. Git commit history is the technical audit trail; dated handoffs and decision files explain the reasons.

## Timeline

| Date | What actually happened | Consequence / files | Completion status |
|---|---|---|---|
| **2026-10-13** | Set up a dedicated asthma gene-expression capstone repository. Drafted the first research question and selected **GSE67472 as a candidate**, not a final dataset. | [README](../README.md), [charter](PROJECT_CHARTER.md), [kickoff handoff](handoffs/2026-10-13-kickoff.md) | Documentation completed; feasibility outstanding |
| **2026-10-13** | Performed a source-based *desk review* of GEO and the original paper lead; set up weekly roadmap and handoff rules. | [Initial feasibility review](../research/initial-dataset-feasibility-review.md), [original v1.0 roadmap](archive/PROJECT_ROADMAP_v1.0_2026-10-13.md) | Desk review completed; **no GEO2R analysis** |
| **2026-10-14** | Student discussed COPD, heterogeneous disease, pathogenesis, corticosteroids and biomarkers; chose Q1 B, Q2 C, Q3 B, Q4 B. Full reasoning/questions not available in retained discussion summary. | [Retrospective learning notes](../research/paper-notes/2026-10-14-copd-asthma-biomarkers-learning.md) | Student questions/answers documented; mastery not presumed |
| **2026-10-15** | Imported learning notes into GitHub and separated a treatment-response biomarker idea as an **optional future direction**, not the current research aim. | [Handoff](handoffs/2026-10-15-retrospective-learning-import.md), [future direction](../research/future-directions/treatment-response-biomarker-study.md) | Documentation completed |
| **Between Oct 13 and Oct 26** | Created an original-paper note scaffold and added a two-column source-location ↔ student-understanding workspace and an annotation log. | [Reading notebook](../research/paper-notes/2026-10-13-original-paper-reading.md), [reading-note instructions](../research/paper-notes/README.md) | Recording framework created; **not** proof the paper was read |
| **2026-10-26** | Student reported having read only **part of the Abstract**. Their interpretation correctly approached the asthma/COPD signature question and broad methods, but concepts such as cohort, airway epithelium, and detailed Results needed help. | [Initial interpretation + assistant feedback](../research/paper-notes/2026-10-26-abstract-reading-feedback.md), [article structure guide](../research/literature/christenson-2015-paper-structure.md) | First-pass learning documented; Methods/Results independent reading incomplete |
| **2026-10-26** | Student requested a better method: **assistant explanation → original-source comparison → student explanation → GitHub evidence/commit**. Adopted this without treating AI-produced explanations as student-authored scholarship. | [Decision record](decisions/DECISION-2026-10-26-reading-workflow-and-sat-schedule.md), updated reading instructions | Workflow revised |
| **2026-10-26** | Student confirmed SAT postponed from **Nov 7 to Dec 5, 2026**, with limited computer access. Previous Oct/Nov milestones were behind the actual work. | [Revised roadmap v1.1](PROJECT_ROADMAP.md), [archived v1.0](archive/PROJECT_ROADMAP_v1.0_2026-10-13.md) | SAT-priority schedule adopted; no missed work backfilled |
| **2026-10-26** | Prepared a comprehensive end-of-session handoff and explicit next-step instructions for a new conversation. | [Handoff — paper reading and v1.1 roadmap](handoffs/2026-10-26-paper-reading-sat-adjustment.md) | Documentation/transition only |

| **2026-10-27** | Student questioned the scientific value and originality of a GSE67472 asthma-versus-healthy comparison, how reanalyses differ from plagiarism, and whether simple replication adds value when prior researchers have already validated findings. Agreed on a **staged strategy: guided reproduction → literature-gap assessment → independent question only if feasible**. This is a strategic clarification, **not** a completed experiment or a finalized new research question. | [Decision: reproduction to independent research](decisions/DECISION-2026-10-27-reproduction-to-independent-research.md); initial documentation commit [`cf01c04`](https://github.com/chunspringbom-dot/asthma-gene-expression/commit/cf01c04e537b14d0bf9ef9a245d2b2fe4fe17543) | Decision documented; no GEO2R run, independent validation, or original analysis completed |

| **2026-10-27** | After the research-direction decision, the student requested a clear seven-step, admission-facing research progression in the README and asked whether a major direction change requires a handoff. Added the **long-term scientific roadmap** while retaining the current SAT-adjusted weekly plan; created a session handoff documenting what was decided versus what was actually done. | [README seven-step roadmap](../README.md#seven-step-research-roadmap-long-term-direction), [Oct 27 decision](decisions/DECISION-2026-10-27-reproduction-to-independent-research.md), [Oct 27 handoff](handoffs/2026-10-27-seven-step-research-direction.md); README commit [`b50bed0`](https://github.com/chunspringbom-dot/asthma-gene-expression/commit/b50bed0872ed9704d38f5a985844604f83bf6b8a) | Documentation updated; weekly roadmap v1.1 unchanged; no analysis completed |
| **2026-11-04** | Corrected the roadmap to reflect the scope and progress of the asthma project. | [Correction handoff](handoffs/2026-11-04-asthma-only-roadmap-correction.md) | Documentation updated |
| **2026-11-24** | Adopted the evidence-first workflow, built the initial literature matrix and completed the guided paper-review checkpoint. | [Workflow decision](decisions/DECISION-2026-11-24-ai-assisted-analysis-student-investigation.md), [evidence matrix](../research/literature/2026-11-24-initial-evidence-matrix.md), [review handoff](handoffs/2026-11-24-guided-paper-review-to-student-investigation.md) | Workflow and guided review documented |
| **2026-11-24** | Proposed a Th2-high versus Th2-low comparison and an exploratory link between gene expression and FEV₁. | [Q9 investigation](../research/student-investigations/2026-11-24-q9-th2-low-asthma.md) | Hypotheses recorded. Score definition and patient-level spirometry linkage were pending. |
| **2026-11-25** | Shifted from the asthma–control comparison to asking whether patients with similar asthma control (ACQ) have similar airway type 2 gene expression. Selected GSE89809 as the leading candidate and updated the roadmap to v1.3. | [Decision and rationale](decisions/DECISION-2026-11-25-asthma-control.md), [handoff](handoffs/2026-11-25-asthma-control-and-type-2-expression.md) | Research question selected. Sample audit, score definition and analysis pending. |

## November 4, 2026 — Asthma-only roadmap correction

The student requested an asthma-only revision in the archive, with reasons and a continuation record. The multi-project portfolio HTML added in commit `a5ff65a` was incorrectly scoped and placed. It has been removed from the current tree; Git history retains it.

- [New asthma-only revision snapshot](archive/ASTHMA_ROADMAP_REVISION_2026-11-04.md): current progress, reasons for revision, revised target schedule, and feasibility boundaries.
- [Session handoff](handoffs/2026-11-04-asthma-only-roadmap-correction.md): changed files, remaining work, and next reading section.
- The original v1.0 archive and active v1.1 roadmap are preserved. The new archive entry is a dated planning snapshot, not a relabeling of v1.0.
- Updated status evidence: the [November 3 midpoint report](reports/2026-11-03-classroom-midpoint-progress-report.md) records Abstract discussion and Methods begun. The October status below is historical; sample verification and analysis remain incomplete.
- Completion status: documentation corrected; no new scientific analysis or figures.

## November 24, 2026 — AI-assisted evidence-first workflow (v1.2)

The student reported a lack of time and requested the previously discussed approach: AI explains papers, organizes related published evidence and performs supported data analysis, then the student chooses patterns/questions and investigates further. The latest prior commit was November 4; no new analysis output was identified. The prior reading-first plan and missed milestones are preserved, not retroactively completed.

- [Archived exact v1.1](archive/PROJECT_ROADMAP_v1.1_2026-10-26.md) and [active v1.2](PROJECT_ROADMAP.md).
- [Decision](decisions/DECISION-2026-11-24-ai-assisted-analysis-student-investigation.md), updated [README](../README.md) and [charter](PROJECT_CHARTER.md).
- [November 24 handoff](handoffs/2026-11-24-ai-assisted-research-workflow.md).
- No mandatory work before Dec 5 SAT; post-exam evidence matrix, metadata audit, educational pilot if valid, student-led investigation and conditional follow-up. Distinguish published results, actual AI-assisted computation, and student's own work. **Documentation change only; no analysis or new result produced.**

## November 24, 2026 — Initial literature evidence session

- [Initial evidence matrix](../research/literature/2026-11-24-initial-evidence-matrix.md): assistant-supported review of Christenson 2015 plus Woodruff 2007, Woodruff 2009 and Kuo 2017; selected published quantitative values, comparability and overlap cautions, GEO overview and candidate student questions. Commit `005c265a`.
- [Session handoff](handoffs/2026-11-24-initial-literature-evidence.md): student question selection pending. Full-text supplements, sample audit, processing and original analysis remain incomplete. No independent results claimed.

## November 24, 2026 — Guided paper review checkpoint and cumulative research handoff

- [Guided paper learning checkpoint](../research/paper-notes/2026-11-24-guided-methods-results-discussion.md): assistant-supported Methods, Statistical Analysis, Results and Discussion; student answered Q1–Q8 correctly (8/8), demonstrating guided conceptual recognition, not independent mastery.
- [Cumulative research handoff](handoffs/2026-11-24-guided-paper-review-to-student-investigation.md), commit `55fdc10a615319dd2f2982bac0fdb170345f5ced`: preserves the four-paper evidence matrix, actual student responses, scientific boundaries and exact resume point (unanswered Q9 on Th2-low asthma and data needed to investigate a hypothesis).
- [README](../README.md) was updated to link to the latest handoff and show Q9 as the starting point for the student-led investigation. Commit [`9064247`](https://github.com/chunspringbom-dot/asthma-gene-expression/commit/9064247c5893e40f43650031e1cccf556946f058).
- Student-selected question, full metadata audit, and original analysis remain pending. Earlier planning and literature handoffs are preserved.

## November 24, 2026 — Student-led Q9 hypothesis

- [Q9 investigation note](../research/student-investigations/2026-11-24-q9-th2-low-asthma.md): the student proposed comparing Th2-low and Th2-high asthma to explore whether a type 2 expression pattern observed in COPD is less evident in the low group. Assistant checked representative GEO subgroup labels and clarified what the proposed comparison can test.
- The student then proposed FEV₁ as a candidate clinical outcome and identified a small difference on an additional expression score as a result that could weaken the hypothesis. The student predicted lower FEV₁ at higher values of the additional expression score, based on how the candidate genes were identified. Score definition, patient-level spirometry linkage, full metadata audit, and original analysis remain pending.

## 2026-11-25 · Student selected the within-asthma comparison

The earlier asthma–control and Q9 subgroup questions left several possible outcomes. The student chose to ask how much patients with similar asthma control differ in airway type 2 expression. GSE89809 has individual epithelial records with ACQ. The full patient audit, scoring protocol and original analysis are pending. [Decision and rationale](decisions/DECISION-2026-11-25-asthma-control.md) · [Handoff](handoffs/2026-11-25-asthma-control-and-type-2-expression.md).

## Rules for future changes

1. **Never rewrite this timeline to hide delays or mistakes.** Add a correction or new entry when information changes.
2. **Roadmap change:** keep the previous version in `docs/archive/` and create a dated `docs/decisions/DECISION-...` note when methodology, dataset, comparison, or major timing changes.
3. **Learning vs evidence:** label student-authored interpretations, assistant explanations, original paper claims, and actual analysis outputs separately.
4. **Research output:** results count as completed only if file, method, dataset provenance and relevant settings are committed and verifiable.
5. **Session continuation:** create `docs/handoffs/YYYY-MM-DD-short-topic.md` with the current state, file links, blockers and exact next actions.
6. **GitHub history:** use small, descriptive commits. A Git commit date documents when a note was saved, which can differ from the date of the learning event it summarizes.

## Historical project status (2026-10-27)

- **Done:** repository structure, initial sources/feasibility desk review, paper-reading workspace, partial Abstract learning record, study-orientation guide, SAT-adjusted pacing decision, Oct 27 research-direction decision, README seven-step roadmap, and session handoff.
- **Not done:** full student reading of Methods/Results, sample-group mapping, validated GEO2R execution, literature-gap verification, independent research question selection, figures, final report.
- **Next milestone:** 2026-12-13 post-SAT re-entry review; 2026-12-20 target for metadata/primary contrast, subject to feasibility.

Primary sources: [Original article](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/) · [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472).
