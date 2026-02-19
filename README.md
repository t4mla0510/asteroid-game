# 🚀 Asteroid Game

A classic asteroid-style arcade game built with Python Pygame library.

## Description

This is a Python implementation of the classic Asteroids arcade game where players control a spaceship navigating through an asteroid field. The objective is to survive as long as possible while destroying asteroids and avoiding collisions.

## Features

- Classic asteroid gameplay mechanics
- Player-controlled spaceship
- Asteroid destruction system
- Collision detection

## Dependencies

- Python 3.12
- Pygame (for graphics and game engine)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/tamB2203579/asteroid-game.git
cd asteroid-game
```

2. Install required dependencies:
```bash
pip install uv
uv add pygame
```

## How to Play

1. Run the game:
```bash
uv run src/main.py
```

2. Game Controls:
   - **WASD**: Move spaceship
   - **Spacebar**: Shoot
   - **ESC**: Pause/Exit game

3. Gameplay:
   - Navigate your spaceship through the asteroid field
   - Shoot asteroids to destroy them and earn points
   - Avoid colliding with asteroids
   - Survive as long as possible to achieve a high score

## Game Rules

- Destroying asteroids earns points
- Larger asteroids break into smaller pieces when shot
- Collision with asteroids ends the game
- Your score increases based on asteroids destroyed

## Project Structure

```
asteroid-game/
├── src/
│   ├── main.py           # Main game loop and initialization
│   ├── player.py         # Player spaceship class
│   ├── asteroid.py       # Asteroid object implementation
│   ├── asteroidfield.py  # Asteroid field management
│   ├── shot.py           # Projectile/bullet class
│   ├── circleshape.py    # Base class for circular game objects
│   └── constants.py      # Game configuration and constants
├── README.md  
└── ...
```

## Development

This project was created as a learning exercise to practice:
- Python programming
- Game development with Pygame
- Object-oriented programming concepts
- Game physics and collision detection

## Acknowledgments

- Inspired by the classic Asteroids arcade game
- Built with Python and Pygame
- Adapted from a python game development course on [Boot.dev](https://boot.dev)

---

Enjoy playing the game! 🚀
