# Public Project Index

The entries below describe project families and skills without publishing
private production code or NDA-bound details.

| Area | Public status | What it demonstrates |
| --- | --- | --- |
| [HAP converter](hap-converter.md) | Publication candidate | Native multimedia tooling, FFmpeg, HAP, DXT/BC compression, batch media workflows |
| [AI media evidence method](ai-media-evidence-method.md) | Method published here | C2PA-compatible provenance framing, seal-style watermark status, manifests, verification gates |
| [AI character dataset and training pipeline](ai-character-training.md) | Clean-room demo planned | Dataset lineage, train gates, VLM-assisted review, human-in-the-loop curation |
| [AI video post-production pipeline](ai-video-postproduction.md) | Clean-room demo planned | GPU video processing APIs, color/post pipeline, media validation, cloud GPU discipline |
| [Layered image workflows](layered-image-workflows.md) | Public fork plus private adaptations | Qwen-Image-Layered, RGBA layers, Gradio workflows, multi-GPU/local inference setup |
| [Local meeting AI pipeline](local-meeting-ai-pipeline.md) | Clean-room demo planned | Whisper/faster-whisper, diarization, local LLM summaries, reports, privacy-first processing |
| [Local voice installation](local-voice-installation.md) | Clean-room demo planned | Whisper STT, LLM response backends, TTS, OSC/TouchDesigner control, operator runtime |
| [Unreal delivery and DevOps](unreal-delivery-devops.md) | Sanitized case only | Unreal Engine delivery support, packaging, final integration, deployment workflow |
| [Geospatial simulation tooling](geospatial-simulation-tooling.md) | Sanitized case only | OpenStreetMap/Overpass ingestion, coordinate transforms, procedural UE simulation data |

Public code links will be added only after each demo passes its own publication
gate.

See also the central [stack diagrams](../stack-diagrams.md) page.

## Card Format

Each project card uses the same public-safe structure:

- **What existed before** — upstream libraries, public standards, or an
  existing project environment.
- **What I did** — the concrete engineering slice I can claim.
- **How I extended it** — integrations, runtime hardening, validation,
  documentation, or operator workflow added around the baseline.
- **Why it matters** — the skill signal for CV, interviews, and proof pagers.
- **Diagram** — a Mermaid sketch of the public-safe architecture or workflow.
- **Stack diagram** — a Mermaid sketch of the technology layers and integration
  responsibility.

This keeps authorship precise: upstream models and frameworks are credited as
baselines; my work is described as implementation, adaptation, integration,
hardening, validation, and production-readiness work around them.
