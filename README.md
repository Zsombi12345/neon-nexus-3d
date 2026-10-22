# NEON NEXUS 3D — Anime Edition v3.0.0

A coop sci-fi 3D browser-based wave-survival game: defend the crystal against drones, upgrade your skills and survive a boss every 10 waves.

**Play online:** https://zsombi12345.github.io/neon-nexus-3d/

## Anime Edition v3 features

### Pick your look BEFORE starting
Four original, anime-styled cosplay outfits inspired by the fashion and cosplay atmosphere of **My Dress-Up Darling**:
- Marin-inspired gyaru: blonde hair, school-style outfit and pink ribbon
- Shizuku-inspired gothic cosplay: dark hair and violet-black fashion
- Rizu-inspired anime idol: sky-blue hair and bright performance outfit
- Marin-inspired streetwear: pastel pink clothes and light hair

These are game-made 3D character designs, not copied artwork or official licensed assets. Everyone in the room can see the skin you pick. The browser remembers your selection.

### Pick a Jujutsu Kaisen-inspired cursed technique
Pick one ability in the main menu; use it with **Q** in battle. Each ability has a cooldown:
- **Purple Energy Break (9s):** powerful beam through multiple enemies
- **Infinity Field (12s):** knock back and slow surrounding drones
- **Shadow Summoning (10s):** spectral wolves target up to five nearby enemies
- **Black Flash (8s):** heavy area-of-effect attack
- **Reverse Energy (17s):** heal nearby teammates and repair the crystal

Effects are performed by the authoritative host and synchronized over WebRTC in multiplayer.

### Visuals
- Anime-inspired toon-shaded characters and drones
- Character-specific hair, outfits and accessories with hand-built Three.js geometry
- Neon magical sigils and combat particles
- Name and HP bar above every player
- **Version v3.0.0** shown in the bottom-left corner
- Abilities HUD showing cooldown and readiness

## Controls
- **WASD** or arrow keys: move
- **Mouse**: aim
- **Left click**: shoot
- **Q** or tap the skill button: use selected special ability
- **Mobile touch**: directional buttons, shoot button and ability button

## Wave upgrades and boss fights
Pick one of three upgrades after each wave. In multiplayer, everyone chooses individually and the next wave starts when all players are ready. Every tenth wave has a strong titan boss with a dedicated health bar. Drone enemies have different colors, HP and movement speeds.

## Multiplayer and hosting
1. Select a skin and ability, then enter your name.
2. Press **MULTIPLAYER SZOBA LÉTREHOZÁSA** to host.
3. Invite friends with the six-character code or invitation link.
4. Friends choose their skins/abilities before joining with **CSATLAKOZÁS**.

Up to six players may join a session. Multiplayer uses PeerJS/WebRTC and depends on peer connectivity and the host remaining online.

The static site is hosted via GitHub Pages from the `main` branch and `/ (root)`. `index.html` is the entry point. Three.js and PeerJS are loaded from CDNs, requiring an internet connection.

### Notes
Game progress is not persisted between page reloads. Character menu preferences are saved locally in the browser. This is a playable prototype and not an official collaboration with any anime franchise.
