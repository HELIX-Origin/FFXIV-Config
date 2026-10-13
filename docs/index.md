---
layout: default
title: FFXIV Config
summary: "A custom, information-dense HUD, hotbar and macro layout for Final Fantasy XIV. Every combat, crafting and gathering job is pre-arranged, with an on-screen macro menu for switching jobs and opening common windows."
nav_order: 1
notice: "<strong>Config-only.</strong> FFXIV Config ships only the game's own character data files — no installer and no third-party tools. <strong>Back up your character folder before installing.</strong>"
header_actions:
  - title: Installation Guide
    url: /docs/Installation/
    class: button--primary
  - title: Configuration Files
    url: /docs/Configuration-Files/
    class: button--secondary
  - title: View on GitHub ↗
    url: https://github.com/HELIX-Origin/FFXIV-Config
    class: button--secondary
---

<img width="100%" height="auto" alt="FFXIV Config preview" src="https://github.com/user-attachments/assets/14de1ec4-7703-4396-89c5-c4976dbc1cf8" />

## What is FFXIV Config?

**FFXIV Config** is a ready-to-use HUD, hotbar and macro layout for **Final Fantasy XIV**. Every
combat, crafting and gathering job has its actions, spells, items and macros laid out ahead of
time — so you spend your time playing instead of arranging hotbars.

It is built on top of [Fr4nsson's FFXIV Config (FFC)](https://github.com/Fr4nsson/FFC) and adapted
for current 8.x jobs. Switching jobs from the on-screen menu changes your gear set and reveals the
hotbars for that role, giving you one consistent layout across every job in the game.

## At a glance

| | |
| --- | --- |
| **What it is** | A set of the game's own per-character data files (no executable) |
| **What it changes** | HUD layout, hotbars, macros, keybinds, gear sets, control settings |
| **What it does *not* change** | Graphics, audio, resolution and chat settings |
| **Platform** | Windows PC client |
| **Requires** | Final Fantasy XIV, and the game closed while you install |

## Features

| Area | Description |
| --- | --- |
| **Hotbars 1–3** | Combat hotbars — the active job's single-target, AoE and combo actions. |
| **Hotbars 4–7** | Free-use hotbars — left empty for you to fill with whatever you like. |
| **Hotbars 8–9** | Utility hotbars — role actions, sprint, mounts, items and general conveniences. |
| **Hotbar 10** | Menu hotbar — the on-screen macro menu used to switch jobs and open common windows. |
| **Job switching** | A macro for every job that changes your gear set and reveals that role's hotbars. |
| **Clean HUD** | A one-button "Clean Hud" macro that hides the duty list, server info, minimap and experience bar. |
| **Battle-effect presets** | Five "BFX" presets that toggle battle effects and nameplates for raids or performance. |

## Supported jobs

- **Tank** — Paladin, Warrior, Dark Knight, Gunbreaker
- **Healer** — White Mage, Scholar, Astrologian, Sage
- **Melee DPS** — Monk, Dragoon, Ninja, Samurai, Reaper, Viper
- **Physical ranged DPS** — Bard, Machinist, Dancer
- **Magical ranged DPS** — Black Mage, Summoner, Red Mage, Blue Mage, Beastmaster
- **Disciples of the Hand (crafters)** — Carpenter, Blacksmith, Armorer, Goldsmith, Leatherworker, Weaver, Alchemist, Culinarian
- **Disciples of the Land (gatherers)** — Miner, Botanist, Fisher

## Explore the documentation

- **[Installation]({{ '/docs/Installation/' | relative_url }})** — requirements, backing up, and step-by-step installation (including multiple characters and reverting).
- **[Configuration Files]({{ '/docs/Configuration-Files/' | relative_url }})** — exactly which `.DAT` file controls what.
- **[HUD & Hotbars]({{ '/docs/Hud-And-Hotbars/' | relative_url }})** — how the hotbars and menu are organised.
- **[Macros]({{ '/docs/Macros/' | relative_url }})** — the macro menu and every macro the config ships.
- **[Troubleshooting]({{ '/docs/Troubleshooting/' | relative_url }})** — common questions and fixes.

## Credits & disclaimer

- Base layout, keybinds and menu system: [Fr4nsson's FFXIV Config (FFC)](https://github.com/Fr4nsson/FFC), adapted and extended for current 8.x jobs.
- FFXIV Config is **config-only**. Every file is one the game itself creates and reads; no third-party files or tools are required. Use at your own risk — always keep the backup described in the [Installation]({{ '/docs/Installation/' | relative_url }}) guide.
