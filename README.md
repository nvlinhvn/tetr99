# 🟦 TETR99 — Battle Trainer

> A fast, no-install, browser-based block-stacking game with **garbage-line attack simulation** — built to sharpen your reflexes for competitive play.

🎮 **[Play Now →](https://nvlinhvn.github.io/tetr99/)**

---

## What Is This?

This is a **single-page Tetris trainer** that simulates the pressure of competitive battle-royale Tetris — the kind where random garbage lines slam in from opponents and you need to survive, clear, and counter at speed.

No account. No download. Just open the page and play.

---

## Features at a Glance

| Feature | Details |
|---|---|
| ⚡ **Speed Modes** | ×1 Normal · ×2 Fast · ×3 Insane |
| 🎯 **Attack Intensity** | Off · Low · Medium · High |
| 👻 **Ghost Piece** | Previews landing position |
| 🔮 **Next Queue** | See the next 4 upcoming pieces |
| 🤝 **Hold Mechanic** | Swap and save a piece for later |
| 🔊 **Retro Audio** | 8-bit BGM + SFX, toggleable |
| 📊 **Live Stats** | Score · Level · Lines cleared |
| 📋 **Attack Log** | Tracks garbage sent and received |

---

## How to Play

### Keyboard Controls

| Key | Action |
|---|---|
| `← →` | Move piece left / right |
| `↑` | Rotate clockwise |
| `Z` | Rotate counter-clockwise |
| `↓` | Soft drop |
| `Space` | Hard drop |
| `C` | Hold / swap piece |
| `P` | Pause |

### Gameplay Loop

1. **Pick your difficulty** — choose speed and how aggressively garbage lines come in
2. **Stack and clear lines** to send garbage back out
3. **Combos multiply your attack power** — chain clears to overwhelm the pressure
4. **Survive as long as possible** — garbage stacks up fast on higher settings

---

## Difficulty Guide

### Speed
- **×1 Normal** — Standard pace, good for warming up
- **×2 Fast** — Forces quicker decision-making
- **×3 Insane** — Reaction-speed training at its limits

### Attack Intensity
- **Off** — Pure Tetris, no interruption
- **Low** — Occasional garbage, manageable
- **Medium** — Consistent pressure, recommended for training
- **High** — Relentless — expect garbage every few seconds

> 💡 **Recommended training combo:** ×2 Fast + Medium attack — closely mimics real competitive match pressure.

---

## Scoring

| Clear | Base Points |
|---|---|
| Single | 100 × level |
| Double | 300 × level |
| Triple | 500 × level |
| Tetris (4 lines) | 800 × level |
| Combo bonus | +50 × combo × level |

Consecutive line clears build your **combo multiplier** and send more garbage to your opponents.

---

## Tech Stack

- **Vanilla HTML/CSS/JS** — zero dependencies, zero frameworks
- **Web Audio API** — procedural 8-bit synth (no audio files needed)
- **Canvas 2D rendering** — offscreen canvas + dirty-flag optimisation
- Retro paper aesthetic with `Share Tech Mono` font

---

## Getting Started (Self-Hosting)

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
# Just open the file — no build step needed
open index.html
```

Or drop the single `.html` file onto any static host (GitHub Pages, Netlify, Vercel).

## License

MIT — free to use, modify, and share.

---

*Built with ☕ and block-stacking obsession.*

---

*Disclaimer: This is an vibe-coded project built for practice and portfolio building. It is not affiliated with, endorsed by, or monetized by any official trademark holders.*
