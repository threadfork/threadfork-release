# threadfork

## architecture
Tauri desktop app: React/TypeScript frontend + Rust backend. Key modules: `src/App.tsx` (main UI), `src-tauri/src/audio/` (mic capture, system audio, VAD), `src-tauri/src/asr/whisper.rs` (speech recognition with Metal acceleration), `src-tauri/src/plugins/` (custom Tauri plugins). Uses CPAL for audio, Whisper.cpp for transcription, Metal shaders for GPU processing.


