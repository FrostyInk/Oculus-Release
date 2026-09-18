# Oculus

A [Nexus](https://github.com/RaidcoreGG/Nexus) addon for Guild Wars 2. Toggle an in-game overlay that shows
a targeted (or your own) player's equipped gear — stat combinations, runes, sigils, relics, infusions — and
active traits/specializations.

This repository distributes the built addon only. The source is closed for now.

## Installation

1. Install [Nexus](https://github.com/RaidcoreGG/Nexus) if you haven't already.
2. Download `Oculus.dll` from this repo and place it in `<Guild Wars 2>/addons/`.
3. Launch the game — Nexus loads the addon automatically.
4. Press `CTRL+G` (rebindable in Nexus's Keybinds settings) to toggle the inspection window.

## What it does

- Shows equipped armor, weapons, and trinkets for your current target (or yourself if nothing is targeted),
  including resolved names for stat combinations, runes, sigils, relics, and infusions.
- Optionally shows active traits/specializations (toggle in the window itself).
- Read-only and non-automated — it inspects data the game already has loaded, the same way tools like
  arcdps, kx-vision, and gw2-reffect do. It never modifies game state or automates any in-game action.

## Version

`2026.9.18.10`

## Author

Ashen
