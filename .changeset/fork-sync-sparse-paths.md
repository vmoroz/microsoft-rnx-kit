---
"@rnx-kit/fork-sync": minor
---

Add `sparsePaths` to vendor multiple upstream directories via sparse-checkout (identity-mapped, so each keeps its repo-relative path under the local path), and support first-time syncs from an empty `commit` as a direct import (no base, no merge). `sparsePaths` is mutually exclusive with `subDir`.
