# Pong_Game
This is a modern remake of the classic Pong arcade game—built completely in Python using the turtle graphics library. Two paddles, a bouncing ball, score tracking, and smooth movement... all wrapped into a clean, beginner-friendly Python project.

Whether you're looking to play a quick game or understand the inner workings of collision detection and game loops, this one's for you.

🗂️ Project Breakdown
Here’s how the project is structured:

main.py – Runs the game. Sets up the window, listens for key presses, and keeps the game loop running.

paddle.py – Contains the Paddle class, which handles player movement.

ball.py – Handles ball movement, bouncing logic, and reset behavior.

scoreboard.py – Tracks and displays the score for both players.

💡 Python Concepts Used
Here’s a rundown of the key Python features and topics this project covers:

🔁 Core Concepts
Functions: Breaks up the game into small, reusable logic blocks.

Conditionals: Used to detect paddle collisions and score boundaries.

Loops: A while loop drives the main game flow.

🧱 Object-Oriented Programming
Classes: Everything from paddles to the scoreboard is handled with classes, making the code modular and easy to extend.

📦 Standard & Built-in Libraries
time: Used to control the frame rate and pacing of the game.

turtle: Powers the visuals, key inputs, and drawing the game elements.

🔧 Extras
Method calls: All game elements interact using custom methods like .move_up(), .bounce_x(), .increase_speed(), etc.

Module imports: Clean separation of logic across files, keeping things tidy and readable.

