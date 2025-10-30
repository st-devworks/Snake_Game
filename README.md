🐍 Snake Game
A simple Snake Game built using Python and the turtle graphics module. This project is a fun and beginner-friendly way to understand the basics of game loops, event handling, and object-oriented programming in Python.

✨ Features
Classic Gameplay: Eat the food to grow the snake and score points.

Collision Detection: Game over when the snake hits the wall or its own tail.

Score Tracking: Displayed score and high score.

Simple Graphics: Utilizes the built-in turtle module for drawing.

🛠️ Prerequisites

Python 3.x

turtle module (comes standard with most Python installations)

🐍 Snake Game
A simple Snake Game built using Python and the turtle graphics module. This project is a fun and beginner-friendly way to understand the basics of game loops, event handling, and object-oriented programming in Python.

✨ Features
Classic Gameplay: Eat the food to grow the snake and score points.

Collision Detection: Game over when the snake hits the wall or its own tail.

Score Tracking: Displayed score and high score.

Simple Graphics: Utilizes the built-in turtle module for drawing.

🛠️ Prerequisites
Python 3.x

turtle module (comes standard with most Python installations)

🎮 How to Run

Clone this repository:
git clone https://github.com/st-devworks/Snake_Game.git

Navigate to the project directory:
cd Snake_Game

Run the game script:
python snake_game.py

Key                                 Action
Up Arrow                          Move snake Up
Down Arrow                        Move snake Down
Left Arrow                        Move snake Left
Right Arrow                       Move snake Right

💡 How It Works (Brief Overview)

The game uses several key components:

Screen Setup: Initializes the game window using turtle.Screen.

Snake Head: A turtle object for the snake's head, which handles movement and direction.

Food: A simple turtle object that teleports to a new random location when eaten.

Scoreboard: A separate turtle object used to display the current score and high score.

Game Loop: The core of the game, which constantly updates the screen, moves the snake, checks for collisions, and updates the score.

Key Bindings: Uses screen.listen() and screen.onkey() to register keyboard input for controlling the snake's direction.

🧑‍💻 Author
st-devworks




