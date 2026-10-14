# Educators — AUDACITY

**Project:** AUDACITY  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/audacity/audacity  
**Pinned commit:** `8de3891657f6348916a466239b01301d16399747`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `048f3347290ae99099898ae3a8e95096ef6d157abaad5c25fc9200708b85cfa1`  
**Date:** October 2026

## Teaching with AUDACITY

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `048f3347290ae99099898ae3a8e95096ef6d157abaad5c25fc9200708b85cfa1` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
