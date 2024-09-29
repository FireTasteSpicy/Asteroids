# Asteroids Game
This project is a follow-through of Boot.dev's course on Asteroids, demonstrating the implementation of Object-Oriented Programming (OOP) concepts in Python. The game is a recreation of the classic Asteroids arcade game, where players control a spaceship to shoot and destroy incoming asteroids.

## Features
Player Control: Move and rotate the spaceship to navigate through the asteroid field.
Asteroid Field: Randomly generated asteroids with varying sizes and speeds.
Shooting Mechanism: The player can shoot projectiles to break apart asteroids.
Object-Oriented Design: Classes such as Player, Asteroid, AsteroidField, and Shot are used to encapsulate game logic and state.
Simple Physics: Basic collision detection and movement mechanics based on velocity and direction.

## Files Overview
main.py: The entry point for running the game.
player.py: Defines the behaviour and attributes of the player's spaceship.
asteroid.py: Handles individual asteroid objects.
asteroidfield.py: Manages a collection of asteroids on the screen.
shot.py: Manages the player's projectiles.
circleshape.py: Defines circular shapes used in the game for collisions.
constants.py: Contains constant values such as screen dimensions and speed settings.

## Requirements
To install the dependencies, run:
```
pip install -r requirements.txt
```
## How to Run
You can start the game by executing the main.py file:
```
python main.py
```

## Purpose
This project serves as an educational exercise to reinforce concepts of OOP while building a simple, yet interactive game.