# Educators — OPENHD

**Project:** OPENHD  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/OpenHD/OpenHD  
**Pinned commit:** `f07729b35e273fe3612e1aade030a7a86350d1ac`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f2f30cc591712570f30fe1838e63a986812df8ff0b7d3486ef5fa5d2aa6801df`  
**Date:** October 2026

## Teaching with OPENHD

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `f2f30cc591712570f30fe1838e63a986812df8ff0b7d3486ef5fa5d2aa6801df` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
