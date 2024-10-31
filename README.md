
> Open this page at [https://lizard6096.github.io/jungle-rescue/](https://lizard6096.github.io/jungle-rescue/)


# Jungle Rescue Arcade Game

### A thrilling, single-player, side-scrolling arcade game built in Microsoft MakeCode Arcade with Python!

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Gameplay](#gameplay)
4. [Getting Started](#getting-started)
5. [How to Play](#how-to-play)
6. [Code Explanation](#code-explanation)
7. [Future Enhancements](#future-enhancements)

## Project Overview
**Jungle Rescue Arcade Game** challenges players to navigate a jeep through a jungle landscape to rescue animals while avoiding obstacles. The player’s goal is to score as high as possible by rescuing animals and avoiding hazards. This project was developed using Microsoft MakeCode Arcade and Python, inspired by the simplicity and appeal of the Google Chrome dinosaur game.

## Features
- **Single-player Mode**: The player drives a safari jeep through the jungle on a side-scrolling screen.
- **Animal Rescue**: Colliding with animal sprites adds points to the score.
- **Obstacle Avoidance**: Colliding with an obstacle results in a game reset.
- **Score System**: Points increase by 10 for each rescued animal, with speed increments every 25 points.
- **Progressive Challenge**: The game speed increases as the score rises, making it more challenging.

## Gameplay
In Jungle Rescue, the player uses the arrow keys to move the jeep vertically to:
- **Rescue Animals**: Collide with animals to earn points.
- **Avoid Obstacles**: Stay clear of hazards to avoid resetting the game.

The player’s objective is to score the highest possible points in a single, continuous round.

## Getting Started
To set up and run this project:
1. **Install Microsoft MakeCode Arcade**: Go to [MakeCode Arcade](https://arcade.makecode.com/) to access the editor.
2. **Download the Code**: Clone this repository or download the game code.
3. **Load Code into MakeCode**: Open MakeCode, upload the `.py` file, and test it directly in the simulator or on a compatible hardware device.

## How to Play
1. **Start Game**: Press the up or down arrow key to begin. The jeep will appear, and the background will switch to the jungle setting.
2. **Navigate**: Use the arrow keys to move the jeep up and down. Stay within the screen boundaries and avoid obstacles.
3. **Score Points**: Collide with animals to earn points, increasing your score by 10 points per animal.
4. **Avoid Obstacles**: Hitting an obstacle ends the game, resets your score, and returns to the intro screen. Rescue as many animals as you can for the highest score!

## Code Explanation
The code implements several key functionalities:

### Intro Screen and Game Start
The game begins with an intro screen that remains visible until the player presses an arrow key. Once the game starts, the jeep becomes visible, and the background switches to a jungle theme.

### Spawning Animals and Obstacles
Animals and obstacles spawn randomly in the vertical range every second. Animals grant points when rescued, while obstacles end the game and reset the score if hit.

### Collision Handling
- **Animal Collision**: Adds points to the player’s score. Every 25 points, the game speed increases to create a progressive challenge.
- **Obstacle Collision**: Ends the game, resets the score, hides the jeep, and displays the intro screen again.

### Progressive Difficulty
As players collect animals and increase their score, the speed of both animals and obstacles accelerates. This feature increases the game’s difficulty as players progress.

## Future Enhancements
Planned improvements include:

- **Levels or Milestones**: Add variety to gameplay by changing jungle backgrounds or settings at score milestones.
- **Power-ups**: Introduce power-ups such as temporary shields or speed boosts to enhance gameplay.
- **Sound Effects**: Enhance the gaming experience with background music and sound effects for key events like collisions and collecting animals.
    start_game()
