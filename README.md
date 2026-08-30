# AI Strategic Autonomy Framework (AI-SAF)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22178006.svg)](https://doi.org/10.5281/zenodo.22178006)

A framework for measuring AI strategic autonomy: **whether an organisation or a state can
keep its critical AI systems running, and keep improving them, if a supplier or a
government withdraws access.**

This repository holds the framework itself — the documents, the scoring rubric and the
Evidence Base — at the version they were published. The self-assessment instrument, the
document reader and the searchable Evidence Base are at
**[ai-strategic-autonomy.org](https://ai-strategic-autonomy.org)**.

Current release: **v0.7.1** (August 2026). CC BY 4.0.

> Not affiliated with any AI Safety Institute.

## What is here

| Path | What it is |
|---|---|
| `documents/` | The five-document package, in DOCX and PDF. The DOCX is the editable source the licence's adaptation grant is meant to make practical. |
| `rubric/` | `AI-SAF-C-rubric-v0.7.1.json` — the corporate instrument as data: 9 pillars, 38 sub-indicators, every anchor, every point value, the axis mapping, the Quick Check and its bands. This is what the site computes from. |
| `evidence/` | The Evidence Base as JSON: 50 entries — 37 dated incidents and instruments from 2024–2026, plus 13 research references and peer indices — each with its sources and the pillar it moves. |
| `CHANGELOG.md` | The package's own version history, from first public release to now. |

The files in `documents/` are byte-identical to the ones served from the site's downloads
page. Each release is tagged, so the files at a tag are the files that revision was
assessed against.

## The shape of the framework

Nine weighted pillars for companies (AI-SAF-C), eight for states (AI-SAF-N) — culture and
operating model applies to companies only. Weights differ on purpose: manufacturing is
worth 1 point to a firm and 12 to a state.

Two design choices carry most of the argument:

- **Same pillar, opposite meaning.** Open weights are sovereignty-positive for a nation
  and a fallback layer rather than a strategy for a company. The two variants share
  pillars and disagree deliberately.
- **Two numbers, not one.** Every sub-indicator is tagged resilience (60 points) or
  autonomy (40 points), and assessments report both subtotals alongside the headline. A
  reading of 45 / 60 resilience with 12 / 40 autonomy and one of 27 / 60 with 30 / 40
  score the same 57 and describe opposite problems.

There is no radar chart. Radar equalises nine spokes weighted from 1 to 16, which
contradicts the framework's own thesis on sight.

## Status: v0.7.1, published unfinished on purpose

Part V of Document 1 — *Areas of genuine uncertainty* — lists what the author is not sure
about, including the parts a methods reviewer is most likely to attack. The two things
standing between this and v1.0:

1. **Published weight-sensitivity analysis.** Monte Carlo runs and PCA cross-checks are
   described in §4.3 as design commitments. They have not been run.
2. **At least two assessments performed by someone other than the author**, landing within
   a band of the author's own reading.

29 of the 38 corporate sub-indicator anchor sets are authored for the instrument and still
await sign-off; the site marks them as provisional rather than settled.

## Review

The second precondition is why this repository takes issues. Three templates cover the
critique that changes a version — a methodology challenge, a missing Evidence Base
incident, an independent assessment — and anything else is welcome as a blank issue.
**[Open an issue](https://github.com/galexandrov11/ai-saf/issues/new/choose)**, or read
[how to review the framework](https://ai-strategic-autonomy.org/review) first.

What makes a critique land: point at something dated and sourced. The Evidence Base is the
referee — every scoring choice is supposed to trace to something that actually happened,
and a disagreement backed by an incident beats one backed by intuition.

Pull requests are welcome as arguments. The rubric changes by author decision, so a PR is
read as a proposal with a diff attached rather than as a merge waiting to happen.

## Citation

```
Alexandrov, G. (2026). AI Strategic Autonomy Framework: Assessment Framework
(Version 0.7.1) [Document package]. https://doi.org/10.5281/zenodo.22178006
```

That is the package's own citation block, verbatim — the same string the documents
carry and the site prints. `CITATION.cff` holds the machine-readable form, and GitHub
renders it as "Cite this repository" in the sidebar.

Cite the version you actually read: the DOI above is minted per release, and the
framework changes between them. Where you mean the framework rather than one release —
a reading list, a talk, a profile — use the concept DOI,
[10.5281/zenodo.22178005](https://doi.org/10.5281/zenodo.22178005), which always resolves
to the newest version.

## Licence

CC BY 4.0 — see [LICENSE](LICENSE). Share and adapt, including commercially, with
attribution and an indication of what you changed. An adaptation is not the AI Strategic
Autonomy Framework: please do not present a modified rubric as this framework's own
scoring.
