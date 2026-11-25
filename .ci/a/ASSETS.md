# Additive A trusted inputs

`scripts/fetch_a_assets.py` verifies the separate additive A archive. The real
archive was generated from accepted native build, expanded audit and A Comparator
receipts. All 20 members passed full extraction and content verification, and
the Linux extension preflight accepted the exact payload.

The lock pins archive SHA-256
`708769593918d887f04cfff0794439ef0356584ce690c699b355b28969b89d64`
and manifest SHA-256
`3c33d4d9c26acbffa4ee7ac4c1859af155054785d1cdbf75aba8adaa6999a4cd`.
The archive is 44,330,972 bytes and is published at the URL in
[the asset lock](asset-lock.json). See the
[local verification summary](local-verification-summary.json) for the
original acceptance record.

Use `--output` with a fresh directory. The default
input is the pinned HTTPS URL; `--archive` accepts a separately supplied local
file while retaining both independent hash requirements. `--preflight-only`
checks configuration and, in local mode, the archive hash; it does not inspect
archive contents.

Full verification requires the exact 20 regular tar members, safe paths, an
independently pinned manifest, every payload hash and size, the 2771-module
source graph, the 366-module A Challenge context, the 2771/71/8 audit inputs,
and native evidence that explicitly makes no Linux or publication claim.
Extraction becomes visible at the requested output only after all checks pass.
The B/C/D runtime archive is pinned separately in
[`../bcd/asset-lock.json`](../bcd/asset-lock.json).
The additive A archive and its evidence retain the historical B/C/D digest
from the original acceptance run. The source runner checks the replacement
B/C/D runtime digest independently.

Synthetic local and mocked HTTPS tests cover successful extraction and reject
missing pins, altered bytes, forged status, unsafe paths, links and extra files.
The real archive also passed the full fetch checks. The synthetic tests themselves
do not execute Lean or Linux CI. Before using the extracted payload with the
source runner, retain `fetch-receipt.json` outside that exact payload directory.
