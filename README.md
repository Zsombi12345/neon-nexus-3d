# NEON NEXUS 3D — Marin Edition v3.2.0

3D sci-fi multiplayer wave survival. Defend a crystal against drones, choose upgrades after every wave and face a boss every tenth wave.

**Play:** https://zsombi12345.github.io/neon-nexus-3d/

## New in v3.2.0 — three detailed Marin-inspired skins

Choose a skin **before entering** your singleplayer or multiplayer game. Three original, procedural 3D costumes were constructed using the provided character references from *My Dress-Up Darling*:

1. **Marin — iskolai egyenruha**: flowing blonde/pink hair, white shirt, dark blue tie, sky-blue plaid pleated skirt.
2. **Marin — blézeres viselet**: navy blazer, white lapels, dark inner layers, red tie, blue-grey pleated skirt.
3. **Marin — fekete jukata**: flower-patterned black yukata, deep magenta obi, sunset blonde and pink hair tips.

The game uses custom Three.js shapes and toon shading with modeled bangs, hair strands, eyelids, eye highlights, outfit folds, buttons, ribbons and patterns. These are stylized original game meshes, not copied or extracted anime models.

The selected skin is visible to other multiplayer participants and remembered locally between visits.

## Better shooting

The **multishot spread was reduced** from 0.17 rad to 0.045 rad between adjacent beams. Extra beams stay much closer to your cursor, allowing more precise aiming without changing the unlock/upgrades system.

## More spectacular JJK-inspired techniques

Choose one technique before the game; use **Q** (or the ability button) in the arena:

| Ability | Effect | Cooldown |
| --- | --- | --- |
| Lila energiatörés | Piercing beam that hits enemies in a line | 9 s |
| Végtelen mező | Pushes and slows nearby enemies | 12 s |
| Árnyékidézés | Hits up to five nearby enemies with shadow energy | 10 s |
| Fekete villanás | Heavy close-range area attack | 8 s |
| Fordított energia | Heals teammates and repairs the crystal | 17 s |

Visual effects now include arc lightning, animated magic circles, layered glowing beams, energy spheres, particle petals and screen shake. Host-triggered spell effects synchronize in multiplayer.

## How to play

- **WASD** / arrows — move
- **Mouse** — aim
- **Left click** — shoot
- **Q** — activate chosen special ability
- **Mobile/touch** — directional controls, FIRE, ability button

Create a room and share its six-character code (or use the invite button). Up to six players may join. The host runs the world simulation, and every player chooses one of three upgrades after each wave. A boss appears every 10th wave.

## Hosting and limitations

This site uses static HTML/CSS/JavaScript, Three.js and PeerJS. **GitHub Pages** serves `index.html` from the `main` branch's root. External CDNs require an internet connection. Multiplayer depends on peer-to-peer connectivity and on the host staying online.

Gameplay progress is reset on reload; skin and technique preferences are saved locally. This is a fan-inspired prototype, not an official franchise game.
