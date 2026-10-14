# Students — AUDACITY

**Project:** AUDACITY  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/audacity/audacity  
**Pinned commit:** `8de3891657f6348916a466239b01301d16399747`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `048f3347290ae99099898ae3a8e95096ef6d157abaad5c25fc9200708b85cfa1`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `8de3891657f6348916a466239b01301d16399747`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `048f3347290ae99099898ae3a8e95096ef6d157abaad5c25fc9200708b85cfa1`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
