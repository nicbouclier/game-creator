# Game-Creator: Master Rules

## Target Platform
- HTML5 games for Comcast X1 / Xumo TV.
- Layout: 1280 × 720 canvas (centered, with at least 32px safe-area margins).
- All on-screen text and UI must be readable from a living room distance.

## Controls
- Only use TV remote D-pad (arrow keys: keycodes 37–40) and Enter/OK (keycode 13).
- Never require analog input, mouse, or rapid button presses.

## Code & Asset Limits
- Main JavaScript file: ≤ 300 lines.
- All assets (images, sprites, sounds, CSS, etc.): ≤ 3 MB total.
- Only inline critical CSS and JS in the HTML when possible.
- No WebGL. Use 2D Canvas or DOM rendering only.

## Visual & Audio Style — 16-bit Standards
- Visual style must evoke high-quality Sega Mega Drive/SNES games: defined, colorful, animated pixel art (never plain rectangles).
- Use color palettes sampled from NES/SNES/MD era—list hex codes in specs.
- All characters, enemies, objects, and backgrounds must be distinct pixel-art sprites (24×24 or 32×32 px recommended).
- Support multi-frame sprites for characters and objects.
- UI and menu elements: chunky, pixel-perfect, blocky with no gradients, shadows, or skeuomorphic gloss.
- Text: Only large, pixelated fonts (≥28px), e.g., “Press Start 2P”, “Pixeloid-Sans”; ensure all text fits TV readability requirements.
- Where possible, use or adapt open-license pixel art from Kenney.nl or OpenGameArt.org, or provide detailed ASCII/description for new sprites.
- If audio is included, use chiptune/synth sounds appropriate for 16-bit style.

## Game Design & Mechanics
- Each game must offer at least two fun, replayable gameplay concepts ranked by theme fit and remote-friendliness.
- Allowed genres: platformer (Sonic-style), endless runner, grid puzzle, top-down adventure, action maze, turn-based tactics, simple rhythm.
- Gameplay must work with only D-pad and Enter; design mechanics and challenge for TV/remote pace, not high-speed arcade twitch.
- Each design must specify core loop, win/loss condition, scoring, and difficulty progression (≤5 levels/phases).
- Prototype-builder and visual-designer must coordinate on every game to ensure pixel-art assets are available and referenced by name.

## Directory & File Structure
- Save every new mini-game in `games/<slug>/` with its own `index.html`, JS, CSS, and assets.
- Always provide a manifest (JSON or Markdown) of used sprites, palettes, and music.

## Deployment
- After each game is finalized and tested, commit all files, push to the main branch, and provide a public GitHub Pages preview link.
- Ensure build/deploy steps are repeatable for future automation.

---

**This file should be referenced by all agents at each workflow step.**