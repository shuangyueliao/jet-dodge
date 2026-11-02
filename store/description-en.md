# Jet Dodge — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Hold to thrust, release to fall. Thread the gaps in laser walls, dodge
rotating turrets and outfly homing missiles in a night-city gauntlet. Near
misses pay double - how high can you fly?

(187 characters, within the 200-character limit)

## Details

- Genre: Arcade / Casual / Action
- Controls: Hold anywhere on touch, hold mouse button, or hold Space to
  thrust; release to fall. One-input gameplay, portrait-friendly.
- Features: Dual scoring (distance altitude, 10 m = 1 pt + NEAR MISS +2 with
  0.2 s slow motion), gapped laser walls with reachable gap shifts, rotating
  laser turrets (2/4 beams), homing missiles that track a predicted heading
  for 4 s then fly straight (jink to shake them off), shield powerup every
  800 points that blocks one hit, rising scroll speed, best score saved
  locally, mute toggle, procedural night-city parallax skyline and particles.
- Tech: Vanilla JavaScript, Canvas, WebAudio (jet white-noise, laser, missile
  alarm, near-miss chime — all synthesized). Single-file HTML5, zero external
  assets, no frameworks, no tracking, works offline once loaded.

## Tags
jetpack, dodge, arcade, laser, missile, casual, endless, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales to viewport, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover image (16:9) — to be captured from gameplay
- [ ] Screenshots — to be captured from gameplay

## itch.io
- Upload jet-dodge-itch.zip, mark "This file is playable in browser",
  entry file: index.html, viewport 480×720 (portrait), kind: html
- Pricing: $0 (donations optional)

## GameDistribution
- Upload jet-dodge-gd.zip (index.html only). The GD SDK auto-loads on
  gamedistribution / gd.games domains and is dormant everywhere else.
