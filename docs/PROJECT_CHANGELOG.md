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

## Rules for future changes

1. **Never rewrite this timeline to hide delays or mistakes.** Add a correction or new entry when information changes.
2. **Roadmap change:** keep the previous version in `docs/archive/` and create a dated `docs/decisions/DECISION-...` note when methodology, dataset, comparison, or major timing changes.
3. **Learning vs evidence:** label student-authored interpretations, assistant explanations, original paper claims, and actual analysis outputs separately.
4. **Research output:** results count as completed only if file, method, dataset provenance and relevant settings are committed and verifiable.
5. **Session continuation:** create `docs/handoffs/YYYY-MM-DD-short-topic.md` with the current state, file links, blockers and exact next actions.
6. **GitHub history:** use small, descriptive commits. A Git commit date documents when a note was saved, which can differ from the date of the learning event it summarizes.

## Project status at latest update (2026-10-27)

- **Done:** repository structure, initial sources/feasibility desk review, paper-reading workspace, partial Abstract learning record, study-orientation guide, SAT-adjusted pacing decision, Oct 27 research-direction decision, README seven-step roadmap, and session handoff.
- **Not done:** full student reading of Methods/Results, sample-group mapping, validated GEO2R execution, literature-gap verification, independent research question selection, figures, final report.
- **Next milestone:** 2026-12-13 post-SAT re-entry review; 2026-12-20 target for metadata/primary contrast, subject to feasibility.

Primary sources: [Original article](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/) · [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472).
