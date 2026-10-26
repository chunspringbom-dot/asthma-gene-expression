# Archived original roadmap (v1.0)

> Historical copy retained on 2026-10-26 before revising the plan for a December 5 SAT exam. This is **not** the active schedule; see [the current roadmap](../PROJECT_ROADMAP.md) and [decision record](../decisions/DECISION-2026-10-26-reading-workflow-and-sat-schedule.md). The original planned milestones were not all achieved.

---

# Project Roadmap & Weekly Work Logic

**Project:** Asthma airway gene-expression reanalysis  
**Repository:** https://github.com/chunspringbom-dot/asthma-gene-expression  
**Planning window:** 2026-10-13 to 2027-02-28  
**Version:** 1.0 — provisional; revise only when evidence or feasibility requires it.

## 1. North-star objective

Produce a small, reproducible, scientifically cautious analysis of a public asthma-related gene-expression dataset, with a clear research question, documented sample selection, transparent analysis settings, interpretable results, limitations, and an admissions-ready GitHub narrative. This is a reanalysis, not an independent replication or clinical diagnostic tool.

## 2. Weekly operating logic

1. Orient: read this roadmap, the project charter, session handoff rules, and latest handoff.
2. Question: write the specific question this week's work should answer.
3. Execute: complete one bounded task and record tools, settings, sources, and decisions.
4. Verify: check results against primary sources or official metadata; separate facts from interpretation.
5. Decide: record what is supported, what remains uncertain, and whether the plan should change.
6. Version: commit meaningful work with a descriptive message.
7. Handoff: record completed work, evidence, files/commits, unresolved questions, next actions, and a copyable resume prompt.

A week is complete only when its exit criteria are met, or when a blocker and revised plan are explicitly recorded.

## 3. Week-by-week plan

| Week | Dates | Direction / key question | Work and deliverables | Exit criteria |
|---|---|---|---|---|
| 1 | Oct 13–18 | Establish project and scientific context | Read original paper Methods/Results; inspect GEO record/platform; capture authoritative sources; confirm scope and reproducibility rules. | Cited paper notes; facts separated from assumptions; handoff created. |
| 2 | Oct 19–25 | Verify sample identities | Inspect GEO sample metadata. Build mapping table: accession, title, phenotype/group, evidence, ambiguity, inclusion decision. | Every group assignment has traceable metadata; ambiguous samples are not guessed. |
| 3 | Oct 26–Nov 1 | Lock research question | Compare feasible contrasts, such as asthma vs healthy controls. Define one primary contrast and rationale before exploring attractive results. | Question, hypothesis, inclusion/exclusion rules, and analysis plan documented. |
| 4 | Nov 2–8 | Test data feasibility | Check processed data and comparability; inspect GEO2R sample assignment/settings. Run only after group mapping passes review. | Proceed/revise/change-dataset decision with reasons recorded. |
| 5 | Nov 9–15 | Produce first analysis output | Run the pre-specified contrast; save settings, output tables, date, and tool-generated script/record where available. Do not chase significance by changing the question. | Output saved with provenance; no unrecorded manual edits. |
| 6 | Nov 16–22 | Understand the result table | Learn log fold change, p-value, adjusted p-value, probe/gene annotation, and multiple-testing correction. | Data dictionary/analysis notes; significance criterion stated in advance. |
| 7 | Nov 23–29 | Quality-control findings | Check group sizes, ambiguous samples, annotation, effect direction, and design plausibility. | QC checklist complete; issues resolved or acknowledged. |
| 8 | Nov 30–Dec 6 | Build readable result summary | Create a ranked table using pre-declared criteria and 1–2 plots if appropriate. | Figures have labels, captions, and source/provenance notes. |
| 9 | Dec 7–13 | Interpret biological meaning | Research a small set of candidate genes using authoritative gene databases and primary literature. Separate known biology from this dataset's evidence. | Evidence table: gene, observed direction/statistic, external context, citations. |
| 10 | Dec 14–20 | Stress-test interpretation | Consider cohort composition, airway sampling, platform/probe limits, treatment/subgroup definitions, confounding, and multiple testing. | Limitations and alternative interpretations drafted. |
| 11 | Dec 21–27 | Reproducibility pass | Re-run documented workflow; compare outputs; record tool/software versions and manual steps. | A reader can follow the documented steps without undocumented memory. |
| 12 | Dec 28–Jan 3 | Midpoint review / scope control | Review question, evidence, time budget, and missing deliverables. Drop optional work if needed; update roadmap only with a documented reason. | Written midpoint decision and revised milestones if required. |
| 13 | Jan 4–10 | Draft scientific report | Write Introduction, Question, Dataset/Methods, Results, and Limitations using supported claims only. | Full report draft with citations and figure references. |
| 14 | Jan 11–17 | Improve communication | Refine figures/tables; explain statistics plainly; challenge interpretations as a skeptical reader. | Science-literate reader can follow results without causal overclaiming. |
| 15 | Jan 18–24 | Audit sources and citations | Verify biological claims against primary/authoritative sources; check dataset/paper citations and attribution. | Citation audit complete; unsupported claims removed or qualified. |
| 16 | Jan 25–31 | Polish GitHub portfolio | Organize README, methods, results/data directories, source list, limitations, and reproduction instructions. | Repository navigation clear; filenames and commits tell a coherent project story. |
| 17 | Feb 1–7 | Critical review and revision | Reviewer-style critique of question, grouping, methods, statistics, interpretation, limits, reproducibility; revise. | Review comments answered or unresolved items clearly marked. |
| 18 | Feb 8–14 | Final validation | Check links, provenance, outputs, consistency across report/README, and claims. | QA checklist passes; release candidate documented. |
| 19 | Feb 15–21 | Admissions narrative | Write a truthful summary of motivation, decisions, methods learned, obstacles, evidence, and limitations. | Portfolio summary and concise individual-contribution statement. |
| 20 | Feb 22–28 | Closeout and retrospective | Freeze report/results; summarize learning and limits; create final handoff and next-project lessons. | Final deliverables committed; final handoff and retrospective published. |

