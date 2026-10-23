# Neon Blaster 2D: sound effect credits (v6; v7 jump, v8 charge shot)

## Sound effects shipped in this build (assets/sfx/, each as .ogg Vorbis q3 + .m4a AAC-LC 64k, mono 44.1 kHz)
All sound effects come from four Kenney audio packs, released under **Creative Commons Zero (CC0 1.0)**
(http://creativecommons.org/publicdomain/zero/1.0/): free for personal, educational and commercial use, no attribution required.
Credit (optional, kindly requested by the author): "Sound effects by Kenney (www.kenney.nl)".
Packs (downloaded 2026-10-22 from kenney.nl; License.txt in each zip says CC0):
- Sci-fi Sounds 1.0 - https://kenney.nl/assets/sci-fi-sounds
- Impact Sounds - https://kenney.nl/assets/impact-sounds
- Interface Sounds - https://kenney.nl/assets/interface-sounds
- Digital Audio - https://kenney.nl/assets/digital-audio

Edits (tools/make_sfx.py): layering / pitch shifts as listed, silence trimmed, short fades, loudness-normalised, re-encoded. No other sources and no synthesized sounds.

| Shipped file | Used for | Kenney source (pack + file, edits) | Length | License |
|---|---|---|---|---|
| shot.ogg / .m4a | Ronin blaster shot | Sci-fi Sounds laserSmall_000.ogg (trimmed to 0.24 s) | 0.24 s | CC0 1.0 |
| hit.ogg / .m4a | shot hits a drone (not a kill) | Sci-fi Sounds impactMetal_004.ogg (high-passed) + Interface Sounds glass_002.ogg (tick layer), 0.22 s | 0.18 s | CC0 1.0 |
| boom_s.ogg / .m4a | patrol / fast drone explosion (fast: rate 1.1) | Sci-fi Sounds explosionCrunch_000.ogg | 0.72 s | CC0 1.0 |
| boom_l.ogg / .m4a | heavy drone explosion | Sci-fi Sounds explosionCrunch_002.ogg + lowFrequency_explosion_001.ogg (low-passed sub layer), 1.25 s | 1.24 s | CC0 1.0 |
| enemy_shot.ogg / .m4a | drone shot (heavy 0.85x, fast 1.12x rate) | Sci-fi Sounds laserRetro_002.ogg, pitched -4 semitones | 0.29 s | CC0 1.0 |
| hurt.ogg / .m4a | Ronin hit | Impact Sounds impactPunch_medium_000.ogg + Interface Sounds error_007.ogg (-3 st buzz layer) | 0.29 s | CC0 1.0 |
| death.ogg / .m4a | Ronin death | Digital Audio zapThreeToneDown.ogg + Sci-fi Sounds lowFrequency_explosion_001.ogg (low-passed) | 1.27 s | CC0 1.0 |
| jump.ogg / .m4a | jump (heel boosters) | Impact Sounds footstep_concrete_000.ogg + Sci-fi Sounds thrusterFire_003.ogg (first 0.35 s) | 0.33 s | CC0 1.0 |
| boost.ogg / .m4a | jetpack ignition burst (each hover start) | Sci-fi Sounds thrusterFire_001.ogg (first 0.45 s, burst) | 0.41 s | CC0 1.0 |
| hover_loop.ogg / .m4a | quiet thruster loop while hovering | Sci-fi Sounds thrusterFire_000.ogg (1.2-2.58 s, low-passed, crossfaded into a 1.2 s seamless loop) | 1.20 s | CC0 1.0 |
| land.ogg / .m4a | landing thud | Impact Sounds impactSoft_medium_000.ogg (low-passed) | 0.12 s | CC0 1.0 |
| pickup.ogg / .m4a | energy cell (rate steps +1 semitone per quick pickup, max +5) | Interface Sounds glass_001.ogg + the same pitched +7 st, 45 ms later (two-note chime) | 0.26 s | CC0 1.0 |
| checkpoint.ogg / .m4a | checkpoint reached | Interface Sounds confirmation_004.ogg | 0.49 s | CC0 1.0 |
| pit.ogg / .m4a | fall into a pit | Digital Audio lowDown.ogg | 0.63 s | CC0 1.0 |
| complete.ogg / .m4a | LEVEL COMPLETE jingle | Digital Audio powerUp11.ogg + Interface Sounds glass_004.ogg stacked as a major chord (0/+4/+7/+12 st) | 0.79 s | CC0 1.0 |
| ui.ogg / .m4a | title screen tap | Interface Sounds maximize_008.ogg | 0.21 s | CC0 1.0 |
| charge_rise.ogg / .m4a | charge shot: rising hum while charging (v8) | Sci-fi Sounds forceField_000.ogg (low-passed, pitch glide -9 -> 0 st, swelling) + Digital Audio phaserUp3.ogg (glide -5 -> +2 st, quiet), 1.0 s | 0.96 s | CC0 1.0 |
| charge_loop.ogg / .m4a | charge shot: quiet hum loop while fully charged (v8) | Sci-fi Sounds forceField_000.ogg (0.15-0.89 s, low-passed, crossfaded into a 0.6 s seamless loop) | 0.60 s | CC0 1.0 |
| charge_ready.ogg / .m4a | charge shot: ready ping at full charge (v8) | Interface Sounds glass_003.ogg stacked 0 / +7 / +12 st, 30 ms apart (ready ping) | 0.12 s | CC0 1.0 |
| blast.ogg / .m4a | charged blast release (v8) | Sci-fi Sounds laserLarge_000.ogg + lowFrequency_explosion_001.ogg (first 0.5 s, low-passed sub) + Impact Sounds impactPunch_heavy_000.ogg (low-passed thump), 0.75 s | 0.68 s | CC0 1.0 |

Total (20 sounds): 142,853 bytes ogg + 113,729 bytes m4a (a browser loads one format: ~139 KB ogg or ~111 KB m4a).

---

# Neon Blaster 2D (Level 1 'Neon Street' preview): music credits

## Music shipped in this build (assets/audio/, each as .ogg + .m4a, re-encoded ~96 kbps)
| Shipped file | Used for | Source file below | License |
|---|---|---|---|
| menu_chill_lofi_loop.ogg / .m4a | title screen | slot2_a_chill_lofi_inspired_loop.ogg | CC0 1.0 |
| level_neon_pagoda.ogg / .m4a | level | slot1_a_neon_pagoda.mp3 | CC-BY 4.0 |
| boss_mist_city.ogg / .m4a | end arena (boss placeholder) | slot3_a_mist_city.ogg | CC-BY 4.0 |

In-game credits (title screen):
- "Neon Pagoda" by joeBaxterWebb (https://opengameart.org/content/neon-pagoda), licensed CC-BY 4.0 (https://creativecommons.org/licenses/by/4.0/)
- "Mist City" by Section7 at OpenGameArt (https://opengameart.org/content/mist-city), licensed CC-BY 4.0
- "Chill lofi inspired" by omfgdude, made loopable by qubodup, CC0

The original candidate list and license notes follow unchanged.

---

# Neon Blaster: Music Candidates and Credits

All tracks come from OpenGameArt.org. Each one is CC0 (public domain) or CC-BY / OGA-BY, so it can be bundled in a public web game.
None of them is NC, ND, SA, or "personal use only". Licenses were checked on each source page on 2026-10-22.
CC-BY tracks need the attribution line in the game credits (for example a Credits screen or a CREDITS file in the repo). For CC0 tracks, credit is optional but nice.

| File | Title | Artist | Duration | License |
|---|---|---|---|---|
| slot1_a_neon_pagoda.mp3 | Neon Pagoda | joeBaxterWebb | 2:15 | CC-BY 4.0 |
| slot1_b_ninja_theme.ogg | Ninja Theme | Spring Spring (Julie Damsgaard) | 2:44 | CC0 |
| slot1_c_four_sequence.mp3 (spare) | Four Sequence | Indieteur | 2:36 | CC0 |
| slot2_a_chill_lofi_inspired_loop.ogg | Chill lofi inspired [loop edit] | omfgdude (loop edit by qubodup) | 1:37 | CC0 |
| slot2_b_lofi_again.ogg | Lofi again | omfgdude | 1:28 | CC0 |
| slot3_a_mist_city.ogg | Mist City | Section7 | 2:55 | CC-BY 4.0 |
| slot3_b_resistor.mp3 | Resistor | FoxSynergy | 4:11 | CC-BY 3.0 |

Each track has a 30-second preview, `slotN_x_preview.mp3`, with a 1s fade in and out. Previews are for listening only. Do not ship them.

---

## Slot 1: Main level ("cyber samurai")

### slot1_a: Neon Pagoda
- Artist: joeBaxterWebb
- Source page: https://opengameart.org/content/neon-pagoda
- Direct download: https://opengameart.org/sites/default/files/Neon%20Pagoda.mp3
- License: CC-BY 4.0, https://creativecommons.org/licenses/by/4.0/
- Attribution required: `"Neon Pagoda" by joeBaxterWebb (https://opengameart.org/content/neon-pagoda), licensed CC-BY 4.0 (https://creativecommons.org/licenses/by/4.0/)`
- Duration: 2:15 (134.8 s), MP3
- Source tags/description: scifi, asian, dance. "A floaty but urgent scifi scene, with asian overtones."

### slot1_b: Ninja Theme
- Artist: Spring Spring (Julie Damsgaard / Spring Enterprises)
- Source page: https://opengameart.org/content/ninja-theme
- Direct download: https://opengameart.org/sites/default/files/ninja%20theme.ogg
- License: CC0 1.0 (public domain), https://creativecommons.org/publicdomain/zero/1.0/
- Attribution: not required. Suggested: `"Ninja Theme" produced by Julie Damsgaard / Spring Spring / Spring Enterprises (https://spring-enterprises.neocities.org), CC0`
- Duration: 2:44 (164.0 s), OGG Vorbis
- Source tags/description: ninja, bells, koto, synth, FM synth, arpeggio, flute. "Reminds me of the theme to Double Dragon 3."

### slot1_c (spare): Four Sequence
- Artist: Indieteur
- Source page: https://opengameart.org/content/four-sequence
- Direct download: https://opengameart.org/sites/default/files/Four%20Sequence.mp3
- License: CC0 1.0, https://creativecommons.org/publicdomain/zero/1.0/
- Attribution: not required ("Attribution will be appreciated but not required"). Suggested: `"Four Sequence" by Indieteur, CC0`
- Duration: 2:36 (156.0 s), MP3
- Source tags/description: asian, city, cityspace, electronic, EDM. "A kind of eastern cityspace EDM background music."

## Slot 2: Menu / quiet moments (lofi)

### slot2_a: Chill lofi inspired [loop edit]
- Artist: omfgdude (original). Seamless loop edit by qubodup.
- Source page: https://opengameart.org/content/chill-lofi-inspired-loop-edit (original: https://opengameart.org/content/chill-lofi-inspired)
- Direct download: https://opengameart.org/sites/default/files/chilllofir-loop.ogg
- License: CC0 1.0 (original and loop edit), https://creativecommons.org/publicdomain/zero/1.0/
- Attribution: optional. Suggested: `"Chill lofi inspired" by omfgdude, made loopable by qubodup, CC0`
- Duration: 1:37 (97.2 s), OGG Vorbis, seamless loop
- Source tags/description: chill, lofi, jazzy, piano, drums, hip hop. "A short song inspired by lofi hip hop" (Yamaha CVP-701 styles).

### slot2_b: Lofi again
- Artist: omfgdude
- Source page: https://opengameart.org/content/lofi-again
- Direct download: https://opengameart.org/sites/default/files/lofiagain.ogg
- License: CC0 1.0, https://creativecommons.org/publicdomain/zero/1.0/
- Attribution: optional. Suggested: `"Lofi again" by Omfgdude, CC0`
- Duration: 1:28 (87.8 s), OGG Vorbis
- Source tags/description: lofi, hiphop, loop, chill. "Korg Triton, 4 instrumental tracks and some ambience."

## Slot 3: Boss fight (darksynth)

### slot3_a: Mist City
- Artist: Section7
- Source page: https://opengameart.org/content/mist-city
- Direct download: https://opengameart.org/sites/default/files/mist_city.ogg
- License: CC-BY 4.0, https://creativecommons.org/licenses/by/4.0/
- Attribution required (the author's requested wording): `"Mist City" by Section7 at OpenGameArt (https://opengameart.org/content/mist-city), licensed CC-BY 4.0`
- Duration: 2:55 (175.4 s), OGG Vorbis
- Source tags/description: synthwave, darksynth, futuristic, dark, modern-retro, retro synth. "Darksynth track."

### slot3_b: Resistor
- Artist: FoxSynergy
- Source page: https://opengameart.org/content/resistor
- Direct download: https://opengameart.org/sites/default/files/FoxSynergy%20-%20Resistor%20v1.0.mp3
- License: CC-BY 3.0, https://creativecommons.org/licenses/by/3.0/
- Attribution required: `"Resistor" by FoxSynergy (https://opengameart.org/content/resistor), licensed CC-BY 3.0 (https://creativecommons.org/licenses/by/3.0/)`
- Duration: 4:11 (251.5 s), MP3
- Source tags/description: drums, synth, tech, boss. "A boss fight theme originally made for BoltSabre... Heavy drums, klaxons, and somewhat frantic and oppressive synth."

---

## Suggested in-game credits block (if you ship slot1_a, slot3_a, slot3_b)
```
Music:
"Neon Pagoda" by joeBaxterWebb - CC-BY 4.0 - opengameart.org/content/neon-pagoda
"Mist City" by Section7 at OpenGameArt - CC-BY 4.0 - opengameart.org/content/mist-city
"Resistor" by FoxSynergy - CC-BY 3.0 - opengameart.org/content/resistor
"Ninja Theme" by Spring Spring (CC0), "Chill lofi inspired" by omfgdude / loop by qubodup (CC0),
"Lofi again" by omfgdude (CC0)
```
