# Ethics — TELEPOT

**Project:** TELEPOT  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/nickoala/telepot  
**Pinned commit:** `4bfe4eeb5e48b40e72976ee085a1b0a941ef3cf2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `4c4b81bde684d9c6e0e524e05077fa2e2675195bad033588d845115b37d694bd`  
**Date:** October 2026

## Position

TELEPOT is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
