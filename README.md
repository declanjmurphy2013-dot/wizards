# Wizards & Warriors

A high-fantasy browser fighting game inspired by classic arena fighters, built as a single-file web game.

---

## Overview
Wizards & Warriors is a fast-paced 1v1 fighting game featuring unique characters, abilities, and dynamic combat. Play against the CPU or challenge a friend locally using a generated code.

---

## Characters
- 12 unique fighters
- Each has:
  - Custom stats: attack, defense, and speed
  - Unique weapon and abilities
  - Signature moves
- Includes **Morvane, Lord of the Undead**, the necromancer

---

## Controls
| Key | Action |
|-----|--------|
| Arrow Keys | Move / Jump |
| Z | Block |
| V | Quick Attack |
| X | Heavy Attack |
| C | Signature Move |
| Shift | Grab / Throw |
| Space | Super Move |

---

## Gameplay Features
- Health and super meter system
- Hidden combos, not shown to the player
- Character stat balancing
- Difficulty modes:
  - Easy
  - Normal
  - Hard
  - Nightmare
- Smooth animations for running, jumping, and combat
- Unique character models and weapons
- Magic/projectile attacks deal damage without stun or knockback
- Physical attacks, grabs, and heavy impact moves still apply knockback

---

## Multiplayer (Local)
- Host / Join system using a 6-digit code
- Uses browser `BroadcastChannel`
- Intended for same-machine or same-browser-environment play
- Joiners send their selected fighter to the host before the match starts
- Join requests retry until the host acknowledges the match

---

## Audio System
- Dynamic procedural music engine
- Modes:
  - Menu ambient music
  - Battle action music
  - End win/loss music
- Low-health visual intensity with a red flashing border
- Music adapts to game state

---

## Running the Game
Open `index.html` in a browser.
