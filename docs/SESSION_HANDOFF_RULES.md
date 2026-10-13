# Session Handoff Rules

These rules keep the project coherent when work continues in a new ChatGPT conversation or after a long break.

## 1. When a handoff is required

Create or update a handoff whenever a meaningful work block ends, especially after:

- making or changing the research question or scope;
- selecting, rejecting, or validating a dataset;
- completing a literature review or analysis;
- making a methodological decision;
- creating or changing files, code, figures, or results;
- discovering a blocker or a result that changes the plan;
- ending a work session that is likely to continue in another conversation.

Do not create a separate handoff for every tiny question. Group related work into one session handoff.

## 2. Required handoff location and naming

Save dated handoffs in `docs/handoffs/` using:

`YYYY-MM-DD-short-topic.md`

Example: `docs/handoffs/2026-10-13-kickoff.md`

Never silently overwrite an older handoff. Add a new dated handoff for a new session; edit an existing handoff only to correct an obvious error, and record the correction.

## 3. Required handoff sections

Every handoff must include:

1. **Session metadata** — date, session goal, status.
2. **Current project state** — current research question and phase.
3. **Work completed** — concrete actions and outputs, not vague summaries.
4. **Evidence and sources** — links, accession numbers, papers, and what each source supports.
5. **Decisions made** — decision, reason, and whether it is provisional or final.
6. **Files and Git state** — files created/changed, commit SHA or link when available; never claim a change was pushed unless verified.
7. **Open questions / blockers** — what remains uncertain and why it matters.
8. **Next actions** — ordered, specific tasks that can be started without guessing.
9. **Resume prompt** — a short copyable prompt for a new ChatGPT session.

## 4. Rules for evidence and uncertainty

- Label information as **verified**, **provisional**, **hypothesis**, or **not yet checked** when status could be confused.
- Prefer primary sources for dataset facts and methods.
- Record the source URL and access date for important external facts.
- Separate source-supported facts from our interpretation.
- Never invent results, citations, sample counts, or analysis steps.
- If two sources disagree, document the discrepancy instead of silently choosing one.
- A dataset being publicly available does not automatically mean every file may be redistributed.

## 5. Rules for scope and analysis

- Keep the project feasible for October 2026–February 2027 and the student's current level (little Python; basic descriptive statistics).
- Prefer a small, well-documented analysis over a broad, shallow one.
- Do not start interpreting gene-level results until group labels, data format, and comparison design have been checked.
- Distinguish gene-expression association from causation.
- Distinguish reanalysis of an existing study from independent replication or validation.
- Pre-specify the primary comparison and a limited set of candidate genes before reviewing all results where practical.
- Record exclusions, tool settings, analysis dates, and any deviations from the plan.
- Do not make clinical recommendations or diagnostic claims.

## 6. GitHub workflow

- Keep one repository for this project: `chunspringbom-dot/asthma-gene-expression`.
- Use clear, small commits with messages such as `docs: add research question`, `research: document dataset feasibility`, or `analysis: add gene-expression plot`.
- Do not commit secrets, access tokens, personal information, or large raw datasets.
- Before editing an existing file through the GitHub API, fetch its current content and SHA.
- After each write, verify the returned commit and, when practical, fetch the file again.
- Keep README concise and audience-facing; put detailed process notes under `docs/` or `research/`.
- Never describe planned work as completed work.

## 7. Starting a new session

At the start of each new session:

1. Open the repository README.
2. Read this file.
3. Read the latest dated handoff in `docs/handoffs/`.
4. Check the current repository state and relevant files before assuming the handoff is still current.
5. Briefly state the current phase, the next action, and any important uncertainty.
6. Continue from the next action unless new evidence requires revising the plan; document any change.

If the latest handoff is missing or ambiguous, ask one focused question rather than guessing.

## 8. Ending a session

Before ending a meaningful session:

1. Summarize what was actually completed.
2. Record evidence and decisions in the handoff.
3. List changed files and verify commit status.
4. Update the project log if a milestone or decision changed.
5. Give the user the repository link and the exact next step.

## 9. Handoff quality checklist

- [ ] A new session can understand the project without relying on chat history.
- [ ] Current question and project phase are stated.
- [ ] Decisions are marked provisional or final.
- [ ] Evidence is linked and the claims it supports are clear.
- [ ] Results are not overstated.
- [ ] Changed files and commit status are accurate.
- [ ] Next actions are concrete and ordered.
- [ ] A copyable resume prompt is included.
