# Medium Digital Archive (Secondary Account)

Permanent, SHA-256 verified digital archive of published Medium articles, responses, original HTML exports, clean plain-text transcripts, and embedded images.

- **Published Articles:** 4
- **Published Responses:** 0
- **Archived Media Files:** 7
- **Privacy Filter:** Unpublished drafts and private account data excluded (0 drafts skipped)

## Contents
- `articles-html/` — Original Medium HTML export files for all 4 published articles.
- `medium-articles-readable.txt` — Clean, chronological plain-text compilation of all articles.
- `media/` — All 7 embedded images renamed with SHA-256 digests.
- `MANIFEST.sha256` — Cryptographic SHA-256 checksums for every file in the archive.

## Verification
```bash
shasum -a 256 -c MANIFEST.sha256
```
