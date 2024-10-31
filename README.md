
> Open this page at [https://lizard6096.github.io/jungle-rescue/](https://lizard6096.github.io/jungle-rescue/)


A thrilling, single-player, side-scrolling arcade game built in Microsoft MakeCode Arcade with Python!
Table of Contents
Project Overview
Features
Gameplay
Getting Started
How to Play
Code Explanation
Future Enhancements
Contributing
License
Project Overview
Jungle Rescue Arcade Game challenges players to navigate a jeep through a jungle landscape to rescue animals while avoiding obstacles. The player’s goal is to score as high as possible by rescuing animals and avoiding hazards. This project was developed using Microsoft MakeCode Arcade and Python, inspired by the simplicity and appeal of the Google Chrome dinosaur game.

Features
Single-player Mode: The player drives a safari jeep through the jungle on a side-scrolling screen.
Animal Rescue: Colliding with animal sprites adds points to the score.
Obstacle Avoidance: Colliding with an obstacle results in a game reset.
Score System: Points increase by 10 for each rescued animal, with speed increments every 25 points.
Progressive Challenge: The game speed increases as the score rises, making it more challenging.
Gameplay
In Jungle Rescue, the player uses the arrow keys to move the jeep vertically to:

Rescue Animals: Collide with animals to earn points.
Avoid Obstacles: Stay clear of hazards to avoid resetting the game.
The player’s objective is to score the highest possible points in a single, continuous round.

Getting Started
To set up and run this project:

Install Microsoft MakeCode Arcade: Go to MakeCode Arcade to access the editor.
Download the Code: Clone this repository or download the game code.
Load Code into MakeCode: Open MakeCode, upload the .py file, and test it directly in the simulator or on a compatible hardware device.
bash
Copy code
# Clone the repository
git clone https://github.com/yourusername/jungle-rescue-arcade-game.git
How to Play
Start Game: Press the up or down arrow key to begin.
Navigate: Use the arrow keys to move the jeep up or down.
Score Points: Collide with animal sprites to increase your score.
Avoid Hazards: Dodge obstacles to keep your game going.
Code Explanation
The code implements several key functionalities:

Intro Screen and Game Start: Displays the initial screen until the player presses an arrow key. When pressed, the jeep becomes visible, and the background switches to the jungle setting.
Spawning Animals and Obstacles: Every second, animals (which add points) or obstacles (which cause game reset) spawn randomly in the vertical range.
Collision Handling:
Animal collision: Adds points and increases speed every 25 points.
Obstacle collision: Ends the game, resets score, hides jeep, and returns to the intro screen.
Progressive Difficulty: As players collect animals, the speed of animals and obstacles increases, adding a progressive challenge.
Future Enhancements
Planned improvements include:

Levels or Milestones: Introducing different jungle scenes as milestones.
Power-ups: Adding temporary shields or speed boosts.
Sound Effects: Adding background music and sound effects for collisions.
Contributing
Contributions are welcome! Please follow these steps:

Fork this repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -am 'Add a feature').
Push to the branch (git push origin feature/your-feature).
Create a new Pull Request.
