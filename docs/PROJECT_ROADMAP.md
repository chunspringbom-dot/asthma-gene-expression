# Project Roadmap — v1.2 (AI-assisted evidence, student-led investigation)

**Revised:** 2026-11-24 | **Status:** Active | **Target:** 2027-02-28, conditional  
**Previous versions:** [v1.0](archive/PROJECT_ROADMAP_v1.0_2026-10-13.md), [v1.1](archive/PROJECT_ROADMAP_v1.1_2026-10-26.md), [November 4 snapshot](archive/ASTHMA_ROADMAP_REVISION_2026-11-04.md).  
**Decision:** [November 24 workflow decision](decisions/DECISION-2026-11-24-ai-assisted-analysis-student-investigation.md).  
**Handoff:** [November 24](handoffs/2026-11-24-ai-assisted-research-workflow.md).

## Actual baseline — not a completion claim

Guided Abstract discussion and asthma-specific Methods begun, as recorded in the [November 3 report](reports/2026-11-03-classroom-midpoint-progress-report.md). November 4 was documentation correction only. No subsequent research output was identified in the repository before this revision. Weeks 4–7 reading/metadata milestones are not established as complete. Full sample mapping, preprocessing audit, verified GEO2R or other analysis, literature matrix, student-led gap assessment, final independent question and original results remain incomplete. Blockers: insufficient student time, difficult paper reading and December 5 SAT. Do not backfill missed work.

**Provisional learning question:** Which genes differ between asthma and healthy airway epithelial samples in GSE67472, and how do selected patterns compare with published findings? The 62 asthma and 43 control subjects described by the source are not yet an audited sample manifest. The dataset is not the paper's COPD or GLUCOLD treatment cohorts.

## Working method and division of responsibility

1. **AI briefing:** explain the paper's purpose, study design, groups, methods, reported results and limitations with exact source links/locations; distinguish reported values from interpretation. Focus on what is needed for the question, not line-by-line reading.
2. **AI evidence matrix:** start with 2–3 relevant papers, extend to about 5–10 where useful. Record citation, dataset, participants/tissue, contrast, method, gene/signature, effect/statistic, limitations and comparability. Do not pool incompatible results or count overlapping cohorts as independent. Missing values stay missing.
3. **Verified educational pilot:** assistant inspects actual GEO metadata, sample labels, processing and data availability; student checks representative records and understands the proposed comparison. Record full eligible sample manifest, group definitions/exclusions, processing, platform/probe mapping and primary comparison before any run. Use GEO2R or reproducible code only if suitable and accessible. Save settings/code, tool versions when available, raw outputs, effect estimates and adjusted p-values where applicable. Show actual tables/plots and explain them; if blocked, show only published evidence and the reason.
4. **Student investigation:** student selects a result/pattern or discrepancy, explains it in own words, asks a focused question, checks original sources and investigates selected genes/pathways, alternative explanations or methodological limitations. Save student's own interpretation, citations and next question separately from AI-generated text. Do not require a full paper reading before this cycle.
5. **Question and follow-up:** together compare literature and pilot, evaluate whether a real gap and feasible data exist; student chooses and justifies the question. Prespecify the follow-up protocol and label pilot-derived hypotheses exploratory. Do not call same-data exploration independent confirmation.
6. **Report:** distinguish published findings, AI-assisted reanalysis and student-led investigation; include provenance, reproducibility, uncertainty and individual contribution. An honest educational reanalysis is acceptable if no defensible novel question emerges.

## Schedule and deliverables

| Period | Objective | Evidence / exit criterion |
|---|---|---|
| Nov 24–Dec 4 | SAT priority; optional short AI paper briefing | No mandatory output; if time permits, one student question |
| Dec 5–6 | SAT and recovery | No research requirement |
| Dec 7–13 | AI explains original paper and 2–3 related papers; start GEO audit | Cited evidence matrix draft; student explains key comparison and chooses one question; unresolved metadata listed |
| Dec 14–20 | Complete group/processing audit and primary comparison | Verified eligible sample manifest, documented processing, justified go/no-go; no run if gate fails |
| Dec 21–Jan 3 | AI-assisted educational pilot and interpretation; extend literature matrix | Actual saved outputs/code/settings if feasible, otherwise explicit blocker; student identifies 1–2 patterns/questions |
| Jan 4–17 | Student investigates selected patterns; compare roughly 5–10 papers | Cited student investigation note; gap assessment and feasible question/protocol or decision to finish educational reanalysis |
| Jan 18–31 | Follow-up analysis if appropriate and feasible | Reproducible results, student interpretation, limitations; exploratory if pilot-derived |
| Feb 1–14 | Verify results and draft English report | Traceable methods/results, literature discussion, contribution statement |
| Feb 15–28 | Portfolio finalization | README, report, evidence files, figures if available, clear limitations; disclose incomplete work |

Capacity: optional up to 60–90 min/week before SAT only if feasible; 3–4 hours/week after Dec 7 if feasible. Reassess Dec 13 and Dec 20. Do not compensate for delay by skipping data checks. Narrow scope or extend the target if needed.

## Evidence and repository rules

- Published claims vs assistant explanation vs student interpretation vs actual computed outputs must be labeled separately.
- Proposed locations (create only when work exists): `research/literature/` for evidence matrix; `research/student-investigations/` for authentic student follow-up; `research/` for metadata/analysis protocol; `scripts/` for executable code; `results/` for saved outputs with provenance; `docs/reports/` for English reports.
- All important claims require source URLs and locations. Store sample IDs, data retrieval date, processing, settings, comparison direction, exclusions and reproducibility information. Respect reuse terms; avoid large raw-data copies.
- Literature values alone are not a new statistical analysis; no pooling of incomparable data, invented values, fabricated student authorship, clinical diagnosis, causal or treatment-response claims. Independent validation requires genuinely independent data and suitable methods.
- Use existing changelog and handoff conventions; update only for meaningful work. This revision is a planning change, not an analysis.

## Resume

Start with a source-linked briefing on [Christenson et al. 2015](https://pmc.ncbi.nlm.nih.gov/articles/PMC4407484/) and [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472), explain published findings and design, prepare the initial comparison matrix, then ask the student which pattern warrants follow-up. Do not require the student to translate the whole paper. Verify metadata before computing any original results.
