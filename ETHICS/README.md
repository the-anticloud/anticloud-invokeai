# Ethics — INVOKEAI

**Project:** INVOKEAI  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/invoke-ai/InvokeAI  
**Pinned commit:** `6c3277771d5e7885610505ab02900f9567ec3112`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ef0b6884f6280b6f38737554c1587c1b3e4d9b4b0030ec8a4a75b391dd9036a3`  
**Date:** October 2026

## Position

INVOKEAI is packaged for offline deployment with a verifiable audit trail. The
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
