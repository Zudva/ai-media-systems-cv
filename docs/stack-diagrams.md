# Stack Diagrams

Public-safe stack diagrams for the portfolio project families. These diagrams
show technology layers and integration responsibility without exposing private
repositories, production paths, customer data, credentials, or operational
runbooks.

## Portfolio Evidence Stack

```mermaid
flowchart TB
  CV["CV PDFs"] --> Proof["Proof pagers"]
  Proof --> Cards["Sanitized project cards"]
  Cards --> Stacks["Stack diagrams"]
  Stacks --> Demos["Clean-room demo repositories"]
  Cards --> Boundary["Publication boundary"]
  Boundary --> Gates["Secret / path / overclaim gates"]
  Gates --> Public["Public-safe proof links"]
```

## HAP Converter

```mermaid
flowchart TB
  Use["CLI / batch conversion"] --> Core["C++20 converter core"]
  Build["CMake + portable scripts"] --> Core
  Core --> Decode["FFmpeg/libav decode"]
  Decode --> Frames["RGBA frame buffer"]
  Frames --> Compress["DXT/BC compression"]
  Compress --> Pack["Snappy HAP packing"]
  Pack --> Mux["MOV/HAP muxing"]
  Mux --> Verify["ffprobe + synthetic smoke tests"]
```

## AI Media Evidence Method

```mermaid
flowchart TB
  Boundary["Publication boundary"] --> Schema["JSON Schema contract"]
  Artifact["Media artifact hash"] --> Manifest["Evidence manifest"]
  Schema --> Manifest
  Manifest --> Carrier["C2PA-compatible embed or sidecar"]
  Carrier --> Gate["Verification gate"]
  Lint["Leak / overclaim lint"] --> Gate
  Gate --> Report["Pass / fail report"]
```

## AI Character Dataset And Training Pipeline

```mermaid
flowchart TB
  Sources["Dataset inputs"] --> Ledger["Trace ledger"]
  Ledger --> Analysis["Dedup + pose/style/quality checks"]
  Analysis --> Advisory["VLM advisory review"]
  Advisory --> Human["Human decision gate"]
  Human --> Keepers["Keeper subset"]
  Keepers --> Seal["Sealed manifest"]
  Seal --> TrainGate["Train gate"]
  ReviewUI["Static review UI"] --> Human
```

## AI Video Post-Production Pipeline

```mermaid
flowchart TB
  Operator["Operator / client"] --> API["Python job API"]
  API --> Validate["FFmpeg probe + limits"]
  Validate --> State["Job state + metadata"]
  State --> Worker["GPU worker / model adapter"]
  Runtime["Container + GPU lifecycle"] --> Worker
  Worker --> Post["Codec / color / post-processing"]
  Post --> Output["Output artifact + report"]
```

## Layered Image Workflows

```mermaid
flowchart TB
  UI["Gradio / CLI controls"] --> Pipeline["Layer decomposition pipeline"]
  Runtime["PyTorch + CUDA + bfloat16"] --> Pipeline
  Pipeline --> Layers["RGBA layer outputs"]
  Layers --> Preview["Layer preview"]
  Layers --> Export["PPTX / asset export"]
  Pipeline --> Metadata["Run metadata"]
  Metadata --> Reproduce["Reproduce / compare runs"]
```

## Local Meeting AI Pipeline

```mermaid
flowchart TB
  Audio["Meeting audio"] --> Prep["FFmpeg conversion / splitting"]
  Prep --> ASR["Whisper / faster-whisper ASR"]
  ASR --> Diar["Optional diarization"]
  ASR --> LLM["Local LLM summarization"]
  Diar --> UI["Local review UI"]
  LLM --> UI
  UI --> Reports["JSON / Markdown / HTML reports"]
```

## Local Voice Installation

```mermaid
flowchart TB
  Mic["Microphone + audio routing"] --> Capture["Capture + silence detection"]
  Capture --> STT["Whisper-style STT"]
  STT --> Dialogue["LLM response + session state"]
  Dialogue --> TTS["TTS synthesis"]
  TTS --> Playback["Audio playback"]
  OSC["OSC control/status"] --> Dialogue
  Operator["Operator reset / monitor"] --> OSC
  Dialogue --> Logs["Runtime logs"]
```

## Unreal Delivery And DevOps

```mermaid
flowchart TB
  Project["Existing Unreal project"] --> Integration["Plugin / module integration"]
  Integration --> Build["Build + packaging checks"]
  Build --> Runtime["Runtime configuration"]
  Runtime --> QA["Smoke checks + final polish"]
  QA --> Handoff["Operator handoff"]
  Docs["Delivery notes"] --> Handoff
```

## Geospatial Simulation Tooling

```mermaid
flowchart TB
  OSM["OSM / Overpass data"] --> Parser["Nodes / ways / relations parser"]
  Parser --> Filter["BBox filtering"]
  Filter --> Coords["WGS84 -> local coordinates"]
  Coords --> Features["Road / building / terrain features"]
  Features --> Procedural["Procedural scene data"]
  Procedural --> Runtime["Unreal simulation runtime"]
  Procedural --> Validate["Validation logs"]
```
