# GitHub CI status

Observed on November 25, 2026. The retained local validation record is in
[LINUX_VERIFICATION.md](LINUX_VERIFICATION.md). This page explains hosted runs;
it is not a new verification certificate.

| Workflow | Latest observed result | Relevant completed evidence |
| --- | --- | --- |
| `lean.yml` — retained foundation build/audit | Success | [Run 39477694292](https://github.com/Yonoha/dagger-models-lean-part-i/actions/runs/39477694292) |
| `comparator.yml` — retained foundation Challenges | Cancelled | [Earlier successful run 39453081704](https://github.com/Yonoha/dagger-models-lean-part-i/actions/runs/39453081704) |
| `bcd-comparator.yml` — full current A/B/C/D source lane | Cancelled after a fix | [Last failed run 39453081668](https://github.com/Yonoha/dagger-models-lean-part-i/actions/runs/39453081668), [cancelled rerun 39477694305](https://github.com/Yonoha/dagger-models-lean-part-i/actions/runs/39477694305) |

## Why the main-result run failed

In the failed run at commit `c6b2a797c18f67055e3c915a37b557433f75b309`,
the sequential build reached all 2771 modules and ordinary `lake build` reported
`Build completed successfully (5717 jobs).` The saved universe-zero C comparison
also reported successful official Comparator matching and default-kernel replay.

The pipeline then stopped while accepting the all-owner axiom audit:

```text
RuntimeError: all-owner audit emitted stderr
```

The stderr file contained Landrun sandbox diagnostics, including
`Landlock restrictions applied successfully` and the command it was executing.
The controller requires a completely quiet stderr for a positive owner audit.
Consequently diagnostic logging caused the job to fail, even though the source
build had completed. This failure did not report a mismatch of the actual
advertised theorem statement or a rejected proof. It also does not certify the
remaining gates that the pipeline had not yet completed.

Commit [`a3085ac303a868df3f3501bc01f2886f0528cf31`](https://github.com/Yonoha/dagger-models-lean-part-i/commit/a3085ac303a868df3f3501bc01f2886f0528cf31)
removed the sandbox's debug-log option and added a quiet-stderr preflight.
The subsequent hosted run was cancelled after about eight minutes. A successful
end-to-end hosted rerun has therefore not been observed. No long rerun was
started for the repository-name and README update.

## Expected failures in negative controls

The logs also contain deliberately rejected controls: a weakened/mismatched
statement, a forbidden axiom, and a changed protected definition. Their rejection
is the intended test outcome. Those messages are distinct from the stderr
protocol failure that stopped the main job.

The concise README links here instead of mixing old foundation milestones,
current main-result status and a single ambiguous badge. Historical run statuses
are preserved; no failed or cancelled run is relabelled as a pass.
