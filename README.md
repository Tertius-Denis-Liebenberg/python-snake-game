# Neon Snake Game 🐍✨

A futuristic, neon-themed Snake game built with **Python** and **Pygame**. Features include glowing neon graphics, pulsing special food, sound effects, pause functionality, and high score tracking.

## Features

- **Classic Snake gameplay** with smooth, accelerating movement.
- **Neon graphics** with glowing tail and head effects.
- **Special food** that appears every 10 points and gives extra score.
- **Sound effects**:
  - Eating normal food
  - Special food spawns
  - Game over
- **Pause functionality** – press `P` to pause/resume.
- **High score tracking** – your best score is saved locally.
- **Timer** – shows elapsed game time.

## Installation

1. Make sure you have **Python 3.7+** installed.
2. Install **Pygame**:

```bash
pip install pygame
```

3. Download the repository and ensure the following folder structure:

```
Snake Game/
├── snake_game.py
├── highscore.txt        # will be auto-created
└── Sound Effects/
    ├── eating.mp3
    ├── special_food.mp3
    └── game_over.mp3
```

## How to Play

- Run the game:

```bash
python snake_game.py
```

- Control the snake using the arrow keys or `WASD`.
- Press `P` to pause or resume the game.
- Eat normal food to gain 1 point.
- Eat special food (yellow, pulsing) to gain 3 points.
- Avoid colliding with walls or yourself!

## Contributing

Feel free to submit **issues**, **feature requests**, or **pull requests** to improve the game.  

## License

This project is **open-source** and free to use for learning and personal projects.
