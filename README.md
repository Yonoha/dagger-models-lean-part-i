# Models for dagger categories I: Lean companion

This is the **AI-assisted** Lean companion to *Models for dagger
(infinity,1)-categories I: Dagger simplicial sets and unitary cores*,
by Keima Akasaka. The English catalogue identifies its prose and summaries
as AI-generated. Independent human correspondence review is pending.

## Start here

- **[English catalogue (PDF)](https://github.com/Yonoha/dagger-models-lean-part-i/releases/download/catalogue-20261125/part1-lean-formalization-companion-en.pdf)**: concise revised catalogue, 40 grouped substantial results.
- **[Fixed paper-facing release: v0.2.0-rc1](https://github.com/Yonoha/dagger-models-lean-part-i/releases/tag/v0.2.0-rc1)**.
- [Main A/B/C/D entry points](lean/MainTheoremsABCD.lean) and [exact statements and scope](MAIN_THEOREMS.md).
- [Catalogue source and build instructions](docs/formalization-companion/README.md), [declaration index](docs/formalization-companion/RESULT_INDEX.md) and [fixed PDF release](https://github.com/Yonoha/dagger-models-lean-part-i/releases/tag/catalogue-20261125).
- [Saved local verification](LINUX_VERIFICATION.md) and [current GitHub CI explanation](CI_STATUS.md).
- [Part II companion](https://github.com/Yonoha/dagger-models-lean-part-ii).

The sources include the dagger Bergner and dagger Joyal models, their
rigidification--nerve comparison, unitary cores, and substantial supporting
category-theoretic and simplicial infrastructure. The catalogue maps its
40 groups, together with separately credited reused foundations, to 91 declarations
in 58 source files. The PDF states their scope; the linked index retains full references.

## Verification

Saved local macOS and ARM64 Linux evidence covers the 2771-module development,
40022 owned declarations, 71 advertised results and eight main roots, with
standard transitive axioms and the recorded comparison/negative-control checks.
The Linux run resumed from a checked partial cache.

The hosted foundation checks have successful runs. The larger hosted A/B/C/D
lane remains incomplete: its last failed run built the full source graph, then
rejected sandbox diagnostic output on stderr; the corrected rerun was cancelled.
This is not a hosted success for the complete main-result pipeline.
[CI_STATUS.md](CI_STATUS.md) gives the run links and the exact failure boundary.
The saved local checks and independent human review are separate claims.

## Build

Install the toolchain in `lean-toolchain`, then run from the repository root:

```sh
lake build +MainTheoremsABCD
```

The first build can be substantial. Mathlib and the verification tools have
fixed revisions. For the retained foundation scope, use `lake build +DaggerModels`
and `lake env lean lean/Audit.lean`. See the verification documents for the
broader audits and Comparator commands.

## Layout

| Location | Contents |
| --- | --- |
| `lean/MainTheoremsABCD.lean` | Main A/B/C/D entry points |
| `lean/DaggerModels/` | Foundation and dagger-category constructions |
| `lean/TopCatModelCategory/` | Compatibility port of reused model-category infrastructure |
| `docs/formalization-companion/` | English catalogue source |
| `verification/` | Saved local validation records |
| `scripts/` and `.ci/` | Build/audit tools, Challenges and trusted controls |

Lean module names and the package name are unchanged by the repository rename.
The [historical progress inventory](docs/history/README-before-20261125.md)
is retained separately.

## Citation and provenance

Use the fixed release or an exact commit for a paper reference.
The repository is now named `dagger-models-lean-part-i`; its existing history,
release tags and assets are retained. Version v0.1.0 is the earlier foundation
milestone; v0.2.0-rc1 is the Part I main-results companion.

See [publication scope](PUBLICATION.md), [citation metadata](CITATION.cff),
[mathematical reuse](EXISTING_FORMALIZATIONS.md) and
[third-party notices](THIRD_PARTY_NOTICES.md). Original companion code and
documentation use Apache-2.0; dependencies retain their own terms and notices.
