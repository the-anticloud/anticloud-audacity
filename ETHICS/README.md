# Ethics — AUDACITY

**Project:** AUDACITY  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/audacity/audacity  
**Pinned commit:** `8de3891657f6348916a466239b01301d16399747`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `048f3347290ae99099898ae3a8e95096ef6d157abaad5c25fc9200708b85cfa1`  
**Date:** October 2026

## Position

AUDACITY is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
