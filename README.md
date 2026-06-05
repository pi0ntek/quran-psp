# quran-psp

A homebrew Quran reader for the Sony PSP, built in C/C++ using the PSPSDK (pspdev).

## Goal
A lightweight, offline Quran reading app for the PSP — displaying Arabic text, navigating Surahs and Ayahs, with english translation.

## Status
🚧 Early development — Phase 1: Toolchain & Hello World

## Tech Stack
- Language: C/C++
- SDK: [pspdev](https://pspdev.github.io/)
- Emulator for testing: [PPSSPP](https://www.ppsspp.org/)
- Dev machine: macOS (Apple Silicon)

## Phases
1. **Toolchain & Hello World** — pspdev setup, EBOOT.PBP on PPSSPP, basic GPU draw
2. **Quran Data** — parsing and navigating Surah/Ayah structure with english translation
3. **Text Rendering** — Arabic font via custom bitmap or FreeType port
4. **UI & Navigation** — PSP button input, reading interface

## Building
_Instructions coming once toolchain setup is complete._

## License
MIT