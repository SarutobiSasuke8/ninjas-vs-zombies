# Ninjas vs Zombies

**Top-down survival browser game** — play as a ninja surviving endless waves of zombies.

Open `index.html` in any modern browser to play.

## Concept

You are a lone ninja in a ruined city. Zombies swarm from all directions. Survive as long as possible using speed, melee, and throwing stars. Push the score higher each run.

Fits Rokumon Games: original, short-session, distinctive style, browser-native, worth discovering.

## Comprehensive Build Plan

### Phase 1 — Core Prototype (In Progress)
- [x] Top-down movement (WASD / arrows)
- [x] Mouse-aim + shoot throwing stars
- [x] Melee slash
- [x] Zombie AI (seek player)
- [x] Spawning waves with increasing difficulty
- [x] Health, score, kill counter
- [x] Collision and death
- [x] Canvas rendering with placeholder art
- [x] Local high-score (localStorage)
- [x] Start screen + game over with stats
- [x] Screen shake on damage / hits
- [x] Basic zombie variants (runner, tank)
- [x] Wave clear heal
- [ ] More map obstacles / cover
- [ ] Power-up drops

### Phase 2 — Feel & Polish
- Stamina system (dash on Shift)
- Multiple attack types refinement
- More zombie variants (exploder)
- Particle effects, hit feedback
- Sound (Web Audio API)
- Better camera (smooth follow)
- Pause menu

### Phase 3 — Progression & Content
- Power-ups (speed, damage, multi-shot, heal)
- Weapon upgrades / temporary buffs
- Procedural or hand-crafted maps with obstacles
- Leaderboards
- Unlockable ninja skins or starting perks
- Daily challenge seed

### Phase 4 — Art & Audio
- Pixel art or stylized vector sprites
- Animated walk/attack cycles
- Ambient music + SFX
- Visual theme: dusk, neon signs, cherry blossoms mixed with decay

### Phase 5 — Meta & Distribution
- GitHub Pages hosting
- Mobile touch controls
- Shareable score cards
- Submission to Rokumon Games / itch.io
- Optional PWA

### Tech Stack
- **Frontend**: HTML5 Canvas + Vanilla JavaScript (zero dependencies)
- **Hosting**: GitHub Pages (planned)
- **Persistence**: localStorage for high score

### Controls
- **WASD / Arrow keys** — Move
- **Mouse** — Aim
- **Left Click** — Throw shuriken
- **Space** — Melee slash

---

## Running the Game

1. Clone the repo
2. Open `index.html` in any modern browser
3. Or serve locally: `python -m http.server`

## Roadmap Status
- [x] Repo + design doc
- [x] Playable prototype with core loop, high-score, variants, and feedback
- [ ] Polish pass
- [ ] Art upgrade
- [ ] Mobile support
- [ ] Rokumon Games submission

Contributions welcome. Built for discovery.
