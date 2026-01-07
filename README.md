# BepInBridge

**A cross-platform mod loader for Enter the Gungeon**

---

## Overview

**BepInBridge** is a community-driven project designed to enable **cross-platform modding** of Enter the Gungeon. It acts as a bridge for existing **BepInEx mods**, allowing them to run on **macOS, Linux, and Windows** without requiring a full Windows installation or relying on DLL injection.  

Our goal is to make modding **accessible, lightweight, and stable**, especially for players who cannot run r2modman or Windows VMs.

---

## Why BepInBridge

Currently:

- r2modman only works on Windows
- Wine/Whisky can run Enter the Gungeon but fails with injected mods
- Minimal Windows VMs (UTM) are extremely slow on Apple Silicon
- Modding is inaccessible to macOS and Linux users

**BepInBridge solves these problems** by providing a **cross-platform loader** that supports existing mods with minimal changes.

---

## Features (Planned)

**Phase 1 – MVP**
- Load **asset-based mods** (textures, audio, config)
- Support macOS and Linux through Wine/Whisky
- Simple launcher to start Enter the Gungeon with mods

**Phase 2 – Advanced**
- Support **runtime code mods** using a BepInEx API bridge
- Compatibility layer to translate Windows-specific API calls
- Expandable plugin system for future mods

**Future Goals**
- Community-driven contributions for new mod compatibility
- Lightweight installation (<15 GiB)
- Cross-platform documentation and mod tutorials

---

## Getting Started (Contributor Guide)

**Note:** BepInBridge is currently in planning and early prototype stages. We are looking for developers, testers, and modders to contribute.

### How to Help

1. Fork this repository
2. Check the `docs/` and `tests/` folders for current examples
3. Test existing asset mods in your environment
4. Submit pull requests or issues for:
   - Bug reports
   - Feature requests
   - Proof-of-concept code

### Skills Needed

- **C# / .NET** (main language for loader development)
- **BepInEx knowledge**
- **Cross-platform development** (macOS, Linux)
- **Wine / Whisky familiarity** (optional but helpful)
- Testing and QA for mods

---

## Roadmap

| Phase | Goal |
|-------|------|
| Phase 1 | MVP: Load simple asset mods on macOS/Linux |
| Phase 2 | Bridge BepInEx API calls for code mods |
| Phase 3 | Expand cross-platform plugin system |
| Phase 4 | Documentation, community tutorials, and wider adoption |

---

## Contact / Community

- Join our Discord (TBD)
- Discuss on Reddit: r/EnterTheGungeon
- Follow project updates on GitHub

---

## License

BepInBridge is open-source under the **MIT License**. Contributions are welcome from all community members.

---

**Let’s make modding Enter the Gungeon accessible for everyone, everywhere!**
