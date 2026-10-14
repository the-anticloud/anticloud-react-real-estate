# Educators — REACT_REAL_ESTATE

**Project:** REACT_REAL_ESTATE  
**Category:** REAL_ESTATE  
**Upstream:** see BENCH.json  
**Pinned commit:** `146f804de9b7fc09eb3ead9da71826e979794978`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `6b1acd3ad03e1c1b9cabaecc60d0aea0e69686e82563c2353495dbb6ce040e2e`  
**Date:** October 2026

## Teaching with REACT_REAL_ESTATE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `6b1acd3ad03e1c1b9cabaecc60d0aea0e69686e82563c2353495dbb6ce040e2e` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
