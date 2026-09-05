# Bitcoin Timestamp - Mizuhara Kuopio v1.8 CORRECTED

Genesis SHA256: a319ac60e99c148bec865bec710c0924bc822ef1085eb9b605e2c10c8659dcc3
Location: Mualiman Napa 62.8915N 27.6780E Kuopio

## Status
These .ots files contain calendar attestations initially.
After a few hours, calendar anchors to Bitcoin.
Then `ots upgrade` replaces calendar attestation with Bitcoin attestation.

Verify:
  ots verify STAMP/laws.txt.ots
  # If pending:
  ots upgrade STAMP/laws.txt.ots
  ots verify STAMP/laws.txt.ots
  # Read the verified block height from ots verify output.

Do NOT hardcode block height manually. It must be produced by ots verify.

## What is proven
- laws.txt SHA256 is verifiable: sha256sum laws.txt
- BEST_FAMILIES.md is analogy collection, NOT proof that laws work 1000y
  Only Ise Jingu part is verified. Others marked [VERIFIED]/[DISPUTED]/[UNSOURCED]

## If GitHub dies
Keep STAMP/*.ots + original files. Re-run ots verify to inspect the current proof.

## If Bitcoin dies
Metal plate at 62.8915N 27.6780E + paper copies.

[ ] Leave 10% empty - that is Mualiman Napa.
