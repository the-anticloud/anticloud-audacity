# Academic Use — AUDACITY

**Project:** AUDACITY  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/audacity/audacity  
**Pinned commit:** `8de3891657f6348916a466239b01301d16399747`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `048f3347290ae99099898ae3a8e95096ef6d157abaad5c25fc9200708b85cfa1`  
**Date:** October 2026

## Scope

AUDACITY is available for academic research under the Apache 2.0 terms of the
Anticommons 0.1.0 dual licence. Citation details are in `23_HOW_TO_CITE`.

## What is available to researchers

- The full upstream source, pinned at `8de3891657f6348916a466239b01301d16399747`
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
