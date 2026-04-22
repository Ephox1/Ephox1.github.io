# CYBERPONG

A neon-soaked, single-file take on the classic. Vanilla HTML/CSS/JS — no frameworks, no build step, no dependencies.

**Play it:** [ephox1.github.io/pong](https://ephox1.github.io/pong/)

---

## How to play

1. Open the page in any modern browser.
2. **Click the canvas once** so your browser allows audio.
3. Use the arrow keys to navigate the menu, press **Enter** to select.
4. First player to **7 points** wins.

## Controls

| Action              | Key           |
| ------------------- | ------------- |
| Navigate menu       | `↑` / `↓`     |
| Select / confirm    | `Enter` / `Space` |
| Toggle menu option  | `←` / `→`     |
| Player 1 paddle     | `W` / `S`     |
| Player 2 paddle     | `↑` / `↓`     |
| Mute / unmute       | `M`           |
| Return to menu      | `Esc`         |

## Modes

- **1P vs CPU** — tracking AI with a deliberate reaction delay so it's beatable.
- **2P Local** — two players on the same keyboard.

## Features

- Neon cyberpunk palette with glow, scanlines, and a perspective grid
- Paddle physics that factor contact position into the bounce angle
- Procedural chiptune soundtrack + SFX generated live via the Web Audio API (no audio files)
- Particle trail on the ball for that extra arcade feel
- Runs entirely client-side — one HTML file, no build step

## Stack

- HTML5 Canvas for rendering
- Web Audio API for music and SFX
- Vanilla JavaScript (no frameworks)

## Run locally

```bash
git clone https://github.com/Ephox1/Ephox1.github.io
cd Ephox1.github.io/pong
# open index.html directly, or:
python -m http.server 8000
# then visit http://localhost:8000
```

## License

[MIT](../LICENSE) © Nevin Bruce
