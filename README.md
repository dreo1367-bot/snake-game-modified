# Snake Game (Modified Open Source)

A classic Snake game with Conway's Game of Life animated background, built with Python + Pygame.

## Modifications
- Added sound effects (eat / game over), generated in-memory (no external asset files)
- Headless-safe audio/video initialization fallbacks
- Built into a standalone executable with PyInstaller (`--onefile`)

## Run from source
```bash
pip install pygame
python snake_game.py
```

## Controls
- Arrow keys / WASD — move
- Enter — start/restart, ESC — menu/quit, P — pause
