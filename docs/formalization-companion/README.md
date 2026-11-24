# Concise English formalization catalogue

This English companion follows the presentation of Part II and the mathematical
notation of Part I. The opening page explicitly identifies the prose and summaries
as AI-generated. Independent human correspondence review remains pending.

The revised PDF retains all 40 grouped mathematical statements, their hypotheses
and theorem numbering. Per-entry implementation histories and long declaration
lists are now in [RESULT_INDEX.md](RESULT_INDEX.md), with clickable source links
fixed to commit `9ee62295a79ef61269259e27216afc0292458931`.
The machine-readable [results.json](results.json) retains statements, declarations,
source locations, source hashes and the original construction/reuse notes.
The 40 groups reference 88 declarations in 56 files; including the separately
credited upstream foundations gives the earlier catalogue's 91 declarations in
58 files. These are grouped results, not independent novelty claims.

[Read the PDF](part1-lean-formalization-companion-en.pdf), or use the
[fixed catalogue release](https://github.com/Yonoha/dagger-models-lean-part-i/releases/tag/catalogue-20261125).
This is a documentation-only publication. The previous PDF remains in the
unchanged v0.2.0-rc1 formalization release; its frozen publication and validation
receipts are not rewritten.

## Build

From this directory, compile with LuaLaTeX (TeX Live 2025):

```sh
LC_ALL=C LANG=C latexmk -lualatex -interaction=nonstopmode -halt-on-error -outdir=../../build/catalogue main.tex
```

Copy `../../build/catalogue/main.pdf` to
`part1-lean-formalization-companion-en.pdf` after checking the rendered pages.
No manuscript paths or Lean build are required. `part1-notation.tex` retains the
notation definitions copied from Part I; the separately maintained manuscript
is unchanged.

The final section distinguishes saved local verification, hosted CI and human
correspondence review. The current hosted status is explained in
[CI_STATUS.md](../../CI_STATUS.md). No long Lean CI was rerun for this revision.
