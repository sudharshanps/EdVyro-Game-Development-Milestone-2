# ONE-PAGE GAME DESIGN DOCUMENT
## Packet Pulse: Firewall Shift · Version 1.0
**Creator:** Sudharshan P S  |  **Project:** EdVyro Game Development — Milestone 2  |  **Platform:** Browser (desktop and mobile)

### 1. Player fantasy and audience
Act as a futuristic network gatekeeper, rapidly switching a fictional firewall between two modes. Designed for new players, students, and casual arcade-game fans ages 12+; no technical cybersecurity knowledge is required. Session target: **3 minutes**.

### 2. Core concept and one-action mechanic
Colored packets travel downward toward a gateway. **The only gameplay action is toggling firewall mode** between ALLOW and BLOCK. A teal **SAFE** packet must meet **ALLOW**; an amber **THREAT** packet must meet **BLOCK**. The packet's label and symbol reinforce its color for accessibility.

### 3. Core loop: action → feedback → consequence → next decision
**Observe** incoming packet → **switch** mode as needed → packet reaches gateway → **receive** immediate feedback (+10 or −1 life) → **prepare** for next packet. Packets come one at a time with a short preparation gap. No movement or aiming mechanics.

### 4. Rules, goal, and outcomes
Start with 6 lives and a 3:00 timer. Correct match: +10 points, +1 correct, streak increases. Incorrect match: −1 life, streak resets. **Win** when the full 3 minutes finish with **30+ correct matches and at least 1 life**. **Lose** when lives reach zero or fewer than 30 matches are achieved by time-up. On-screen stats show time, correct matches, lives, mode, score, and streak.

### 5. Controls and feedback states
- **Keyboard:** Space toggles ALLOW/BLOCK; P pauses/resumes; R restarts.
- **Touch/mouse:** tap arena or Switch button; visible Pause and Restart buttons.
- **Onboarding:** instructions overlay with a Start button.
- **Feedback:** teal "+10" for correct, red "−1 life" for incorrect; distinct mode and packet labels; countdown and live status.
- **Pause:** packet freezes under pause overlay; **Restart:** clears score/time and begins a fresh run; **End:** win/loss overlay with Replay button.

### 6. Main screen wireframe and art direction
See `screen-sketch.png`. Layout: heading → 4 stat cards → central packet lane, gateway, feedback → rules/control panel. Placeholder art uses original CSS shapes: grid, glow, glyphs, and two high-contrast packet colors. Responsive 360px+ design, visible focus indicators, keyboard and touch.

### 7. Scope boundaries and test plan
**Included:** one mechanic, two packet types, score/lives, 3-minute session, start/pause/restart/win/lose, responsive layout. **Excluded:** real packet analysis, accounts, online scores, audio, multiplayer, skins, power-ups, backend. Test with a keyboard and phone; verify safe/allow, threat/block, mismatches, pause, restart, and ending states. See `PLAYTEST.md` for an observation form.