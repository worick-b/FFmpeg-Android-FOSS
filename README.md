# FFmpeg & FFprobe 8.1 FOSS for Android
~Should I Stay or Should I Go

## Features

- **100% FOSS, Offline & Ready-to-Package:**
  * Compiled under **GPL** (`--enable-gpl`) with no proprietary blobs or network protocols (`--disable-network`)
  * Static binaries packaged as `libffmpeg.so` and `libffprobe.so` (`arm64-v8a` and `armeabi-v7a`, API 28+)
- **Audio:**
  * Native FFmpeg **AAC** encoder (`aac`)
  * `libopus` (Opus)
  * `libmp3lame` (MP3)
- **Video:**
  * `libx264` (H.264 / AVC — with assembly/NEON enabled for `arm64-v8a`)
  * `MediaCodec` (Hardware-accelerated `h264_mediacodec` and `hevc_mediacodec`)
  * `libvpx` (VP8 and VP9 / WebM)
- **Native Filters and Formats:**
  * Native decoding for H.265 (HEVC), AV1, AVIF, WebP, MKV, MP4, AVI, OGV, FLAC, WAV, OGG, and WMA
  * Native video and audio filters (`scale`, `aresample`, `crop`, `fps`, etc.)
- **It's:** `A personal project, don't expect a dev master blaster (12" Version)`.
