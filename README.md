# SNAKE LEGEND — 10-Stage Cyberpunk Edition

A landscape-first, mobile-friendly HTML5 Canvas snake game with a neon cyberpunk interface.

## Run the website

1. Extract the ZIP file.
2. Open a terminal in the extracted folder.
3. Run `python -m http.server 8000`.
4. Open `http://localhost:8000` in Chrome, Edge, or Firefox.
5. On a phone, rotate to landscape. The game displays a loading screen, then the start menu; **PLAY GAME** launches the selected stage directly.

You can also deploy the folder as a static website on any HTTPS static host. Hosting over localhost/HTTPS is recommended so browser storage works consistently.

## Game content

- Exactly 10 stages, with stage progress saved separately for Easy, Normal, and Hard.
- Stage 05 mini-boss and Stage 10 final boss.
- Progressively faster movement, larger apple quotas, and neon obstacle layouts in later stages.
- Three lives, SC coin pickups, diamonds, lightning, magnet, and shield power-ups.
- Five daily tickets, a daily free run, and a simulated rewarded-ad button.
- SC-funded skins, trails, leaderboard preview, settings, and a DONATE screen with six optional support amounts ($0.51, $1.01, $2.01, $3.01, $4.01, and $10.01 USD).
- Desktop: Arrow keys or WASD; Space/P pauses. Mobile: swipe or use the on-screen D-pad.

## Local demo limitations

Progress is stored in the browser's localStorage on the current device. The leaderboard is a local demo, not a global online leaderboard. The DONATE screen is a non-processing demo: selecting an amount does not charge money or grant SC. Connect a secure payment provider before accepting donations. The rewarded-ad action is simulated; it does not show a real ad. A production launch still needs a secure backend/account system, Play Billing or a supported web payment provider, and a rewarded-ad SDK. Never credit paid SC from an unverified client-side action.

The rendering engine is a stylized 2.5D Canvas game, not a mesh-based 3D Unity/Unreal build.


Donation options (demo only): $0.50, $0.51, $0.99, $1.01, $1.99, $2.01, $2.99, $3.01, $3.99, $4.01, $4.99, $5.01, $9.99, $10.01, $12.36, and $15.00 USD. No payment is processed until a secure payment provider is integrated.
