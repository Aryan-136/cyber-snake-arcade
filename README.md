# :video_game: CyberSnake 2077 - Retro Cyberpunk Web Arcade

[![Play Live](https://img.shields.io/badge/PLAY%20LIVE-CYBER%20SNAKE%20ARCADE-00F5D4?style=for-the-badge&logo=gamepad&logoColor=090D16)](https://aryan-136.github.io/cyber-snake-arcade/)
[![HTML5 Canvas](https://img.shields.io/badge/Rendering-HTML5%20Canvas%202D-E34F26?style=for-the-badge&logo=html5&logoColor=white)](index.html)
[![Web Audio API](https://img.shields.io/badge/Synthesizer-Web%20Audio%20API-7928CA?style=for-the-badge&logo=audio-technica&logoColor=white)](index.html)
[![Mobile Friendly](https://img.shields.io/badge/Controls-Touch%20D--Pad%20%2F%20Swipe-00C853?style=for-the-badge&logo=android&logoColor=white)](index.html)

A high-performance, zero-dependency retro cyberpunk Snake game built entirely in pure HTML5 Canvas, modern JavaScript (ES6+), and the Web Audio API. Designed with neon visual effects, toroidal wall-wrapping physics, procedural particle explosions, and cross-platform controls.

---

## :sparkles: Live Gameplay Highlights

- **ðŸ•¹ï¸ Play Immediately in Browser**: **[aryan-136.github.io/cyber-snake-arcade](https://aryan-136.github.io/cyber-snake-arcade/)**
- **â›¶ Immersive Fullscreen Mode**: Tap or click the dedicated Fullscreen toggle to expand the arcade cabinet across 100% of your display.
- **ðŸ”Š Synthesized 8-Bit Audio**: Real-time synthesized chiptune sound effects using browser Web Audio oscillators (zero external `.mp3` or `.wav` dependencies).
- **ðŸ’¥ Dynamic Particle Explosions**: Neon spark bursts upon consuming normal cyan pellets (+15 pts) and golden star pellets (+50 pts).
- **ðŸ›¡ï¸ Input Queue Buffering**: Double-buffered input polling prevents accidental self-collision when executing rapid direction pivots (e.g., Right &rarr; Down).
- **ðŸ’¾ Local Persistence**: High scores are preserved across browser reloads via `localStorage`.

---

## :joystick: Controls Matrix

| Action | Desktop Keyboard | Mobile / Touch |
| :--- | :--- | :--- |
| **Move Up** | `ArrowUp` or `W` | On-Screen `â–²` Button or Swipe Up |
| **Move Down** | `ArrowDown` or `S` | On-Screen `â–¼` Button or Swipe Down |
| **Move Left** | `ArrowLeft` or `A` | On-Screen `â—€` Button or Swipe Left |
| **Move Right** | `ArrowRight` or `D` | On-Screen `â–¶` Button or Swipe Right |
| **Start / Restart** | `Spacebar` | Tap Canvas Screen |
| **Fullscreen** | `Fullscreen Button` | `Fullscreen Button` |

---

## :file_folder: Repository Layout
```text
.
â”œâ”€â”€ index.html        # Unified self-contained game engine, canvas renderer & Web Audio synth
â””â”€â”€ README.md         # Documentation & controls reference
```