# Kentokun updates

Signed reader-rules files for Kentokun — a desktop practice manager for advocates.

When a court website changes its layout, the fix is published here as a small JSON file. Installed copies of
Kentokun download it once a day (and whenever a court page can't be read) and use it **only if its Ed25519
signature verifies** against the public key built into the app. The files contain website-reading rules only:
no program code, no case data, no personal information.

| File | Court |
|---|---|
| `adapters/mphc.json` | High Court of Madhya Pradesh — advocate cause list |
