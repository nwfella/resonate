# ⚡ RESONATE

**A path-routing puzzle game built with HTML5 Canvas + Web Audio API.**

Route the signal from source to target(s) by placing resonant nodes on the grid. Press **PULSE** and watch the wavefront ripple through your network with glowing particle trails and synthesized audio tones.

**[→ Play it live](https://nwfella.github.io/resonate)**

---

## How to Play

| Action | Desktop | Mobile |
|--------|---------|--------|
| Place a node | Click a cell | Tap a cell |
| Cycle node type | Click again | Tap again |
| Send the signal | **PULSE** button or **Space** | **PULSE** button |
| Clear all placed nodes | **CLEAR** button or **R** | **CLEAR** button |

**Node types** (cycle by clicking a cell):

| Node | Color | Symbol | Role |
|------|-------|--------|------|
| Wire | Cyan `◇` | Conducts the signal in a straight line |
| Splitter | Magenta `◈` | Branches the signal into multiple paths |
| Resonator | Gold `◎` | Sustains the signal with harmonic overtones |
| Source | Green `S` | Where the signal originates (fixed) |
| Target | Red `T` | Where the signal must reach (fixed) |
| Block | Dark `✕` | Impassable obstacle (fixed) |

Place a connected path from Source to every Target, then press PULSE. The wave expands one cell at a time — each node type plays its own distinct synthesized frequency as it activates.

---

## Levels

1. **First Light** — A straight shot to introduce the basics.
2. **The Turn** — Obstacles force an L-shaped route around a wall.
3. **Split Decision** — Two targets need a branched path through a divided grid.
4. **Cross Currents** — Three targets in a cross pattern, obstacles everywhere.
5. **Resonance** — Four targets, tight corridors, every node counts.

---

## Tech Stack

- **HTML5 Canvas 2D** — grid rendering, glow effects, particle system
- **Web Audio API** — synthesized node tones via oscillators + gain envelopes
- **Vanilla JavaScript** — no frameworks, no build step, no dependencies
- **CSS** — dark neon theme, responsive layout, touch-ready

---

## License

MIT — see [LICENSE](LICENSE).
