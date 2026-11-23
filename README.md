# Packet Pulse: Firewall Shift

**Game Development — EdVyro, Milestone 2: Game Design Document and Playable Prototype**  
**Creator:** Sudharshan P S  
**Technology:** HTML, CSS, vanilla JavaScript (no packages, accounts, servers, or third-party assets)

## Play the game

**Live playable link:** _Add your GitHub Pages link here after publishing._

You can also download/open `index.html` in any modern browser. On GitHub Pages it runs immediately with no setup.

![Packet Pulse playable game screenshot](preview-gameplay.png)

## The game

In a fictional network gateway, incoming packets are either **SAFE** or **THREAT**. The player performs exactly one kind of action: switch the gateway mode. Set **ALLOW** for SAFE packets and **BLOCK** for THREAT packets before they reach the dashed gateway line. Every correct response earns 10 points. Every wrong response costs one life. Survive for 180 seconds with at least 30 correct packets and one life remaining to win.

**Controls:** Space = switch mode; tap game arena or "Switch firewall mode" = switch mode; P = pause/resume; R = restart; on-screen Pause and Restart buttons are provided.

## Files

- `index.html` — self-contained playable browser game (source code and prototype)
- `GDD.pdf` / `GDD.md` — one-page game design document
- `screen-sketch.png` — screen layout and feedback-state sketch
- `PLAYTEST.md` — testing template and manual functional checklist
- `CHECKLIST.md` — EdVyro submission checklist
- `preview-gameplay.png` / `preview-mobile.png` — desktop and mobile screenshots

## Publish — one public proof link

1. Create a **public** GitHub repository named `packet-pulse-game`.
2. Upload the contents of this folder, including `index.html`, `README.md`, `GDD.pdf`, and `screen-sketch.png`.
3. In repository **Settings → Pages**, set **Deploy from a branch → main → /(root)** and save.
4. Once deployed, open `https://YOUR-USERNAME.github.io/packet-pulse-game/` and test the game.
5. Edit the "Live playable link" line above to show your actual deployed URL.
6. Paste your **public GitHub repository URL** into EdVyro's **Project URL** field. The repository contains the design document, prototype source, screen sketch, and a link to the playable version.

> Publishing is not done automatically by downloading these files. You must upload the project before you can submit a public URL.

## Scope

This is intentionally a small, original prototype with CSS placeholder artwork. No accounts, real networking, tracking, purchased assets, or backend are involved. The packet types are fictional labels for gameplay, not an actual network-security classifier.