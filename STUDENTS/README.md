# Students — OPENHD

**Project:** OPENHD  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/OpenHD/OpenHD  
**Pinned commit:** `f07729b35e273fe3612e1aade030a7a86350d1ac`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f2f30cc591712570f30fe1838e63a986812df8ff0b7d3486ef5fa5d2aa6801df`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `f07729b35e273fe3612e1aade030a7a86350d1ac`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `f2f30cc591712570f30fe1838e63a986812df8ff0b7d3486ef5fa5d2aa6801df`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
