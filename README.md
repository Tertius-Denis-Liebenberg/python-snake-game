# Neon Snake Game 🐍✨

A futuristic, neon-themed Snake game built with **Python** and **Pygame**. Features include glowing neon graphics, pulsing special food, sound effects, pause functionality, and high score tracking.

## 🚀 New Features

- **Snake Color Evolution**: The snake changes its neon hue as you level up:
  - 🔵 **Level 1**: Neon Blue
  - 🟢 **Level 2**: Neon Green
  - 🟣 **Level 3**: Purple
  - 🟠 **Level 4**: Orange
  - 🟡 **Level 5**: Gold
- **Dynamic Screen Scaling**: The game physically resizes and "zooms out" as you level up, expanding the world from a small 200x200 grid to a massive 600x600 arena.
- **Fill-to-Progress Mechanic**: Unlike traditional snake games, you only advance to the next level once you have "filled" the available screen space.
- **Custom Obstacles & Mazes**: Each level introduces new wall layouts, moving from an open field to pillars, bars, and finally a complex maze.
- **Transparent HUD**: A sleek, semi-transparent top-bar displays your level, total score, and a real-time **Percentage Filled** counter (accurate to 2 decimal places).
- **Final Victory Screen**: Reach the end of Level 5 to trigger the victory state, featuring a unique win sound and completion timer.

## 🕹️ Classic Features

- **Neon Graphics**: Glowing head and tail effects with a smooth color gradient.
- **Special Food**: Pulsing yellow food spawns every 10 points for a +3 score bonus.
- **Sound Effects**: Immersive audio for eating, leveling up, and game over.
- **High Score Tracking**: Automatically saves your best performance to `highscore.txt`.

## 🛠️ Installation

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

## 🎮 How to Play

- Run the game:

```bash
python snake_game.py
```

- Control the snake using the arrow keys or `WASD`.
- Press `P` to pause or resume the game.
- Eat normal food to gain 1 point.
- Eat special food (yellow, pulsing) to gain 3 points.
- Avoid colliding with walls or yourself!

## 📊 Level Progression
| Level | Snake Color | Grid Zoom | Obstacles |
| :---: | :--- | :--- | :--- |
| 1 | 🔵 Neon Blue | 200x200 | None (Training) |
| 2 | 🟢 Neon Green | 300x300 | 4 Pillars |
| 3 | 🟣 Purple | 400x400 | Dual Bars |
| 4 | 🟠 Orange | 500x500 | Center Box |
| 5 | 🟡 Gold | 600x600 | **Final Maze** |

## 🤝 Contributing

Feel free to submit **issues**, **feature requests**, or **pull requests** to improve the game.  

## 📜 License

This project is **open-source** and free to use for learning and personal projects.

---

### One last tip for your repository:
Since you are using **GitHub**, you should also create a file named `.gitignore` in that same folder and add the following line to it:
`highscore.txt`

This ensures your personal high score doesn't get uploaded to the internet every time you update your code! 

Would you like me to generate a **neon-style banner image** that you can add to the top of this README to make it look even more professional?
