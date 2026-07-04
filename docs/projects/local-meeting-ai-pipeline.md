# Local Meeting AI Pipeline

## Summary

Local-first AI workflow for meeting audio: transcription, optional diarization,
summarization, and report generation.

## Public-Safe Contribution

- Built local processing flows around faster-whisper/Whisper-style ASR.
- Integrated speaker diarization and fallback paths.
- Used local LLM summarization for structured notes and reports.
- Added a review UI concept for transcript, speaker naming, timeline, summary,
  and client-facing report outputs.
- Kept real audio, transcripts, participant names, customer data, and local
  operational config out of public scope.

## Skills

Speech-to-text, faster-whisper, speaker diarization, local LLMs, report
generation, Python, React/TypeScript UI, privacy-first processing, JSON,
Markdown, HTML reports.

## Public Demo Plan

A clean-room demo should use synthetic audio or generated transcript fixtures,
with no real client meetings or participant data.
