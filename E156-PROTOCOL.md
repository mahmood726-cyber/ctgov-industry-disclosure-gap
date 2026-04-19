# E156 Protocol — `ctgov-industry-disclosure-gap`

This repository is the source code and dashboard backing an E156 micro-paper on the [E156 Student Board](https://mahmood726-cyber.github.io/e156/students.html).

---

## `[33]` CT.gov Industry Disclosure Gap

**Type:** methods  |  ESTIMAND: 2-year no-results rate among eligible older closed interventional industry studies  
**Data:** 128,464 industry-linked studies from the March 29, 2026 full-registry snapshot

### 156-word body

How large is the industry-specific disclosure gap inside the live ClinicalTrials.gov registry? We analysed the March 29, 2026 full-registry snapshot, focusing on 128,464 industry-linked studies and 87,296 closed interventional industry studies. We derived sponsor-level omission flags for missing results, missing actual dates, missing actual enrollment, missing IPD statements, missing publication links, and missing detailed descriptions, while preserving sponsor-level counts so absolute backlog and rate-based silence could be read together across named firms globally. Among eligible older closed interventional industry studies, 58.1 percent still had no posted results, leaving 44,007 unresolved two-year no-results records in the industry bucket alone. The biggest absolute backlogs sat with GlaxoSmithKline, AstraZeneca, Boehringer Ingelheim, Sanofi, and Pfizer, while several smaller sponsors exceeded 95 percent on the same rate metric. Industry records were also structurally sparse, with 63.2 percent lacking IPD statements, 66.6 percent lacking publication links, and 53.8 percent lacking detailed descriptions. These estimates identify registry-visible non-disclosure rather than adjudicated legal breach.

### Submission metadata

```
Corresponding author: Mahmood Ahmad <mahmood.ahmad2@nhs.net>
ORCID: 0000-0001-9107-3704
Affiliation: Tahir Heart Institute, Rabwah, Pakistan

Links:
  Code:      https://github.com/mahmood726-cyber/ctgov-industry-disclosure-gap
  Protocol:  https://github.com/mahmood726-cyber/ctgov-industry-disclosure-gap/blob/main/E156-PROTOCOL.md
  Dashboard: https://mahmood726-cyber.github.io/ctgov-industry-disclosure-gap/

References (topic pack: individual participant data (IPD) meta-analysis):
  1. Riley RD, Lambert PC, Abo-Zaid G. 2010. Meta-analysis of individual participant data: rationale, conduct, and reporting. BMJ. 340:c221. doi:10.1136/bmj.c221
  2. Burke DL, Ensor J, Riley RD. 2017. Meta-analysis using individual participant data: one-stage and two-stage approaches, and why they may differ. Stat Med. 36(5):855-875. doi:10.1002/sim.7141

Data availability: No patient-level data used. Analysis derived exclusively
  from publicly available aggregate records. All source identifiers are in
  the protocol document linked above.

Ethics: Not required. Study uses only publicly available aggregate data; no
  human participants; no patient-identifiable information; no individual-
  participant data. No institutional review board approval sought or required
  under standard research-ethics guidelines for secondary methodological
  research on published literature.

Funding: None.

Competing interests: MA serves on the editorial board of Synthēsis (the
  target journal); MA had no role in editorial decisions on this
  manuscript, which was handled by an independent editor of the journal.

Author contributions (CRediT):
  [STUDENT REWRITER, first author] — Writing – original draft, Writing –
    review & editing, Validation.
  [SUPERVISING FACULTY, last/senior author] — Supervision, Validation,
    Writing – review & editing.
  Mahmood Ahmad (middle author, NOT first or last) — Conceptualization,
    Methodology, Software, Data curation, Formal analysis, Resources.

AI disclosure: Computational tooling (including AI-assisted coding via
  Claude Code [Anthropic]) was used to develop analysis scripts and assist
  with data extraction. The final manuscript was human-written, reviewed,
  and approved by the author; the submitted text is not AI-generated. All
  quantitative claims were verified against source data; cross-validation
  was performed where applicable. The author retains full responsibility for
  the final content.

Preprint: Not preprinted.

Reporting checklist: PRISMA 2020 (methods-paper variant — reports on review corpus).

Target journal: ◆ Synthēsis (https://www.synthesis-medicine.org/index.php/journal)
  Section: Methods Note — submit the 156-word E156 body verbatim as the main text.
  The journal caps main text at ≤400 words; E156's 156-word, 7-sentence
  contract sits well inside that ceiling. Do NOT pad to 400 — the
  micro-paper length is the point of the format.

Manuscript license: CC-BY-4.0.
Code license: MIT.

SUBMITTED: [ ]
```


---

_Auto-generated from the workbook by `C:/E156/scripts/create_missing_protocols.py`. If something is wrong, edit `rewrite-workbook.txt` and re-run the script — it will overwrite this file via the GitHub API._