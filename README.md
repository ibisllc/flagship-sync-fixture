# flagship-sync-fixture

Test input for Flagship's release gym (the `upstream-sync` group). It is a tiny Flagship-ready static app with two
tagged versions, `v1` and `v2`: the gym imports `v1`, deploys it, then syncs to `v2` and checks the three-way merge
proposal. Nothing in the product reads from or depends on this repository; do not rely on it for anything else.

Set `GYM_SYNC_REPO=https://github.com/ibisllc/flagship-sync-fixture` (refs default to `v1` and `v2`).
