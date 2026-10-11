# Neon Blaster 3D

A relaxed 2.5D side-scroller on a neon Tokyo night street, made in Unity 6 (URP).
You play the Crimson Sentinel mech, armed with the Sakura Pulse Cannon, on your way to the torii gate.

**▶ Play in your browser: https://garciaisaac93.github.io/neon-blaster-3d/**

## Controls
| | Keyboard (computer) | Touch (phone/tablet, turn it sideways) |
|---|---|---|
| Move | A / D or ← / → | round `<` `>` buttons, bottom left |
| Jump | Space, W, ↑, K or Z | JUMP button, bottom right |
| Hover (jetpack) | keep holding jump while falling | keep holding JUMP |
| Shoot | J or X | FIRE button |

You can move and shoot at the same time, with two thumbs on a phone.
Touch the lantern posts to save a checkpoint. If you fall into a canal you go back to the last one.

## About this repo
This repo only holds the finished web build (`index.html`, `Build/`, `TemplateData/`).
GitHub Actions publishes it to GitHub Pages on every push to `main`. The files are gzip-compressed with
Unity's "decompression fallback", so they work on GitHub Pages without special server settings.

Credits: Meshy AI hero and cannon models; Kenney and Quaternius CC0 kits; Poly Haven night sky (CC0);
backdrop art from the 2D *Neon Blaster* web game.
