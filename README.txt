# TIME QUEST

A compact, genuinely playable arcade survival game made with Python and Pygame. Move through a neon arena, collect glowing time orbs, and dodge the roaming hazards. Survive the full 100 seconds for the best run.

## Play

1. Install Python 3.10 or newer from [python.org](https://www.python.org/downloads/).
2. Open a terminal in this folder and install the one dependency:
   ```
   python -m pip install pygame
   ```
3. Start the game:
   ```
   python time_quest.py
   ```

## Controls

- **WASD** or **arrow keys** — move
- **Enter** or **Space** — start / restart
- **R** — restart after a run
- **Esc** — quit

## Game rules

Collect gold orbs for points. Each orb is worth more as the run progresses. Pink hazards cost one of your three lives; after a hit, you briefly flash and return to the center. Hazards arrive more often and move faster as time passes. The run ends when the 100-second timer expires or all lives are lost.

The game is self-contained: it draws its own graphics and needs no extra art or sound files.
