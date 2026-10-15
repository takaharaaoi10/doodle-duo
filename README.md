# Doodle Duo

A real-time, two-player drawing-and-guessing game that works across devices using WebRTC peer-to-peer connections.

## Run locally

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Publish

This is a static site. Deploy the folder to Vercel, Netlify, or GitHub Pages. No environment variables or database setup are required. The free PeerJS signaling service connects the two players; drawing and game messages travel directly between their devices.

## How to test

1. Open the deployed URL on one device and create a room.
2. Open the same URL on a second device and join using the room code.
3. Start the game from the host device.
