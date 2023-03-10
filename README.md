# Esacape_The_House


Escape the House

This is a text-based game where the player must escape a house by finding keys and unlocking doors. The player starts in a game room and must explore the house to find the keys to unlock the doors to escape.

How to Play

Prerequisites
This game requires the following python packages to be installed:
pyttsx3
matplotlib
To install them, run the following command:

pip install pyttsx3 matplotlib

Run the Game

To run the game, run the escape_game.py file using Python.
The player will start in the game room and must explore the house to find the keys to unlock the doors to escape.
When the game starts, the player will hear a message that sets the scene and explains the goal of the game.


How to Win

The goal of the game is to escape the house by finding the keys to unlock the doors. Once the player has collected all of the keys and unlocked all of the doors, they will be able to escape the house and win the game.





How to Lose

If the player examines an explosive item, they will lose the game. The game will also end if the player does not escape the house before the time runs out.

Game Design

Overview
The game is designed as a text-based adventure game where the player must explore a house to find keys to unlock doors to escape. The game is divided into rooms, with each room containing items and doors that lead to other rooms. The player starts in the game room and must explore the house to find the keys to unlock the doors to escape.

Game State
The state of the game is stored in a Python dictionary. When a new game starts, a copy of this dictionary is made and used to store gameplay state. This way, the game can be replayed multiple times.

Objects
Objects are represented as Python dictionaries with a name, type, and optional target. The type is used to determine how the object can be used, while the target is used to determine what the object can be used on.


Rooms
Rooms are represented as Python dictionaries with a name and type. Rooms contain items and doors that lead to other rooms.

Doors
Doors are represented as Python dictionaries with a name, type, and target. The type is used to determine what kind of door it is, while the target is used to determine what room the door leads to.

