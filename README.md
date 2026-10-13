<div align="center">

# FFXIV Config

A custom, information-dense HUD and hotbar setup for **Final Fantasy XIV**, built on top of
[Fr4nsson's FFXIV Config (FFC)](https://github.com/Fr4nsson/FFC) with up-to-date support for 8.x jobs.

<img width="100%" height="auto" alt="FFXIV Config preview" src="https://github.com/user-attachments/assets/14de1ec4-7703-4396-89c5-c4976dbc1cf8" />

**[📖 Documentation](https://helix-origin.github.io/FFXIV-Config/)** ·
[Installation](https://helix-origin.github.io/FFXIV-Config/docs/Installation/) ·
[Configuration Files](https://helix-origin.github.io/FFXIV-Config/docs/Configuration-Files/)

</div>

---

**FFXIV Config** pre-arranges every combat, crafting and gathering job — actions, spells, items and
macros — onto a consistent set of hotbars, with an on-screen macro menu for switching jobs and
opening common windows. Install it and play; no hotbar arranging required.

## Install in three steps

1. **Back up** your `FFXIV_CHR…` folder (the game must be closed).
2. **Copy** everything in [`src`](src) into
   `Documents\My Games\FINAL FANTASY XIV - A Realm Reborn\FFXIV_CHR<your-id>\`.
3. **Log in** and check your HUD, hotbars and menu.

> Full instructions — including multi-character setups, a PowerShell copy one-liner, and how to
> revert — are in the **[Installation guide](https://helix-origin.github.io/FFXIV-Config/docs/Installation/)**.

## Supported jobs

**Tanks** — Paladin · Warrior · Dark Knight · Gunbreaker  
**Healers** — White Mage · Scholar · Astrologian · Sage  
**Melee DPS** — Monk · Dragoon · Ninja · Samurai · Reaper · Viper  
**Physical ranged DPS** — Bard · Machinist · Dancer  
**Magical ranged DPS** — Black Mage · Summoner · Red Mage · Blue Mage · Beastmaster  
**Crafters** — Carpenter · Blacksmith · Armorer · Goldsmith · Leatherworker · Weaver · Alchemist · Culinarian  
**Gatherers** — Miner · Botanist · Fisher

## Documentation

The full reference lives at **<https://helix-origin.github.io/FFXIV-Config/>**:

- [Installation](https://helix-origin.github.io/FFXIV-Config/docs/Installation/) — requirements, backup, step-by-step install, multiple characters, reverting.
- [Configuration Files](https://helix-origin.github.io/FFXIV-Config/docs/Configuration-Files/) — exactly what each `.DAT` file controls.
- [HUD & Hotbars](https://helix-origin.github.io/FFXIV-Config/docs/Hud-And-Hotbars/) — the hotbar layout and the job-switching menu.
- [Macros](https://helix-origin.github.io/FFXIV-Config/docs/Macros/) — the macro menu and every macro the config ships.
- [Troubleshooting](https://helix-origin.github.io/FFXIV-Config/docs/Troubleshooting/) — common questions and fixes.

The documentation source (a Jekyll site built on the `helix-docs` remote theme) is in [`docs/`](docs/).

## Credits & disclaimer

- Base layout, keybinds and menu system: [Fr4nsson's FFXIV Config (FFC)](https://github.com/Fr4nsson/FFC), adapted and extended here for current 8.x jobs.
- FFXIV Config is **config-only**. Every file is one the game itself creates and reads; no third-party files or tools are required. Use at your own risk — always keep the backup described in the install guide.
