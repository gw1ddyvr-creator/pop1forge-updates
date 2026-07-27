[README.md](https://github.com/user-attachments/files/30437261/README.md)
# POP·1 Skin Forge

A desktop toolkit for personalizing your own copy of **Population: One** — weapon
skins, billboards, sounds, and reticles. Everything it changes is on **your own PC,
in your own game files**. It never touches the game while it's running, reads no game
memory, and connects to no game servers.

Made by **GW1DDY**.

---

## Contents
- [Requirements](#requirements)
- [Installing & first run](#installing--first-run)
- [Updates (automatic)](#updates-automatic)
- [The tabs](#the-tabs)
  - [Forge (skin editor)](#forge-skin-editor)
  - [File Export](#file-export)
  - [Billboards](#billboards)
  - [Sounds](#sounds)
  - [Reticle](#reticle)
- [Backups & undo](#backups--undo)
- [Troubleshooting](#troubleshooting)
- [Terms of Use](#terms-of-use)

---

## Requirements
- Windows 10 or 11.
- The **Edge WebView2 Runtime** (already on almost every modern Windows PC; if the
  window is blank, install it free from Microsoft).
- Your **own installed copy of Population: One** (PCVR, via Meta/Steam). The app reads
  and writes only your local game files.

## Installing & first run
1. Keep `SkinForge.exe` **in its folder** — it needs the files next to it (`Library`,
   `textures`, etc.). Don't move the exe out on its own.
2. Double-click `SkinForge.exe`.
3. The first time, Windows may show **"Windows protected your PC."** That's just because
   the app isn't code-signed yet. Click **More info → Run anyway**. It opens normally
   after that.
4. **Close Population: One before applying** any change (skins, sounds, reticles). The
   game locks its files while it's open. Relaunch the game afterward to see your change.

## Updates (automatic)
You don't do anything. Each time you open Skin Forge it quietly checks for updates in
the background, downloads anything new, and applies it the next time you open the app.
No reinstalling, no store, no buttons. If it can't reach the update server, it just runs
normally.

---

## The tabs

### Forge (skin editor)
Design a weapon skin: load a gun, paint/replace its textures, and preview it in 3D.

### File Export
Turns your design into the game files: it auto-detects the right format, encodes the
textures, and repacks the weapon bundle so the game loads your skin.

### Billboards
Replace the in-game advertising signs/billboards with your own art. Extract the sign
slices, drop in replacements, and inject them back into the game.

### Sounds
Swap Population: One's sound effects (guns, items, etc.) with your own audio.
- Pick a bank, browse its sounds, and **Replace** any with a `.wav`.
- **Rebuild + install** splices your sounds in and copies the bank over the live game
  file — a **one-time backup** of the original is saved first.
- **Restore game files** puts the original bank back from that backup.
- A **Library** remembers sounds you've used so you can reuse them.

### Reticle
Put a custom crosshair into a weapon's sight. The five sights you can edit:
1. **AWP** scope · 2. **SPR** scope · 3. **Reflex** sights (MP9, MP5, MK18, RFB) ·
4. the scope's round **mask/frame** (not a crosshair) · 5. the **iron/tunnel sight**
used by AKM, FAL, Sako 85, CX4, M1014, SW357.

Open a sight with **Edit…** — it always loads the **original** to start from. Then:
- **Full reticles** library — drop in a complete crosshair (duplex, cross, circle-dot…),
  matched to the game's own line thickness.
- **Select** a part (click a line or the dot) → **Replace** it with a shape (arrows,
  dots, chevrons…) or **Import** your own PNG. Shapes snap to the crosshair centre.
- **Erase** brushes parts away. **Weight** makes lines thicker or thinner. **Move / Scale
  / Opacity** place a piece.
- **Export originals** saves the stock reticle images as a starting point to trace over.
- **Restore original** puts a sight back to stock.

Author custom art as a **white shape on a transparent background** — the game colours the
reticle itself (so it comes out the weapon's colour). A game update resets the sights, so
re-apply after game patches.

---

## Backups & undo
Every feature that writes to the game makes a **one-time backup of the original first**,
and gives you a **Restore** button. If something looks wrong in-game, close the game, hit
Restore, and relaunch. Your original files are always recoverable.

## Troubleshooting
- **"Can't write the game file"** → Population: One is still open. Close it fully, then try again.
- **Change didn't show up** → relaunch the game (it caches files at startup).
- **Blank window** → install the Edge WebView2 Runtime.
- **A scope shows black** → restore that sight and re-apply your reticle as a white shape
  on a transparent background (a solid background blacks out the lens).

---

## Terms of Use

> **DRAFT — GW1DDY: review and edit this section to match your actual terms. This is a
> starting template, not legal advice.**

By using POP·1 Skin Forge you agree that:

1. **Personal use.** Access is granted per person by GW1DDY and may be revoked at any
   time. Don't share your access key or redistribute the app or its files.
2. **Your own game, your own files.** The app only modifies your own local installation
   of Population: One. You are responsible for how you use it and for complying with the
   game's own Terms of Service.
3. **What it does / doesn't do.** It edits local textures, sounds, billboards, and
   reticles on your PC. It does **not** read game memory, automate gameplay, or provide
   any competitive advantage, and it never connects to the game's servers.
4. **Cosmetic edits at your discretion.** Skin/texture mods are covered by BigBox VR's
   written permission to GW1DDY. Other edits (sounds, reticles) are personal client-side
   changes; use your own judgement about using them in ranked/competitive play.
5. **No warranty.** The app is provided "as is," with no guarantee it works or is free of
   issues. Every change is reversible via the built-in backups, but you use it at your own
   risk. GW1DDY isn't liable for any damage, data loss, or account action resulting from
   its use.
6. **Not affiliated.** POP·1 Skin Forge is an independent fan tool. It is not made,
   endorsed, or supported by BigBox VR or Meta. "Population: One" and related names belong
   to their owners.

_© 2026 GW1DDY. All rights reserved._
