# Independent Insurance — AUDACITY

**Project:** AUDACITY  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/audacity/audacity  
**Pinned commit:** `8de3891657f6348916a466239b01301d16399747`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `048f3347290ae99099898ae3a8e95096ef6d157abaad5c25fc9200708b85cfa1`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | AUDACITY with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `048f3347290ae99099898ae3a8e95096ef6d157abaad5c25fc9200708b85cfa1`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
