# Spin‑or‑Dodge

A minimal, one‑button arcade game where you control a spinning orb and dodge flying obstacles. Reverse your spin with a tap or a keystroke and survive as long as you can. Built entirely on a phone, plays everywhere.

## 🎮 How to Play

- A white dot automatically spins around a circle.
- Red triangles fly outward from the centre.
- Reverse the spin direction to avoid them.
- Each obstacle you dodge earns 1 point.
- Speed and spawn rate increase over time – how long can you last?

## 🎛️ Controls

| Platform | Action |
|----------|--------|
| **Mobile / Touchscreen** | Tap anywhere |
| **Desktop (Mouse)** | Click the game screen |
| **Desktop (Keyboard)** | Press `Space`, `Enter`, or any Arrow key |

> On game over, tap/press again to restart. First tap starts the game.

## ✨ Features

- **Spinning trail effect** – smooth motion blur
- **Shooting sounds** – obstacles make a crisp “pew” when they spawn
- **Wilhelm scream** – iconic scream on death
- **Vibration** – haptic feedback on mobile when you reverse
- **High score** – saved locally in your browser
- **Responsive** – works on tiny screens, full desktop, and everything between
- **No external dependencies** – pure HTML/CSS/JavaScript in one file

## 🚀 Play Now

- **itch.io**: [https://qazi-01.itch.io/spin-or-dodge](https://qazi-01/spin-or-dodge/)  
  *(Replace with your actual itch.io link after publishing)*
- **GitHub Pages**: [https://qazi-01.github.io/spin-or-dodge/](https://qazi-01.github.io/spin-or-dodge/)

## 🛠️ Tech

- Vanilla HTML, CSS, JavaScript (Canvas API)
- Web Audio API for sound effects (no external audio files)
- localStorage for high score persistence
- `pointerdown` + `keydown` for unified input handling
- Touch‑friendly with `touch-action: manipulation` to prevent double‑tap zoom

## 📱 Built on a Phone

This entire project – from code to sound design to publishing – was created using only a phone (4 GB RAM, no external keyboard). Tools used:

- **Termux** (code editor)
- **Chrome** (testing & debugging)
- **GitHub + GitHub Pages** (hosting & version control)

## 📄 License

MIT – see [LICENSE](LICENSE) for details.
