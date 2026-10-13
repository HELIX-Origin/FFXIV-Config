---
layout: docs
parent: Documentation Directory
title: Installation
nav_order: 1
---

# Installation

FFXIV Config is installed by copying the game's own character data files into your character's
folder. There is **no installer**, and nothing outside the character folder you choose is touched.

> [!WARNING]
> Installing the config **replaces** your current HUD layout, hotbars, macros, keybinds, gear sets
> and control settings **for the character you copy it to**. Back up first — see
> [step 2](#2-back-up-your-character-data).

---

## 1. Requirements

- A **Windows PC** running the Final Fantasy XIV client.
- Your character must have been logged in **at least once**, so the game has created their data
  folder.
- The game **must be fully closed** while you install. FFXIV rewrites its data files on logout and
  exit, which would overwrite your changes.

## 2. Back up your character data

1. Make sure the game is **not running**.
2. Open your FFXIV config folder:

   ```
   %USERPROFILE%\Documents\My Games\FINAL FANTASY XIV - A Realm Reborn\
   ```

   (If your `Documents` folder is synced through OneDrive, the path may be under
   `OneDrive\Documents` instead.)

3. Copy `FFXIV.cfg` and every folder starting with `FFXIV_CHR` somewhere safe.

   ```
   FFXIV.cfg
   FFXIV_CHR0048000000000001\
   FFXIV_CHR…
   ```

That backup is what you restore from if you ever want the old layout back.

## 3. Find your character's folder

Inside the config folder, each character has their own folder named `FFXIV_CHR` followed by a
16-character hexadecimal ID, for example `FFXIV_CHR0048000000000001`.

- **One character?** There will be a single `FFXIV_CHR…` folder.
- **Several characters?** Log into the character you want, exit the game, then use the `FFXIV_CHR…`
  folder with the **most recent modified timestamp** — that is the one you last played.
- **No folder at all?** Log into the character once and exit; the game will create it.

## 4. Copy the files

Copy **everything inside the [`src`](https://github.com/HELIX-Origin/FFXIV-Config/tree/main/src)
folder** into that character's `FFXIV_CHR…` folder, replacing the existing files when prompted:

```
src/*.DAT   →   …\FFXIV_CHR<ID>\
```

See [Configuration Files](Configuration-Files.md) for exactly which files are copied and what each
one controls.

## 5. Log in and verify

Start FFXIV, log into the character, and check that the HUD, hotbars and menu match the preview on
the [documentation home]({{ '/' | relative_url }}). Open the menu hotbar and try a job-change macro
to confirm the layout switches.

---

## Applying to several characters

The config is **per character**. To set it up on another character, repeat steps 2–5 for their own
`FFXIV_CHR…` folder.

## Optional: copy with PowerShell

> [!WARNING]
> Back up the character folder first. This overwrites everything in it.

```powershell
# Point this at the character's FFXIV_CHR… folder (keep the quotes)
$charFolder = "C:\Users\<You>\Documents\My Games\FINAL FANTASY XIV - A Realm Reborn\FFXIV_CHR0048000000000001"

Copy-Item -Path ".\src\*" -Destination $charFolder -Force
```

## Reverting (uninstalling)

There is nothing to uninstall — restoring your backup *is* the uninstall.

1. Close the game.
2. Delete the contents of the `FFXIV_CHR…` folder you installed into.
3. Copy your backed-up `FFXIV.cfg` and `FFXIV_CHR…` folder back into place, replacing the installed
   files.
4. Log back in to confirm your original layout has returned.

---

## Next steps

- **[Configuration Files](Configuration-Files.md)** — what each shipped file controls.
- **[HUD & Hotbars](Hud-And-Hotbars.md)** — how the layout is organised.
- **[Troubleshooting](Troubleshooting.md)** — if something does not look right.
