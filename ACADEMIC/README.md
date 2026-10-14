# Academic Use — OPENHD

**Project:** OPENHD  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/OpenHD/OpenHD  
**Pinned commit:** `f07729b35e273fe3612e1aade030a7a86350d1ac`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f2f30cc591712570f30fe1838e63a986812df8ff0b7d3486ef5fa5d2aa6801df`  
**Date:** October 2026

## Scope

OPENHD is available for academic research under the Apache 2.0 terms of the
Anticommons 0.1.0 dual licence. Citation details are in `23_HOW_TO_CITE`.

## What is available to researchers

- The full upstream source, pinned at `f07729b35e273fe3612e1aade030a7a86350d1ac`
- The 16-check assurance register with per-check evidence and hashes
- The AIOSS ledger attesting the project artifacts
- Benchmark output in `BENCH.json`

## Reproducing the result

```
python tools/run_bench.py --out BENCH.json
```

Then recompute any row's SHA3-256 from `ISOLATED_LAB_RESULTS/04_Evidence/`.

## Contact

lois@0-1.gg · 0-1.gg
