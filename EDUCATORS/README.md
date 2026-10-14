# Educators — INVOKEAI

**Project:** INVOKEAI  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/invoke-ai/InvokeAI  
**Pinned commit:** `6c3277771d5e7885610505ab02900f9567ec3112`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ef0b6884f6280b6f38737554c1587c1b3e4d9b4b0030ec8a4a75b391dd9036a3`  
**Date:** October 2026

## Teaching with INVOKEAI

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `ef0b6884f6280b6f38737554c1587c1b3e4d9b4b0030ec8a4a75b391dd9036a3` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
