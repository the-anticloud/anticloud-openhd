# Onboarding — OPENHD

**Project:** OPENHD  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/OpenHD/OpenHD  
**Pinned commit:** `f07729b35e273fe3612e1aade030a7a86350d1ac`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f2f30cc591712570f30fe1838e63a986812df8ff0b7d3486ef5fa5d2aa6801df`  
**Date:** October 2026

## First hour

1. Read `README.md` — what the project is and what it measures.
2. Read `ISOLATED_LAB_RESULTS/03_Result_Register.md` — the 16 checks and their
   evidence hashes.
3. Run the suite: `python tools/run_bench.py --out BENCH.json`.
4. Verify a hash: recompute SHA3-256 of a file in `04_Evidence/` and compare.

## First day

- `10_TECHNICAL_HANDOFF` — architecture and interfaces
- `11_TUTORIAL_DEVELOPERS` — build and test
- `18_COMMAND_LINE_INTERFACE` — CLI reference
- `27_DEPENDENCIES` — the offline dependency mirror

## Getting help

lois@0-1.gg · 0-1.gg
