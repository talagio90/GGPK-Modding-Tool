
# ⚡ Path of Exile Modding Tool - POE Smoother

A community-built WPF tool for modding **Path of Exile 1 & 2** — optimize your visuals, clean up effects, and get a smoother gameplay experience without touching a single config file manually.

> Built for the community, by someone who plays too much PoE.

---
📸 Screenshots

![Main Window](https://raw.githubusercontent.com/talagio90/GGPK-Modding-Tool/main/screenshots/Main%20window%20.png)

*Main patch selection screen*

![GGPK Browser](https://raw.githubusercontent.com/talagio90/GGPK-Modding-Tool/main/screenshots/VisualGGPK.png)

*Built-in GGPK file browser with DDS preview*

![MTX Editor](https://raw.githubusercontent.com/talagio90/GGPK-Modding-Tool/main/screenshots/PetReplace.png)

*MTX replacer — swap pet, portal, and skill visuals*

![Color Mods](https://raw.githubusercontent.com/talagio90/GGPK-Modding-Tool/main/screenshots/Mod%20Color.png)

*Map mod colorizer — highlight dangerous or loot mods at a glance*

## ✨ What It Does

Path of Exile Modding Tool lets you apply, manage, and recover game patches directly to your `Content.ggpk` (Standalone) or `_.index.bin` (Steam) file — with a clean UI and zero terminal knowledge required.

### 🎨 Visual & Performance Patches
- Remove or reduce particle effects, MTX visuals, environmental fog, shadows, and more
- Zero Particles, Delirium effects, Clean Terrain, Remove MTX
- Support for both POE1 and POE2 patch sets

### 🗺️ UI Patches
- Custom minimap colors & settings
- Camera zoom control (1.2× – 4.0×)
- Hide loading screens, show monster life bars, corpse visibility toggle

### 🐾 Beast & Special Encounter Highlights
- Highlight expensive beasts (Black Morrigan, Craicic Chimeral, Hellion Alpha, and more)
- Special encounter markers (Nameless Seer, Reflecting Mist, Zana Memories, etc.)

### 🎭 MTX Replacer
- Replace Pet, Portal, and Skill MTX visuals with custom assets
- Flexible file-by-file or full folder replacement

### 🗂️ GGPK Editor
- Browse, preview, export, and replace files inside your GGPK directly
- DDS image preview, text file editor, recursive export/replace
- Search with highlight and debounce

### 🔁 Smart Recovery
- **Standalone:** Hash-based recovery — only re-downloads changed files (~20 seconds)
- **Steam:** Bundle-level recovery (~300 bundles instead of 3.4M files — much faster)
- Automatic detection of corrupted bundles via `UncompressedSize` comparison

### 💾 Profile System
- Separate profiles for POE1 and POE2
- Saves all patch states, colors, MTX, skills, camera zoom, and GGPK path
- Auto-loads on startup and when switching games

---

## 🚀 Getting Started

1. Download the latest release from the [Releases page](../../releases)
2. Run `Talagio90.exe`
3. Select your `Content.ggpk` or `_.index.bin` file
4. Choose your patches and hit **Apply**

> ⚠️ Always use **Recover** after a game update before re-applying patches.

---

## 🔐 License & Access

This tool uses a **license key system** tied to your hardware (HWID).

- Keys are distributed free via our **Discord server**
- Each key is valid for **30 days** and can be renewed at anytime
- Join Discord → use `/getkey` command → enter your HWID → done

👉 **[Join our Discord](https://discord.gg/77E3ffa547)**

---

## 🛡️ Safety & Recovery

Path of Exile Modding Tool is designed with recovery in mind:
- If anything goes wrong, hit **Recover** — the tool will restore your files from official game servers
- PathProtect system lets you lock specific files from being overwritten

---

## 🌐 Supported Languages

- Vietnamese
- English
- Korean
- Rusian
- *(more coming)*

---

## 🛠️ Built With

- [.NET 10](https://dotnet.microsoft.com/) + WPF
- [LibGGPK3](https://github.com/aianlinb/LibGGPK3) — GGPK read/write
- [LibBundle3](https://github.com/aianlinb/LibGGPK3) — Bundle handling
- [Pfim](https://github.com/nickbabcock/Pfim) — DDS image preview
- [Newtonsoft.Json](https://www.newtonsoft.com/json)

---

## ⚠️ Disclaimer

This tool modifies local game files for **personal, non-commercial use only**.
Use at your own risk. Always keep backups or use the built-in recovery feature.

---

## 💬 Community & Support

Have a bug? A patch idea? Want to hang out with fellow exiles?

👉 **[Discord Server](https://discord.gg/77E3ffa547)**

---

*Made with ☕ and too many hours in Wraeclast.*
