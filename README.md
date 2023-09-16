# Turtle Crossing Game 🐢🚗

Welcome to the Turtle Crossing Game, where quick reflexes and a knack for dodging traffic can make you a turtle hero! In this thrilling game, you take on the role of a brave turtle trying to cross a busy road safely. Watch out for speeding cars and make it to the other side to earn points and level up.

## Table of Contents

- [OOP Principles 🧰](#oop-principles-)
- [How to Play 🎮](#how-to-play-)
- [Installation 🚀](#installation-)
- [Dependencies 📦](#dependencies-)

## OOP Principles 🧰

The Turtle Crossing Game embraces Object-Oriented Programming (OOP) to deliver a seamless gaming experience. Every game element is a meticulously crafted object, contributing to the game's dynamic nature.

### Player Object 🐢

The `Player` object, our game's protagonist, handles user input and turtle movement. When you press the **Up Arrow Key**, the `Player` object's `move_forward()` method calculates the turtle's new position and moves it accordingly.

### CarManager Object 🚗

The `CarManager` object manages traffic. It dynamically generates and moves cars across the screen. The `create_cars()` method spawns cars randomly, while the `speed_up()` method increases the car speed as the game progresses.

### Scoreboard Object 🏆

The trusty `Scoreboard` object keeps track of your progress. It boasts a `level_up()` method that increments the level and displays it on the screen. In the event of a collision, the `game_over()` method gracefully ends the game.

### Screen Object 🌐

Although not explicitly mentioned, the `Screen` object plays a pivotal role. It renders game elements, updates the screen, and handles user input. `screen.update()` ensures a smooth display, while `screen.listen()` and `screen.onkey()` enable user interaction.

### Interaction Flow 💡

Here's how these objects collaborate during gameplay:

1. The `Player` object responds to user input, moving the turtle when the **Up Arrow Key** is pressed.

2. The `CarManager` object continuously generates and moves cars, simulating traffic.

3. Upon reaching the finish line, the `Player` object triggers the `level_up()` method in the `Scoreboard` object.

4. The `CarManager` object steps up the game's difficulty with increased speed.

5. If the `Player` object detects a collision with a car, the `Scoreboard` object displays "GAME OVER."

The Turtle Crossing Game is a testament to the power of structured code, showcasing OOP principles and delivering an engaging and enjoyable gaming experience. Dive in, and help our turtle hero cross the road safely! 🚀🐍

## How to Play 🎮

- Control the turtle using the **Up Arrow Key** to move forward.
- Navigate the turtle across the road, avoiding oncoming cars.
- Reach the other side to level up and earn points.
- Watch out for speeding cars; a collision means "GAME OVER."

## Installation 🚀

To play the Turtle Crossing Game, follow these steps:

1. Clone this repository to your local machine.

2. Make sure you have Python installed.

3. Open your terminal and navigate to the project directory.

4. Run the game by executing the `turtle_crossing_game.py` file.

## Dependencies 📦

This game requires Python and the Turtle graphics library. Python can be downloaded [here](https://www.python.org/downloads/).

The Turtle graphics library is included in Python's standard library, so no additional installation is needed.
