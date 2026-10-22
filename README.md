# Reincarnated: Monster Evolution

A browser-based 3D fantasy exploration prototype inspired by anime reincarnation adventures.

## Play

Open [index.html](index.html) through GitHub Pages after enabling Pages in **Settings → Pages → Deploy from a branch → main → /(root) → Save**.

## Controls

- **W** — Move forward
- **S** — Move backward
- **A** — Move left
- **D** — Move right
- **Mouse** — Look around
- **Esc** — Release the mouse pointer

Click **Enter the World** to begin. Click the game again to recapture the mouse.

## Current scope

This first version focuses on movement and looking around in a fantasy landscape. Monsters and combat are intentionally not included yet.

Three.js is loaded from jsDelivr, so an internet connection is required.


## Evolution expansion

The `feature/evolution-expansion` branch adds:

- **Slimeborn, Beastkin, and Demon** race awakenings with visible transformation details.
- Race-specific ability sets, unlocked by defeating milestone bosses.
- **Monster Essence** orbs that can be collected by moving close to them.
- Rare boss relic drops, including Alpha Fang, Broodmother Core, Abyssal Heart, Titan Shard, and Eclipse Relic.
- A small HUD for essence, relic count, and the awakened class. Essence and relics persist in local browser storage.

Existing movement, weapon abilities, quests, level progression, boss arenas, and save data remain in place.
