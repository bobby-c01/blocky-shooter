# BLOCKY SHOOTER

---

## Description

BLOCKY SHOOTER is a 2D shooter game built using Pygame and Pymunk. Players control two blocky characters on a playing field, and each can shoot projectiles at the other. The objective is to reduce the opponent's health to zero by hitting them with projectiles. The game features simple collision detection, player movement, and projectile mechanics. This is game is designed to be local multiplayer and playing with a friend on the same device.

![Blocky-Shooter](https://raw.githubusercontent.com/bobby-c01/blocky-shooter/3538577f25e130fead4d205f8e0e75c5faf89fb9/blocky-shooter.png)

---

## Features

- Two-player game
- Player movement and shooting
- Health tracking for each player
- Collision detection using Pymunk
- Boundaries to keep players within the screen

---

## Requirements

- Python 3.0 or higher
- Pygame
- Pymunk

---

## Game Mechanics

- Each player starts with 3 health points.
- Players 1 can move left and right and aim their projectiles up and down, they fire with l
- Player 2 moves using a and d and aims their projectiles using w and s, they fire with g
- Projectiles are shot with a specific speed and angle.
- When a projectile hits a player, the player's health decreases by 1.
- The game ends when one player's health reaches zero.

