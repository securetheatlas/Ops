# Ink Ops

A one-map browser FPS drawn in ink. M4, pistol and knife — against an AI rival, or against a friend online.

**Play:** https://securetheatlas.github.io/Ops/

## Modes

- **Play vs Bot** — offline duel against the AI (Rookie / Soldier / Veteran).
- **Online duel (1 vs 1)** — type a name, press **HOST** and send the 4-letter room code to a friend; they type it in and press **JOIN**. The match starts as soon as both are in. Online play runs over Supabase Realtime (broadcast + presence) straight from the browser; nothing is stored.

## Controls

| Key | Action |
|---|---|
| W A S D | Move |
| Mouse | Aim · left click fires · right click aims down sights |
| 1 / 2 / 3 / wheel | M4 · Pistol · Knife |
| R | Reload |
| V | Quick knife |
| Shift | Sprint |
| C | Crouch |
| Space | Jump |
| Esc | Pause |

## Graphics

The **Graphics** setting (Low / Medium / High) changes render scale, shadows and outline detail. If a match runs below ~30 fps for a few seconds the game steps down one level by itself.

## Running it

The whole game is a single `index.html`. It loads three.js r128 from cdnjs and two Google Fonts; everything else is inline. Serve it from GitHub Pages (Settings → Pages → Deploy from branch `main`, folder `/ (root)`) or open the file directly.
