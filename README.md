# Coin Collector 3D — Rainbow Runner

A colorful 3D coin-collecting adventure game developed using **Python, PyOpenGL, and OpenGL**. Navigate through a vibrant 3D world, collect coins, avoid obstacles, and challenge yourself across multiple difficulty levels.

## Overview

**Coin Collector 3D (CoinQuest 3D)** is a 3D arcade-style game that combines coin collection, obstacle avoidance, player movement, and time-based challenges. Players can choose a difficulty level, earn points by collecting coins, and work toward reaching the destination.

The project demonstrates fundamental game development concepts, including 3D graphics rendering, keyboard input handling, animation, collision-based gameplay, and real-time game logic.

## Key Features

- **3D Game Environment:** Explore a colorful environment with a third-person camera.
- **Multiple Difficulty Levels:** Choose Easy, Medium, or Hard to suit your preferred challenge.
- **Coin Collection and Scoring:** Collect coins and earn points during gameplay.
- **Interactive Obstacles:** Navigate around obstacles such as cupcakes, rings, blocks, and stars.
- **Player Health:** Manage your health while navigating the course.
- **Jump Mechanics:** Jump to overcome obstacles and movement challenges.
- **Time-Based Gameplay:** Play within a defined time limit.
- **Progressive Challenges:** Encounter longer courses and changing challenges as levels progress.
- **Special Abilities:** Access selected abilities depending on the difficulty level.
- **Interactive Menu:** Select a difficulty level from the introductory screen.
- **Pause and Restart:** Pause gameplay, restart a run, or return to the menu after game over.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language and game logic |
| OpenGL | Real-time 3D graphics rendering |
| PyOpenGL | Python interface for OpenGL |
| GLUT | Window management, keyboard and mouse input, and game-loop support |
| GLU | Graphics utility functions |
| `math` | Mathematical calculations |
| `random` | Randomized game elements |
| `time` | Timing and time-based gameplay |

## Game Controls

| Key | Action |
|---|---|
| `A` | Move left |
| `D` | Move right |
| `W` | Move forward |
| `S` | Move backward |
| `Space` | Jump |
| `Esc` | Pause the game |
| `R` | Restart the game |
| `B` | Return to the menu after game over |

## Special Ability Controls

Special abilities vary by difficulty level.

| Key | Ability |
|---|---|
| `F` | Fly |
| `Q` | Speed boost |
| `V` | No-clip |
| `J` | Infinite jump |
| `M` | Coin magnet |
| `H` | Reveal ability in Easy mode |

Not every ability is available in every difficulty mode.

## Difficulty Levels

- **Easy:** A more accessible experience with additional special abilities.
- **Medium:** A more challenging experience with a limited selection of special abilities.
- **Hard:** The most challenging mode, without the listed special abilities.

## Project Structure

```text
Coin-Collector-3D/
├── CoinQuest 3D
└── README.md
```

## Future Enhancements

- Add background music and sound effects.
- Introduce more levels, environments, and obstacles.
- Implement a high-score leaderboard and persistent player progress.
- Enhance visual effects, animations, and gameplay feedback.
- Include gameplay screenshots and a demonstration video.

## License

No license has been specified for this project. Until a license is added, others should not assume that they have permission to redistribute or modify the code.
