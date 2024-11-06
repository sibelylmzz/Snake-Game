# Snake-Game 🐍
A classic Snake game built using Python's turtle library! 
Control the snake, collect food, and watch your score grow. 
But beware—hitting the wall or your own tail will reset your score.

# 🎮 Game Preview

![Screenshot from 2024-11-06 17-08-07](https://github.com/user-attachments/assets/6fc0e33c-eb3d-4a4c-af41-27001e0d7ac5)

# 🚀 Features
Smooth Movement: Control the snake with arrow keys.
Random Food Generation: Food spawns randomly on the screen, and collecting it extends the snake.
Score Tracking: Displays current and high scores in the top center.
Self-Collision & Wall Detection: Game resets upon collision with walls or the snake's own body.

# 🛠️ Installation

git clone https://github.com/your-username/Snake-Game.git

cd snake-game

Install required dependencies (if any):

This game is built with Python's turtle graphics library, which is included in the Python Standard Library. Ensure you have Python 3.6+ installed.

Run the game:

python main.py

# 🎯 How to Play
Use the arrow keys to control the snake:

Up Arrow: Move Up
Down Arrow: Move Down
Left Arrow: Move Left
Right Arrow: Move Right
Objective: Collect as much food as possible without hitting the walls or the snake's own body.
Scoring: Each piece of food increases your score by 1. The game resets if you collide with the wall or your own tail.

# 🗂️ Project Structure

snake-game/

│

├── main.py             # The main game loop and screen setup

├── snake.py            # Snake class handling movement, growth, and direction

├── food.py             # Food class for spawning food at random locations

├── scoreboard.py       # Scoreboard class to track and display scores

└── data.txt            # Stores the high score

# 👾 Code Highlights
Collision Detection: The game detects collisions between the snake and walls or food and handles scoring and resets.
Score Persistence: The highest score is saved in data.txt and displayed at the start of each game session.

# 🙌 Acknowledgments
Thanks to the Python community for inspiration and guidance on building projects with turtle. 
Special thanks to anyone who tries and improves this game!
