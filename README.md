# Navuryx Emulations

Official website, WebAssembly browser player, and Windows releases for **Navuryx Emulations** — a closed-source multi-system console emulator, mobile OS runner, and virtual machine suite.

- **Website & Web Player**: https://navuryx.github.io/navuryx-emulations/
- **Download Latest Release (Windows x64)**: https://github.com/Navuryx/navuryx-emulations/releases/latest

## Highlights

- **Xbox One / Series X|S**: Live Emulator Mode (x86-64 + SSE2/BMI2, Era memory, XInput & audio) + Native Mode (SEH unwind, Windows DLL redirection, GDK/XDK/D3D12.X shims, persistent XGameSave).
- **PlayStation 4 & PlayStation 5**: Live x86-64/AVX Emulator Core (VideoOut, sceAudioOut PCM audio, FIOS VFS, Remote Play) + Native Mode with in-place x86-64 `fs:` TLS & stack-canary binary relinker.
- **Nintendo Switch**: Live ARM64+NEON core with NCA decryption, RomFS, HID controller input & audout audio.
- **Apple iPhone / iOS**: Live ARM64e XNU kernel bring-up with 16 KB MMU & Apple S5L UART0 serial console.
- **Xbox, Xbox 360 & PlayStation 2**: Live experimental cores + 16 fully playable classic consoles (NES, SNES, GB/GBC, GBA, N64, GameCube, PS1, Sega SMS/Genesis/Game Gear, Atari 2600/7800, TurboGrafx-16, WonderSwan, Intellivision, Virtual Boy).
- **Built-in Multi-OS Virtual Machines**: Custom x86-64 PC engine with ready templates for Arch Linux, Alpine Linux, FreeDOS, Android Phone/Tablet, Windows & custom ISOs.

*Navuryx Emulations is proprietary closed-source software. Only use games, BIOS dumps, keys, firmware, and OS images you legally own.*