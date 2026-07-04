# Material Protection Overview

The material-protection work is presented publicly as a conservative
provenance and verification method.

## Public Framing

The method combines:

- content hashes for protected artifacts;
- manifest hashes for metadata integrity;
- optional C2PA-compatible embedding or signed sidecar fallback;
- seal-style watermark status fields;
- verification gates that fail closed on missing or mismatched evidence;
- public limitations that avoid overclaiming.

## What The Public Demo Should Prove

A clean-room demo can safely show:

- creating a synthetic artifact;
- computing a SHA-256 hash;
- producing a JSON manifest;
- validating the manifest against a schema;
- attaching or pairing the manifest with the artifact;
- verifying pass and fail cases in CI.

## What It Must Not Claim

The method should not claim that it:

- prevents copying;
- proves copyright ownership;
- makes an asset legally authentic by itself;
- replaces contractual, platform, legal, or trust-anchor review.

The correct public language is tamper-evidence, traceability, provenance,
verification gates, and Content Credentials style metadata.
