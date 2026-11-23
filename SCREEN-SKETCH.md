# Main Screen Sketch — Packet Pulse: Firewall Shift

This is the original wireframe for the EdVyro Game Development Milestone 2 prototype. Open `index.html` for the implemented version.

```text
┌──────────────────────────────────────────────────────┐
│  PACKET PULSE: FIREWALL SHIFT                         │
│  Match incoming packets with the correct firewall    │
├────────────┬────────────┬────────────┬───────────────┤
│ TIME 03:00 │ SCORE 0000 │ LIVES  ♥♥♥ │ CORRECT  0/30 │
├────────────┴────────────┴────────────┴───────────────┤
│                                                      │
│             ↓ SAFE / THREAT PACKET ↓                 │
│                                                      │
│                 [ PACKET ]                           │
│                                                      │
│  - - - - - - FIREWALL GATEWAY - - - - - - - - -      │
│                                                      │
│                MODE: ALLOW / BLOCK                   │
│                                                      │
│           +10 CORRECT  /  -1 LIFE                    │
│                                                      │
├──────────────────────────────────────────────────────┤
│ [ SWITCH FIREWALL MODE ]  [ PAUSE ]  [ RESTART ]     │
│                                                      │
│ SAFE → ALLOW      THREAT → BLOCK                     │
│ Keyboard: SPACE toggle · P pause · R restart         │
└──────────────────────────────────────────────────────┘
```

## Feedback states

| State | Visual and behavior |
| --- | --- |
| Ready | Instructions, start button, countdown at 03:00 |
| Correct match | Teal +10, correct count increases, streak increases |
| Wrong match | Red -1 LIFE, life count drops, streak resets |
| Pause | Dark pause overlay, packet motion and timer frozen |
| Win | Win overlay after 3 minutes with at least 30 correct matches and 1 life |
| Loss | Loss overlay when lives reach zero or end target is missed |
| Restart | New run with reset time, score, packet sequence, lives |

## Responsive sketch

On narrow screens, the stats wrap into a compact grid, the packet lane stays centered, and full-width touch controls sit below the lane. The same information is retained on desktop and mobile.
