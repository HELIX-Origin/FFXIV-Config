---
layout: docs
parent: Documentation Directory
title: Troubleshooting
nav_order: 5
---

# Troubleshooting

## Nothing changed after I copied the files

- Make sure the game was **fully closed** when you copied the files. FFXIV rewrites its data files on
  exit, so if the game was still running it would have overwritten your copy.
- Check that you copied into the **right character folder**. With several characters, pick the
  `FFXIV_CHR…` folder with the most recent modified timestamp — see
  [Installation](Installation.md#3-find-your-character-folder).

## My HUD looks misaligned or elements are in the wrong place

`ADDON.DAT` is laid out for a specific resolution and UI scale. If your HUD does not line up, open
the in-game **HUD Layout** editor from the **System** menu and nudge the affected elements. The
layout still works — it may just need a small adjustment for your display.

## Clicking a job macro does nothing

Job macros switch your active **gear set**. If nothing happens:

- Make sure the gear sets exist and that their **names match** the names the macros reference.
- If you renamed a gear set in-game, update the matching macro, or re-copy `GEARSET.DAT` and
  `MACRO.DAT` from [`src`](https://github.com/HELIX-Origin/FFXIV-Config/tree/main/src).

## My own macros are gone

Installing `MACRO.DAT` replaces every macro on the **Individual** tab. Restore your backup to get
them back — see [Installation](Installation.md#reverting-uninstalling).

## Which files did the config change?

Only the ten files listed under
[Configuration Files](Configuration-Files.md#files-that-are-installed). Your graphics, audio,
resolution and chat settings are untouched.

## Where is the squared minimap from the preview?

The squared minimap is **not** part of this config. If you want it, you can find it separately on
[xivmodarchive](https://www.xivmodarchive.com/modid/11811).

## Can I use this on console (PlayStation / Xbox)?

These are PC client data files. Console players can still transfer settings using the game's client
settings upload/download, which is described on the
[FFC project](https://github.com/Fr4nsson/FFC). That route is out of scope for this guide.

## I only want some of it (for example, the hotbars but not the keybinds)

The config is a set of individual files. Copy only the files you want from
[`src`](https://github.com/HELIX-Origin/FFXIV-Config/tree/main/src) — for example, `HOTBAR.DAT` and
`MACRO.DAT` on their own. See
[Configuration Files](Configuration-Files.md#files-that-are-installed) for what each one controls.

## How do I remove it completely?

Restore the `FFXIV.cfg` and `FFXIV_CHR…` backup you made before installing — see
[Installation](Installation.md#reverting-uninstalling).

---

- **[Installation](Installation.md)** — the full install guide.
- **[Configuration Files](Configuration-Files.md)** — what each file controls.
