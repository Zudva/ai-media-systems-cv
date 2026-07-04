# Publication Boundary

This repository publishes public proof-of-competence, not private production
systems.

## Included

- CV PDFs.
- Curated proof pagers.
- Sanitized project cards.
- Public-safe method descriptions.
- JSON schemas and synthetic fixtures.
- Links to clean-room demo repositories when they are ready.

## Excluded

- Private source code that contains operational details.
- Real datasets, customer files, prompts, transcripts, generated media, and
  session logs.
- Provider configs, API keys, tokens, certificates, `.env` files, local paths,
  hostnames, bucket names, and deployment runbooks.
- Claims that provenance prevents copying, proves copyright ownership, or
  creates legal authenticity by itself.

## Release Gate For Code Demos

Before a linked demo repository is made public:

1. Start from a fresh public history or a cleaned release branch.
2. Remove datasets, media, logs, credentials, local paths, and private names.
3. Add `.env.example`, synthetic fixtures, and clear limitations.
4. Run secret and path scans on current files and git history.
5. Keep upstream authorship and fork boundaries explicit.
6. Link the demo here only after the gate passes.
