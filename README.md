# Maze Core


CRT handheld sonar maze for #GitHubGameOff 2025 – Theme: WAVES*
Ping expanding waves to reveal procedural mazes! Dodge pathfinding red enemies, find yellow EXIT. Every 5 levels: Genre pivot to raycasted 3D FPS HYPERSPEED – strafe/turn, collect +LIVES! Endless levels, hard mode (longer cooldowns), local leaderboards, boot seq, shake/invuln/SFX. Single-file HTML5 – browser/mobile-ready! v17.

## How to Play
- Insert Coin** → Tutorial → Level 1.
- 2D Mode: Move blindly; PING SONAR (cooldown bar) reveals green walls, red enemies (avoid touch!), yellow EXIT. Reach it to level up.
- Hyperspeed (Lv5,10...): 3D first-person maze – collect floating +LIVES, navigate to EXIT (compass arrows if off-screen). Ping flashes full brightness reveal!
- Die 3x? Game Over (high score entry). Hard Mode: Slower pings.
- Goal: Chase endless high score! Start Btn toggles overhead Map view (both modes) or Pause (2D).

## Controls

### Desktop (Keyboard – WASD + Arrows both work!)
2D Top-Down (Most Levels):
| Keys | Action |
|----------|--------------|
| **W** / **↑** | Move Up |
| **S** / **↓** | Move Down |
| **A** / **←** | Move Left |
| **D** / **→** | Move Right |
| **Space** | Sonar Ping (Reveal Waves) |
| **Enter** / **Start Btn** | Toggle Map / Pause |

**3D Hyperspeed FPS (Every 5th Level):**
| Keys | Action |
|----------|--------------------|
| **W** / **↑** | Forward |
| **S** / **↓** | Backward |
| **A** / **D** | Strafe Left/Right |
| **←** / **→** | Turn Left/Right |
| **Space** | Sonar Flash (Full Reveal) |
| **Enter** / **Start Btn** | Toggle Map View |

**Menus / High Score Entry / Settings:**
| Keys | Action |
|-------------------|---------------------------------|
| **↑** / **↓** | Select Up/Down (or Cycle Letters) |
| **←** / **→** | Move Cursor / Toggle Settings |
| **Space** / **Enter** | Confirm / Submit Name |

### Mobile / Touch
| Control | 2D Mode | 3D Mode |
|------------------|----------------------|----------------------------------|
| **D-Pad** | 4-Way Move | Forward/Back + Strafe L/R |
| **Sonar Btn** | Tap: Ping Reveal | Swipe L/R: Turn (like analog stick) |
| **Start Btn** | Toggle Map / Pause | Toggle Map View |

**Pro Tip**: Auto-resizes fullscreen. Touch-optimised dpad/sonar. Map shows full maze + your position/facing!

## Features
- Procedural maze gen w/random holes
- Smart pathfinding enemies (chase you!)
- 2D wave reveal → 3D raycaster pivot
- CRT sim: Scanlines/static/shake/boot/menus/leaderboard (localStorage)
- Procedural synth SFX, sonar cooldown HUD, lives/invuln
- Settings: Audio/Hard Mode
- Endless replayable, mobile/desktop/touch/keyboard

## Screenshots / GIF
<!-- Embed 5-7: Boot, menu, ping reveal (walls/enemy/exit), 3D view+collect+arrows, hyperspeed warning, leaderboard, name entry -->
![alt](screenshots/1-boot.png)
<!-- Use imgur/itch uploads for fast load -->

## Credits
- **A game by Just Jeffs**
- **Antic inc...**

## Play Now
[![Play on itch.io] https://justjeffs.itch.io/maze-core  <!-- itch embed -->

## Source 
`git clone https://github.com/AnticDrazelb/Maze_Core
`index.html` – Drag to browser.

#GitHubGameOff #indiedev #gamedev #WAVES #html5 #raycaster
