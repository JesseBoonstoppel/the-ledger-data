# The Ledger: data feed

Generated JSON for The Ledger app. **Don't edit by hand.** It is overwritten by a scheduled build.

- `v1.json`: served at https://jesseboonstoppel.github.io/the-ledger-data/v1.json
- `CONGRESS`: members of Congress from [unitedstates/congress-legislators](https://github.com/unitedstates/congress-legislators) (public domain), refreshed daily.
- Other keys: hand-checked corrections. Election counts are unofficial.

Format: `{ schema, generatedAt, asOf, sources, data }`.
