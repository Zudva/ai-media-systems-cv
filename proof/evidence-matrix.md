# Evidence Matrix

This matrix connects CV skills to public-safe artifacts. It intentionally
separates current public evidence from planned proof items, so readers can see
what is already available and what still needs a clean-room demo.

## Evidence Tiers

| Tier | Meaning |
| --- | --- |
| A | Public code or runnable demo is available. |
| B | Public-safe project card, diagrams, schema, or proof pager is available; code remains private or pending release. |
| C | Sanitized narrative only; useful for CV context but not enough as standalone proof. |
| D | Upstream/fork/partial contribution; claim is limited to adaptation or workflow work. |

## Skill To Evidence Map

| Skill area | Public evidence | Current tier | What it proves | Next proof to add |
| --- | --- | --- | --- | --- |
| Backend/API architecture | [AI video post-production pipeline](../docs/projects/ai-video-postproduction.md), [Stack diagrams](../docs/stack-diagrams.md) | B | Job API thinking, validation, metadata, stateful processing, operator-facing flow. | Mock GPU job API demo with sample manifest, validation errors, and CI. |
| DevOps and release discipline | [Unreal delivery and DevOps](../docs/projects/unreal-delivery-devops.md), [Publication boundary](../docs/publication-boundary.md) | B/C | Build/package checks, delivery gates, handoff discipline, safe-publication process. | Release checklist template plus CI gate for public demo repos. |
| Native media engineering | [HAP converter](../docs/projects/hap-converter.md) | B | C++20, FFmpeg/libav, HAP, DXT/BC compression, native build and smoke validation. | Public HAP repo link after history scan; CLI examples, codec matrix, CI build. |
| Video post-production | [AI video post-production pipeline](../docs/projects/ai-video-postproduction.md) | B | GPU job lifecycle, FFmpeg validation, codec/color pipeline, artifact reporting. | Clean-room mock worker demo with fake media metadata and sample output report. |
| Generative-media workflows | [Layered image workflows](../docs/projects/layered-image-workflows.md), [Qwen-Image-Layered public fork](https://github.com/Zudva/Qwen-Image-Layered) | A/D | Local inference adaptation, RGBA layers, Gradio/CLI workflow, reproducible run metadata. | Small public example with synthetic image, layer preview screenshots, and run metadata. |
| Dataset governance for AI training | [AI character dataset and training pipeline](../docs/projects/ai-character-training.md) | B | Trace ledger, review states, VLM advisory review, human decision gate, sealed train manifests. | Synthetic dataset demo with pass/fail train gate and static review UI. |
| Local LLM and audio pipelines | [Local meeting AI pipeline](../docs/projects/local-meeting-ai-pipeline.md), [Local voice installation](../docs/projects/local-voice-installation.md) | B | Whisper-style ASR, local LLM summaries/responses, TTS, session state, operator runtime. | Synthetic transcript/audio fixtures, local-only demo, and screenshots of review/operator UI. |
| Realtime interactive systems | [Local voice installation](../docs/projects/local-voice-installation.md), [Unreal delivery and DevOps](../docs/projects/unreal-delivery-devops.md) | B/C | OSC-style control, installation runtime, Unreal delivery support, final integration. | Minimal OSC/TouchDesigner-style simulator with fake events and state logs. |
| Geospatial simulation | [Geospatial simulation tooling](../docs/projects/geospatial-simulation-tooling.md) | C | OSM/Overpass parsing, coordinate transforms, procedural scene data, validation logs. | Synthetic OSM fixture demo with WGS84/local conversion and generated feature report. |
| Provenance and material protection | [AI media evidence method](../docs/projects/ai-media-evidence-method.md), [Material protection overview](../docs/material-protection-overview.md), [Manifest schema](../schemas/material-protection-manifest.schema.json), [Synthetic manifest](../examples/material-protection/cascadeforge-demo-synthetic.json) | B | Manifest design, hash verification, seal-style status, C2PA-compatible framing, overclaim boundaries. | Verification-gate demo with pass/fail fixtures and CI. |

## Highest-Impact Gaps

1. **Public code proof:** HAP converter should become the first real public
   code-proof once its final publication gate passes.
2. **Runnable provenance demo:** the material-protection method needs pass/fail
   fixtures and a small verifier to move from method description to runnable
   proof.
3. **Synthetic UI screenshots:** meeting, voice, dataset, and geospatial cards
   need public screenshots or sample reports to become easier to trust quickly.
4. **CI signals:** every future demo should have at least one visible GitHub
   Actions check, even if the demo is synthetic and lightweight.
