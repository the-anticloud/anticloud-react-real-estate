# Ethics — REACT_REAL_ESTATE

**Project:** REACT_REAL_ESTATE  
**Category:** REAL_ESTATE  
**Upstream:** see BENCH.json  
**Pinned commit:** `146f804de9b7fc09eb3ead9da71826e979794978`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `6b1acd3ad03e1c1b9cabaecc60d0aea0e69686e82563c2353495dbb6ce040e2e`  
**Date:** October 2026

## Position

REACT_REAL_ESTATE is packaged for offline deployment with a verifiable audit trail. The
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
