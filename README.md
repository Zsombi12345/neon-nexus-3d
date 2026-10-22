# NEON NEXUS 3D

A 3D cooperative multiplayer survival browser game. Protect the central crystal against waves of drones.

## Play
Open `index.html` through GitHub Pages (Settings → Pages → Deploy from a branch → main → / (root)). You can also serve it with a local static web server.

## Controls
- WASD / arrow keys: move
- Mouse: aim
- Left click: fire
- Touchscreen: movement buttons and FIRE

## Multiplayer
- Host clicks **MULTIPLAYER SZOBA LÉTREHOZÁSA**.
- Share the six-character room code or invitation URL.
- Friends enter the room code and click **CSATLAKOZÁS**.
- Up to six players can join the same room.
- The host is authoritative and must remain online. If the host leaves, the session ends.
- WebRTC networking uses PeerJS and a public signaling service. Some restrictive networks may block peer-to-peer connections.

## Technical
Static HTML, CSS and JavaScript; Three.js for rendering, PeerJS for multiplayer. No dedicated backend is required. Three.js and PeerJS load from public CDNs and require internet access. All player state is ephemeral; there is no account or persistent leaderboard.

## Limitations
This is an early playable prototype, not a hardened public multiplayer service. Cross-network WebRTC connectivity is not guaranteed; a TURN relay and hosted signaling would be needed for greater reliability.
