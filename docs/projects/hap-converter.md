# HAP Converter

## Summary

Native multimedia tooling for realtime playback workflows: video decoding,
RGBA frame conversion, DXT/BC compression, Snappy packing, and MOV/HAP muxing.

## Public-Safe Contribution

- Developed and adapted a C++20 media pipeline around FFmpeg/libav.
- Implemented HAP-oriented frame processing and container writing.
- Added CLI-oriented build flow and batch-conversion ergonomics.
- Prepared release hygiene for generated artifacts, local paths, and build
  configuration.

## Skills

C++20, FFmpeg, libavcodec, libavformat, libswscale, HAP video, DXT/BC
compression, Snappy, CMake, native CLI tooling, media validation.

## Publication Status

The native CLI/core path has passed a local build and synthetic encode smoke
check in release review. Public visibility is still gated on full git-history
secret scanning and GUI/Wails validation.
