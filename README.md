# Asthma Gene Expression Capstone

A student-led bioinformatics research project investigating gene-expression differences in airway epithelial samples from people with asthma and healthy controls, using publicly available data.

> **Project status:** Kickoff / exploratory phase  
> **Working period:** October 2026 – February 2027  
> **Primary data candidate:** NCBI Gene Expression Omnibus (GEO), accession [GSE67472](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472)  
> **Important:** The dataset and final research question are provisional until the first feasibility check is documented.

## Working research question

In a public gene-expression dataset, which genes differ between airway epithelial samples from people with asthma and healthy controls, and are selected inflammation-related gene-expression patterns consistent with the original study?

The question may be narrowed after reviewing the dataset design, available processed data, group labels, and analysis tools.

## Why this project?

Asthma is a complex disease involving airway inflammation. Gene-expression data can help researchers investigate biological patterns associated with disease, while careful reanalysis can teach how scientific claims depend on data selection, statistical methods, and study limitations.

This project is an educational reanalysis of public data. It is not a clinical test, does not diagnose anyone, and will not claim that gene-expression differences prove causation.

## Proposed approach

1. Review the GEO record and the original paper.
2. Confirm sample groups, sample counts, platform, processed data availability, and limitations.
3. Test whether GEO2R or another accessible method can answer the research question reproducibly.
4. Define a small, pre-specified set of analyses before interpreting results.
5. Compare findings with the original study and explain similarities, differences, and limitations.
6. Publish the research question, methods, results, references, and session handoffs in this repository.

## Planned deliverables

- Research proposal and a dated decision log
- Dataset-selection and feasibility notes
- Reproducible analysis steps and data-source links
- Clearly labelled tables and figures
- Final report with discussion and limitations
- Session handoff notes that allow work to continue across ChatGPT sessions

## Repository structure

- `docs/PROJECT_CHARTER.md` — scope, research question, and decision rules
- `docs/SESSION_HANDOFF_RULES.md` — rules for continuing work across sessions
- `docs/handoffs/` — dated handoff notes
- `research/` — research plan, literature notes, and methods
- `results/` — reviewed tables and figures
- `scripts/` — code added when needed

## Research integrity

- Cite the original dataset, papers, software, and external sources.
- Distinguish observations from interpretations and hypotheses.
- Report null, unexpected, or inconsistent findings rather than hiding them.
- Do not infer causation from observational gene-expression differences.
- Do not present exploratory results as independent validation.
- Do not upload personal, sensitive, or restricted data.
- Keep a record of tool settings, comparison groups, date of analysis, and relevant software versions.

## Session continuity

Before continuing work, read the latest handoff in `docs/handoffs/` and the session rules. At the end of every meaningful work session, update the handoff with completed work, evidence, decisions, unresolved questions, changed files, and the next concrete action.

See [Session Handoff Rules](docs/SESSION_HANDOFF_RULES.md).

## Primary source

- NCBI GEO: [GSE67472 — Airway epithelial gene expression in asthma versus healthy controls](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE67472)

## License and data

No project license has been selected yet. Dataset reuse and redistribution terms must be checked before any third-party data are copied into this repository. Prefer citing and linking to source data rather than duplicating it.
