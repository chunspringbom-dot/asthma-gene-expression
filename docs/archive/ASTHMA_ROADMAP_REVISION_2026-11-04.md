# Asthma Project Roadmap — November 4, 2026 Revision Snapshot

**Scope:** Asthma Gene Expression Capstone only.
**Document status:** Dated planning snapshot saved in `docs/archive/` at the student's request. This is not the original v1.0 roadmap and does not overwrite it.
**Execution baseline:** [Project roadmap v1.1](../PROJECT_ROADMAP.md). The revised targets below are recorded for the next planning update; this archive entry does not silently replace the active schedule.
**Progress evidence:** [November 3 midpoint report](../reports/2026-11-03-classroom-midpoint-progress-report.md).

## Why this revision was made

The November 4 document was incorrectly expanded into a multi-project portfolio and committed under `docs/portfolio/` (commit `a5ff65a`). The student requested an asthma-only document in the archive with an explanation and a continuation record. This snapshot replaces that misplaced document in the current repository tree; Git history preserves the correction.

The older roadmap describes partial Abstract reading as of October 26. The November 3 report documents subsequent Abstract discussion and the beginning of asthma-specific Methods. The revised plan starts from that actual position. It also connects the agreed seven-step scientific direction to realistic dates: educational reproduction first, literature comparison and a feasible question next, then any main analysis. Independent validation and novelty remain conditional.

## Current state

- Completed documentation: repository structure, reading notes, decisions, earlier handoffs, and the classroom midpoint report.
- Learning: Abstract discussed and understood with support; asthma-specific Methods begun.
- Incomplete: full Methods understanding, all 105 sample labels, preprocessing audit, verified GEO2R execution, original result tables/figures, literature-gap assessment, and a final independent question.
- Candidate: GSE67472. Its asthma/control samples are distinct from the paper's COPD cohorts and treatment study.
- No new scientific analysis was performed in this documentation session.

## Working question and progression

Provisional learning question: Which genes differ between asthma and healthy-control airway epithelial samples in GSE67472, and how do selected inflammation-related patterns compare with the original study?

1. Understand the relevant paper methods and rationale.
2. Audit sample metadata and learn a suitable analysis workflow.
3. Conduct a documented educational reproduction only after the audit passes.
4. Compare approximately 5–10 related papers and assess a supportable gap.
5. Finalize a feasible question and analysis protocol.
6. Analyze public data with reproducible settings and appropriate checks.
7. Write an English report distinguishing published findings, reproduced results, and any original extension.

A bounded educational reanalysis is an acceptable final outcome. A question motivated by pilot results must be labeled exploratory; it is not independent confirmation.

## Revised target schedule

| Period | Task | Completion evidence |
|---|---|---|
| Nov 4–15 | Continue asthma-specific Methods and resolve rationale gaps | Source-linked explanation of participants, tissue, measurement, and groups |
| Nov 16–29 | Inspect GEO overview and 5–10 sample records when feasible | Exact sample IDs and a list of unresolved labels/processing questions |
| Nov 30–Dec 6 | SAT priority; exam December 5 | No compulsory research output |
| Dec 7–20 | Complete sample and preprocessing audit | Sample manifest, data dictionary, justified comparison, and go/no-go decision |
| Dec 21–Jan 3 | Test one educational comparison; begin literature matrix | Recorded settings and reproducible pilot output, or documented blocker |
| Jan 4–17 | Compare related papers; decide the final scope | Literature matrix, gap assessment, and analysis protocol |
| Jan 18–31 | Execute the agreed analysis and check outputs | Traceable tables/figures with captions, group sizes, and methods |
| Feb 1–14 | Review reproducibility and draft the report | Methods and results tied to saved outputs; limitations explained |
| Feb 15–28 | Finish report, README, overview, and presentation | Consistent evidence package, or clearly labeled incomplete progress report |

Capacity remains 60–90 minutes/week through December 4 and a target of 3–4 hours/week from December 7 if feasible. February 28 is a target, not a guaranteed completion date. Delay analysis if sample labels or processing remain unclear. If no feasible gap emerges, complete the educational reanalysis without claiming discovery.

## Differences from the active v1.1 schedule

- Update the learning baseline using the November 3 report.
- Label the first analysis as educational reproduction/pilot.
- Explicitly reserve early January for the literature matrix and scope decision before a later main analysis.
- Preserve the SAT constraint and data-verification requirement.
- Keep this repository focused on the asthma project.

## Resume point

Continue Christenson et al. (2015), **Methods → Subjects and Sample Preparation → Asthma dataset—asthma and control subjects**. Explain the participants, tissue, measurements, and group definitions in the student's own words, then list the metadata questions that must be resolved.

See the [November 4 handoff](../handoffs/2026-11-04-asthma-only-roadmap-correction.md) and [change log](../PROJECT_CHANGELOG.md).
