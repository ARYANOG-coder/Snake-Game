# Snake Game

A simple Snake Game built using Python and Pygame.

## 🎮 Overview

This project implements the classic Snake game where the player controls a snake to eat food, growing in size while avoiding collisions with walls or itself.

## 🚀 Features

* Classic snake movement using arrow keys
* Score tracking
* Game over screen with replay option
* Randomly generated food
* Smooth grid-based movement

## 🛠 Requirements

* Python 3.x
* Pygame library

Install Pygame:

bash
pip install pygame


## ▶ How to Run

1. Clone or download this repository
2. Navigate to the project folder
3. Run:

bash
python snake_game.py


## 📁 Project Structure


snake_game.py   # Main game file


## 🎯 Controls

| Key            | Action                    |
| -------------- | ------------------------- |
| ⬆ Up Arrow    | Move Up                   |
| ⬇ Down Arrow  | Move Down                 |
| ⬅ Left Arrow  | Move Left                 |
| ➡ Right Arrow | Move Right                |
| C              | Play Again (after losing) |
| Q              | Quit (after losing)       |

## 📝 Game Logic Summary

* The snake moves in a grid, one block at a time
* Eating food increases the snake's length
* The game ends when:

  * The snake hits a wall
  * The snake collides with itself

## 📌 Customization

You can modify key parameters in snake_game.py:

* Display size (dis_width, dis_height)
* Snake speed (snake_speed)
* Snake block size (snake_block)
* Colors


## 🧑‍💻 Author

*Aryan* — Developer of this Snake Game
