# Students — INVOKEAI

**Project:** INVOKEAI  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/invoke-ai/InvokeAI  
**Pinned commit:** `6c3277771d5e7885610505ab02900f9567ec3112`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ef0b6884f6280b6f38737554c1587c1b3e4d9b4b0030ec8a4a75b391dd9036a3`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `6c3277771d5e7885610505ab02900f9567ec3112`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `ef0b6884f6280b6f38737554c1587c1b3e4d9b4b0030ec8a4a75b391dd9036a3`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
