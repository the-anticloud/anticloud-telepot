# Students — TELEPOT

**Project:** TELEPOT  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/nickoala/telepot  
**Pinned commit:** `4bfe4eeb5e48b40e72976ee085a1b0a941ef3cf2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `4c4b81bde684d9c6e0e524e05077fa2e2675195bad033588d845115b37d694bd`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `4bfe4eeb5e48b40e72976ee085a1b0a941ef3cf2`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `4c4b81bde684d9c6e0e524e05077fa2e2675195bad033588d845115b37d694bd`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
