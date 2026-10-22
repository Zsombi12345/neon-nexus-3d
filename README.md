# NEON NEXUS 3D — Multiplayer Wave Survival

3D sci-fi browser game: defend a central crystal with up to six players and survive increasingly difficult drone waves.

**Play online:** https://zsombi12345.github.io/neon-nexus-3d/

## New in v2
- **3 upgrades at the end of every wave:** pick one upgrade per player. The next round waits for all active players to choose.
- **8 stackable upgrades:** attack speed, damage, movement speed, multishot, max health, health regeneration, piercing shots and crystal repair.
- Your selected upgrades appear on the right side of the screen with their levels.
- Player names and live HP bars above characters.
- Bright dual-layer plasma beams, impact sparks, rings and crystal attack warning flashes.
- **Boss encounter every 10 waves**, with a large boss model and dedicated health bar.
- Enemy varieties: fast cyan runners (low HP), pink standard drones, orange heavy drones (slower, more durable).

## Controls
- WASD or arrow keys — move
- Mouse — aim
- Left click — shoot
- Touchscreen — movement buttons and FIRE

## Multiplayer
1. One player chooses **MULTIPLAYER SZOBA LÉTREHOZÁSA**.
2. Share the 6-character room code or **MEGHÍVÁS** invitation link.
3. Other players join with the code; maximum 6 players.
4. At the end of each wave, each player chooses a personal upgrade. The host starts the next wave when all have selected.

Multiplayer is peer-to-peer using PeerJS. The host must remain in the game; WebRTC may not work on every restrictive network.

## Hosting
The static site is deployed through **GitHub Pages**, from the `main` branch and the `/ (root)` folder. `index.html` is the entry point.

## Technology
HTML, CSS, JavaScript, Three.js, PeerJS. Three.js and PeerJS are loaded from CDNs, so an internet connection is required.

## Notes
This is an early browser-game prototype. Game progress isn't saved when the page is closed, and multiplayer connections depend on network conditions.
