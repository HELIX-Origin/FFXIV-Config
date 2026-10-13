---
layout: docs
parent: Documentation Directory
title: "HUD & Hotbars"
nav_order: 3
---

# HUD & Hotbars

## Hotbar layout

FFXIV Config arranges each job's actions across ten hotbars, with a consistent set of roles:

| Hotbar | Role |
| --- | --- |
| **1–3** | **Combat** — the active job's single-target, AoE and combo actions. |
| **4–7** | **Free use** — left empty for you to fill with whatever you like. |
| **8–9** | **Utility** — role actions, sprint, mounts, items and general conveniences. |
| **10** | **Menu** — the macro menu used to switch jobs and open common windows. |
| Cross hotbar | Gamepad equivalent, enabled by the gamepad settings in `CONTROL1.DAT`. |

The macro menu itself is described in [Macros](Macros.md).

## Switching jobs

The menu hotbar drives job changes through the game's **gear sets**. Each job macro:

1. changes your active gear set to that job, and
2. reveals the hotbars for that role.

Because the macros reference gear sets by name, the names in `GEARSET.DAT` and the names the macros
use must stay in sync. If you rename a gear set in-game, update the matching macro — or simply
re-copy the config.

## The menu

The menu hotbar's macros open common windows and toggle HUD sections. A few useful ones:

- **Expand / Collapse** — show or hide the utility and free-use hotbars.
- **Free Use Hotbars / Utilites** — reveal hotbars 4–7 or 8–9 on their own.
- **Clean Hud** — hide the duty list, server info, minimap and experience bar for a minimal view.
- **Toggle Emotes** — show or hide the emote hotbar.
- **BFX 1–5** — apply a battle-effect and nameplate preset.

The full list is on the [Macros](Macros.md) page.

## HUD elements

The HUD layout (`ADDON.DAT`) positions every on-screen element the layout uses — hotbars, the job
gauge area, the party list, the minimap and the chat windows. Because it is a full HUD layout, it
also determines which elements are visible by default.

## Resolution and UI scale

`ADDON.DAT` is laid out for a specific resolution and UI scale. If your HUD looks misaligned, open
the in-game **HUD Layout** editor (System menu) and nudge the affected elements. The layout will
still work; it may just not line up perfectly until you adjust it — see
[Troubleshooting](Troubleshooting.md).

---

- **[Configuration Files](Configuration-Files.md)** — what each shipped file controls.
- **[Macros](Macros.md)** — the macro menu in detail.
