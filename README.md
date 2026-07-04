# Vyacheslav Babin - R&D / Backend & Applied ML Engineer

Astana / Remote · [zzudva@gmail.com](mailto:zzudva@gmail.com) ·
[GitHub: Zudva](https://github.com/Zudva)

I build backend, DevOps, applied ML/CV, generative-media, and realtime
interactive systems. My strongest area is turning R&D prototypes into
reproducible, operator-friendly systems: backend/API layers, local and cloud GPU
workflows, media tooling, validation gates, documentation, and handoff.

This repository is my public CV and proof-of-work hub. It links a concise CV to
sanitized project cards, stack diagrams, proof pagers, schemas, and clean-room
demo plans.

## Full CV

| Region | English | Russian |
| --- | --- | --- |
| KZ | [babin-cv-kz-en.pdf](cv/babin-cv-kz-en.pdf) | [babin-cv-kz-ru.pdf](cv/babin-cv-kz-ru.pdf) |
| RF | [babin-cv-rf-en.pdf](cv/babin-cv-rf-en.pdf) | [babin-cv-rf-ru.pdf](cv/babin-cv-rf-ru.pdf) |

Regional PDFs differ by contact block. The public README keeps the contact
surface compact; the PDFs contain the full regional details.

## Profile

Technical lead and R&D software engineer working across backend, infrastructure,
applied ML, computer vision, generative AI, and multimedia systems. I have
delivered interactive installations, exhibition systems, AI-assisted media
workflows, backend services, GPU processing pipelines, local LLM/audio tools,
and Unreal Engine delivery support.

I am especially useful where a prototype needs to become a working system:
clear API contracts, reproducible runs, validation, release gates, deployment
discipline, and documentation that lets other people operate the result.

## Core Skills

| Area | Stack / experience |
| --- | --- |
| Backend and APIs | Python, FastAPI, REST, Pydantic, PostgreSQL, Redis, S3-style storage, integration services |
| DevOps and delivery | Linux/VPS, Docker and Compose, NGINX, CI/CD, GitHub Actions, GitLab CI, release documentation |
| AI / ML integration | PyTorch, local LLMs, RAG, LangChain, FAISS, LLM adapters, GPU inference workflows |
| Computer vision | OpenCV, YOLO-style pipelines, image/video processing, tracking, validation |
| Generative media | ComfyUI, Stable Diffusion, ControlNet, LTX-video workflows, layered image generation |
| Media engineering | FFmpeg, HAP/DXT/BC codecs, video post-processing, color/media validation |
| Realtime systems | Unreal Engine, Unity, digital avatars, OSC/TouchDesigner-style installations |
| Provenance and safety | C2PA-compatible framing, manifest hashes, seal-style watermark status, publication gates |

## Selected Evidence Projects

| Project family | What I did | Public proof |
| --- | --- | --- |
| HAP converter | Built and prepared a native C++20/FFmpeg media conversion stack for realtime playback workflows. | [Project card](docs/projects/hap-converter.md) |
| AI media evidence method | Designed a public-safe provenance method around manifests, hashes, C2PA-compatible metadata, and verification gates. | [Project card](docs/projects/ai-media-evidence-method.md) |
| AI character dataset and training pipeline | Worked on traceable dataset preparation, review states, sealed manifests, and train-gate discipline for character training workflows. | [Project card](docs/projects/ai-character-training.md) |
| AI video post-production pipeline | Built engineering layers around GPU video processing: job APIs, validation, artifact metadata, and post-processing workflows. | [Project card](docs/projects/ai-video-postproduction.md) |
| Layered image workflows | Adapted Qwen-Image-Layered style RGBA layer decomposition for local inference, previews, exports, and reproducible runs. | [Project card](docs/projects/layered-image-workflows.md) |
| Local meeting AI pipeline | Built local-first meeting processing: ASR, diarization, local LLM summaries, review UI, and report generation. | [Project card](docs/projects/local-meeting-ai-pipeline.md) |
| Local voice installation | Integrated microphone input, Whisper-style STT, LLM response logic, TTS playback, OSC control, and operator runtime behavior. | [Project card](docs/projects/local-voice-installation.md) |
| Unreal delivery and DevOps | Supported Unreal Engine delivery through packaging, runtime setup, integration checks, final polish, and handoff. | [Project card](docs/projects/unreal-delivery-devops.md) |
| Geospatial simulation tooling | Worked with OpenStreetMap/Overpass-style data, coordinate transforms, procedural scene data, and Unreal simulation workflows. | [Project card](docs/projects/geospatial-simulation-tooling.md) |

## Proof Pagers

- [Skills one-pager EN](proof/skills-onepager-en.pdf)
- [Skills one-pager RU](proof/skills-onepager-ru.pdf)
- [Skills stack map EN](proof/skills-stackmap-en.pdf)
- [Skills stack map RU](proof/skills-stackmap-ru.pdf)
- [Evidence matrix](proof/evidence-matrix.md)

## Stack Diagrams

The public stack diagrams show technology layers and integration responsibility
without exposing private repositories, production paths, customer data,
credentials, or operational runbooks.

- [Portfolio and project stack diagrams](docs/stack-diagrams.md)
- [Public project index](docs/projects/README.md)
- [Public demo roadmap](docs/public-demo-roadmap.md)

## Publication Boundary

This repository publishes proof-of-competence, not private production systems.
It intentionally excludes private source repositories, real datasets, customer
files, prompts, transcripts, generated media, credentials, provider configs,
deployment hostnames, and internal runbooks.

The material-protection work is described as a verification and provenance
method: tamper-evidence, manifests, hashes, verification gates, and
C2PA-compatible Content Credentials framing. It does not claim to prevent
copying, prove copyright ownership, or make assets legally authentic by itself.

Useful public documents:

- [Publication boundary](docs/publication-boundary.md)
- [Material protection overview](docs/material-protection-overview.md)
- [Material protection manifest schema](schemas/material-protection-manifest.schema.json)
- [Synthetic manifest example](examples/material-protection/cascadeforge-demo-synthetic.json)
