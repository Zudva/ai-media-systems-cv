# Public Demo Roadmap

This roadmap tracks which proof repositories should be published next. The goal
is not to publish private production code; the goal is to create clean-room
public demos that prove the same engineering skills with synthetic fixtures,
fresh history, and clear limitations.

## Release Order

| Priority | Demo | Purpose | Target proof |
| --- | --- | --- | --- |
| 1 | HAP converter public release | First strong code-proof for native media engineering. | C++20/FFmpeg build, CLI conversion examples, codec matrix, synthetic smoke output. |
| 2 | C2PA/provenance gate demo | Runnable proof for material protection and seal-style provenance framing. | JSON Schema, pass/fail fixtures, hash verification, overclaim/leak gates, CI. |
| 3 | Local meeting AI demo | Local audio/text AI pipeline with synthetic inputs. | ASR-style transcript fixture, diarization-like speaker map, local summary, HTML/Markdown report. |
| 4 | Local voice installation demo | Interactive runtime proof without real voices or private persona data. | Microphone/event simulator, STT/LLM/TTS adapter boundaries, OSC-style state messages, logs. |
| 5 | AI character dataset/train gate demo | Dataset governance proof without private images or checkpoints. | Synthetic dataset, trace ledger, VLM advisory placeholders, human review states, sealed train manifest. |
| 6 | Geospatial simulation demo | Public OSM-style data pipeline proof. | Synthetic OSM/Overpass fixture, coordinate conversion, generated roads/buildings report, validation logs. |

## Gate For Every Public Demo

Before a demo is linked from the public CV hub:

1. Use synthetic fixtures or public-domain sample data only.
2. Start from fresh public history or a reviewed cleaned release branch.
3. Include `.env.example` only; no real credentials, tokens, certificates, host
   names, private paths, logs, or generated private media.
4. Keep upstream authorship explicit and limit claims to adaptation,
   integration, hardening, validation, or original code that is actually in the
   demo.
5. Add a short README with scope, limitations, run commands, and expected
   output.
6. Add a lightweight CI check: schema validation, unit test, build check, or
   smoke command.
7. Run secret, path, and overclaim scans before linking the repo here.

## Demo-Specific Notes

### 1. HAP Converter

Status: private publication candidate. The native CLI/core path has already
passed local build and synthetic encode smoke review. Remaining public gate:
history scan, final README examples, CI/build status, and GUI/Wails status
worded honestly.

### 2. C2PA/Provenance Gate Demo

Status: method and schema are already public in this hub. Next step is a small
verifier and fixtures:

- `pass`
- `hash_mismatch`
- `missing_manifest`
- `unsupported_format`
- `overclaim`
- `leak`

The demo should describe C2PA-compatible framing as tamper-evidence and
metadata verification. It must not claim DRM, copyright proof, or legal
authenticity.

### 3. Local Meeting AI Demo

Status: clean-room demo planned. Use synthetic transcript/audio fixtures, not
real meeting recordings. The proof should focus on the workflow shape:
preprocess -> ASR transcript -> speaker map -> summary -> report.

### 4. Local Voice Installation Demo

Status: clean-room demo planned. Use fake events and short synthetic audio/text
fixtures. The proof should focus on runtime state: idle, listening,
transcribing, thinking, speaking, reset, monitor.

### 5. AI Character Dataset/Train Gate Demo

Status: clean-room demo planned. Use toy images or generated placeholders. The
proof should show role-aware review, keeper subset creation, sealed manifest,
and fail-closed train gate.

### 6. Geospatial Simulation Demo

Status: sanitized case only. Use a tiny synthetic OSM/Overpass JSON fixture and
show parser output, coordinate conversion, feature classification, and
validation logs.

## What This Roadmap Deliberately Avoids

- Publishing private production repositories as-is.
- Publishing datasets, client materials, private prompts, real meetings, voice
  data, generated media, checkpoints, logs, or credentials.
- Overclaiming upstream model authorship.
- Presenting provenance as copy prevention, copyright proof, or legal
  authenticity.
