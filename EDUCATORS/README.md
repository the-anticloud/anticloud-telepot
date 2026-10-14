# Educators — TELEPOT

**Project:** TELEPOT  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/nickoala/telepot  
**Pinned commit:** `4bfe4eeb5e48b40e72976ee085a1b0a941ef3cf2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `4c4b81bde684d9c6e0e524e05077fa2e2675195bad033588d845115b37d694bd`  
**Date:** October 2026

## Teaching with TELEPOT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `4c4b81bde684d9c6e0e524e05077fa2e2675195bad033588d845115b37d694bd` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
