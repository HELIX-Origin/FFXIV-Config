---
layout: docs
parent: Documentation Directory
title: Macros
nav_order: 4
---

# Macros

FFXIV Config's menu is built from **macros** stored on your character's **Individual** macro tab.
Opening the menu hotbar (hotbar 10) and clicking a button runs the matching macro.

Every character has 100 Individual macro slots. The config uses most of them, grouped below. Slots
named **Reserved** are intentionally empty placeholders for future use.

> [!NOTE]
> Installing `MACRO.DAT` **replaces all macros on your Individual tab**. If you have your own macros
> you want to keep, back them up first — see [Installation](Installation.md).

## Menu & layout controls

| Macro | What it does |
| --- | --- |
| **Expand** | Shows the utility and free-use hotbars for a full HUD. |
| **Collapse** | Hides hotbars 4–9 for a minimal HUD. |
| **Free Use Hotbars** | Shows the free-use hotbars (4–7). |
| **Utilities** | Shows the utility hotbars (8–9). |
| **Toggle Emotes** | Shows or hides the emote hotbar. |
| **Clean Hud** | Hides the duty list, server info, minimap and experience bar. |
| **Gear Sets** | Opens the gear set list. |

## Utility macros

| Macro | What it does |
| --- | --- |
| **Improved Auto-Run** | Auto-run helper. |
| **Examine Mouse Over** | Examines the player or object under your cursor. |
| **EZ Sightseeing** | Steps through sightseeing log prompts. |
| **Ridepillion** | Sit / pillion emote helper. |
| **Hide** | Emote helper that toggles a hidden state. |
| **CID Painter** | Restores HUD element colours to their defaults. |
| **Open & Sort All Inv** | Opens and sorts the armoury chest and inventory. |

## Support macros

| Macro | What it does |
| --- | --- |
| **ezCure** | Single-target healing helper. |
| **ezMedica** | Group-heal helper. |
| **Tank Regen** | Tank regeneration helper. |
| **ezRevive** | Resurrection helper. |
| **Asylum** | Asylum (White Mage) helper for your target, cursor target or mouse-over. |
| **Holmgang** | Holmgang (Warrior) helper. |

## Battle-effect presets

**BFX 1–5** apply five combinations of battle effects and nameplates, from most visible (**BFX 1**)
to fully off (**BFX 5**). **BFX 3 is the shipped default.**

| Macro | Preset |
| --- | --- |
| **BFX 1** | Most effects visible; party nameplates shown. |
| **BFX 2** | Reduced effects; party nameplates shown. |
| **BFX 3 (Default)** | Reduced effects; nameplates off. |
| **BFX 4** | Own effects only; nameplates off. |
| **BFX 5** | Battle effects off; nameplates off. |

## Job-change macros

There is one macro per job, each switching to that job's gear set. They are named after the **job**
(and its base **class**, where relevant):

**Tanks** — Paladin / Gladiator · Warrior / Marauder · Dark Knight · Gunbreaker  
**Healers** — White Mage / Conjurer · Scholar · Astrologian · Sage  
**Melee DPS** — Monk / Pugilist · Dragoon / Lancer · Ninja / Rogue · Samurai · Reaper · Viper  
**Physical ranged DPS** — Bard / Archer · Machinist · Dancer  
**Magical ranged DPS** — Black Mage / Thaumaturge · Summoner / Arcanist · Red Mage · Blue Mage · Beastmaster  
**Crafters** — Carpenter · Blacksmith · Armorer · Goldsmith · Leatherworker · Weaver · Alchemist · Culinarian  
**Gatherers** — Miner · Botanist · Fisher  

Because job changes work through gear sets, the set names in `GEARSET.DAT` and the names these macros
reference must stay in sync — see [HUD & Hotbars](Hud-And-Hotbars.md).

---

- **[HUD & Hotbars](Hud-And-Hotbars.md)** — how the layout is organised.
- **[Troubleshooting](Troubleshooting.md)** — if a macro or job switch does not behave as expected.