## 4. Milestone gates

- Gate A — Dataset/design (by Nov 1): group labels and question are defensible from metadata and original paper.
- Gate B — Feasibility (by Nov 8): data and tool support the planned comparison. If not, revise or choose another dataset rather than forcing it.
- Gate C — Evidence quality (by Dec 20): findings are QC-checked and interpretations supported or explicitly uncertain.
- Gate D — Reproducibility (by Jan 3): workflow and outputs are traceable.
- Gate E — Portfolio quality (by Feb 28): report, repository, limitations, citations, and handoff tell a consistent story.

## 5. Version-control policy for project direction

- This file is the planning baseline. Change it only when scope, dates, milestone criteria, or major decisions change.
- Use docs/decisions/DECISION-YYYY-MM-DD-short-title.md for decisions changing the dataset, comparison, or method.
- Use docs/handoffs/YYYY-MM-DD-short-topic.md for session continuity. A handoff records state; it does not silently change the plan.
- Every meaningful commit should answer: what changed, why, and what evidence supports it.
- Suggested commit prefixes: docs:, research:, data:, analysis:, figures:, report:, qa:.
- At each week's end, add a weekly review/handoff. If a milestone is missed, record the blocker, consequence, and revised date.
- If the plan changes, update the version/date and add a decision note explaining the evidence behind the change.

## 6. Weekly handoff template

Create docs/handoffs/YYYY-MM-DD-week-N.md:

### Metadata
- Week / dates:
- Roadmap version:
- Session date:
- Current branch / latest commit:

### Weekly objective
- Question this week must answer:
- Planned exit criteria:

### Work completed
- Tasks:
- Files/outputs created:
- Commit links:

### Evidence and quality checks
- Primary sources consulted:
- Directly supported findings:
- Inferences or unresolved uncertainties:
- QC checks completed / failed:

### Decisions and plan changes
- Decision:
- Evidence/rationale:
- Roadmap change required? yes/no
- Decision note link, if applicable:

### Current state
- Completed:
- In progress:
- Blocked:
- Next three actions, prioritized:

### Resume prompt
“Continue the asthma gene-expression capstone from this handoff. First read the roadmap, project charter, session handoff rules, and this handoff. Verify current GitHub state before assuming anything is complete. Continue from the next action and do not claim analyses were run unless there is a saved, verifiable output.”

## 7. Immediate actions (Week 1)

1. Read the original paper's Methods and Results and record relevant details with citations.
2. Inspect GSE67472 sample records and create a first-pass sample inventory.
3. Keep the research question provisional until metadata and study design are checked.
4. At session end, commit notes and create a handoff distinguishing verified facts from open questions.

## 8. Source-of-truth links

- GEO series GSE67472: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472
- GEO2R guide: https://www.ncbi.nlm.nih.gov/geo/info/geo2r.html
- Original paper (PubMed): https://pubmed.ncbi.nlm.nih.gov/25611785/
- Original paper (full text): https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/
- Project charter: https://github.com/chunspringbom-dot/asthma-gene-expression/blob/main/docs/PROJECT_CHARTER.md
- Handoff rules: https://github.com/chunspringbom-dot/asthma-gene-expression/blob/main/docs/SESSION_HANDOFF_RULES.md
