---
layout: docs
parent: Documentation Directory
title: Configuration Files
nav_order: 2
---

# Configuration Files

Everything FFXIV Config ships lives in
[`src`](https://github.com/HELIX-Origin/FFXIV-Config/tree/main/src). These are the game's own
**per-character data files**, copied straight into your character's `FFXIV_CHR…` folder — see
[Installation](Installation.md).

## Files that are installed

| File | What it controls |
| --- | --- |
| `ADDON.DAT` | **HUD layout & windows.** The position, size and visibility of every HUD element — hotbars, party list, minimap, job gauges, chat windows — and any saved HUD presets. |
| `HOTBAR.DAT` | **Hotbar contents.** Which action, spell, item or macro occupies each slot on hotbars 1–10 and the cross hotbars. It does **not** store hotbar screen positions. |
| `MACRO.DAT` | **Macros.** Every macro on the character's Individual tab, including the job-change and menu macros this layout relies on. |
| `KEYBIND.DAT` | **Keybinds.** All keyboard and mouse bindings. |
| `GEARSET.DAT` | **Gear sets.** The saved gear sets that the job-change macros use to switch classes and jobs. |
| `CONTROL0.DAT` | **Control settings — keyboard/mouse.** Camera, movement, targeting and hotbar-display options for the keyboard/mouse control mode. |
| `CONTROL1.DAT` | **Control settings — gamepad.** The same options for the gamepad control mode (cross hotbar and so on). |
| `UISAVE.DAT` | **Saved UI state.** Miscellaneous persisted UI state, such as retainer venture timers. |
| `ITEMODR.DAT` | **Item sort order.** The ordering used by inventory and retainer sorting. |
| `ITEMFDR.DAT` | **Item search index.** The index used by "search for item". |

## Files that are left untouched

These files live in the same place but are **not** part of FFXIV Config, so your own settings are
preserved:

| File | Location | What it controls |
| --- | --- | --- |
| `FFXIV.cfg` | One level up, in the config root | System Configuration — resolution, graphics, audio and so on. |
| `COMMON.DAT` | Character folder | Character Configuration (general character settings). |
| `LOGFLTR.DAT` | Character folder | Chat log filters. |

> [!NOTE]
> Because only the ten files above are replaced, your system/display settings and chat configuration
> stay exactly as they were.

## Where the files live

```
Documents\My Games\FINAL FANTASY XIV - A Realm Reborn\
├── FFXIV.cfg                 ← system config (not touched)
└── FFXIV_CHR<16-hex ID>\     ← one folder per character
    ├── ADDON.DAT             ← installed
    ├── HOTBAR.DAT            ← installed
    ├── MACRO.DAT             ← installed
    ├── KEYBIND.DAT           ← installed
    ├── GEARSET.DAT           ← installed
    ├── CONTROL0.DAT          ← installed
    ├── CONTROL1.DAT          ← installed
    ├── UISAVE.DAT            ← installed
    ├── ITEMODR.DAT           ← installed
    ├── ITEMFDR.DAT           ← installed
    ├── COMMON.DAT            ← your own (not touched)
    └── LOGFLTR.DAT           ← your own (not touched)
```

## Technical notes

You never need to edit these files by hand — change a setting in-game and the game rewrites them.
The notes below are for the curious:

- Each `.DAT` file has a small **17-byte header** (file type, maximum size and content size), then a
  content block, then a 15-byte null footer.
- The content is stored in one of two ways:
  - **Plain text** — `CONTROL0.DAT` and `CONTROL1.DAT` are human-readable key/value text.
  - **Masked binary** — the rest are obfuscated and structured. `MACRO.DAT`, for example, stores a
    list of typed records: a title (`T`), an icon/key (`I`, `K`) and up to 15 command lines (`L`).
- Because the files are the game's own format, they can also be inspected with a compatible reader
  such as [`carriejv/libxivdat`](https://github.com/carriejv/libxivdat). This is optional and not
  required to use the config.

---

- **[HUD & Hotbars](Hud-And-Hotbars.md)** — how the layout is organised.
- **[Macros](Macros.md)** — the macro menu in detail.
