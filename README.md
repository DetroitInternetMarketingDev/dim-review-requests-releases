# DIM Review Requests – releases

Built plugin packages and the update manifest that client WordPress sites read to offer one-click updates. Source code lives in a private repository. Nothing here contains keys or client data.

- `update.json` – the current version, its download address, and its SHA-256 fingerprint. Sites refuse any download that doesn't match.
- `releases/` – installable zips.
