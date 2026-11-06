# Sonic Classic Heroes — 2D Platformer

A 2D platformer inspired by the classic Sonic games, developed in **C++ using SFML** as a university project. The game is organised around a game controller, player/character classes, level classes, enemies, collectibles, power-ups, menus, and scoring.

## Features

- 2D platforming with horizontal movement and jumping.
- Gravity and player/world collision handling.
- Animated character states and sprite-based rendering.
- Multiple playable characters, including Sonic, Tails, and Knuckles.
- Multiple levels and a boss-level component.
- Enemies with separate behaviours, including Bee-bot, Crabmeat, Moto Bug, and Bat Brain.
- Collectibles such as rings.
- Power-ups and extra-life mechanics.
- Menu, scoring, and game-state management.
- Sound effects and background music.

## Technology Stack

- C++
- SFML (Graphics, Window, and Audio)
- Object-oriented programming
- Sprite animation and collision detection
- Game-loop and state-management concepts

## Project Structure

The game source is located in the `Sonic Classic Heroes/` directory.

| Files / classes | Responsibility |
|---|---|
| `Game.*` | Main game controller and game loop |
| `Player.*`, `Sonic.*`, `Tails.*`, `knuckles.*` | Player and playable-character logic |
| `levels.*`, `level1.*`, `level2.*`, `level3.*`, `boss_level.*` | Level structure and progression |
| `Enemies.*`, `Bee_bot.*`, `crabMeat.*`, `moto_bug.*`, `Bat_Brain.*`, `eggStinger.*` | Enemy classes and behaviours |
| `collectibles.*`, `rings.*`, `power_ups.*`, `extra_life.*` | Collectibles and power-ups |
| `Menu.*`, `Scorings.*` | Menus and scoring |
| `Music/`, asset folders | Audio, sprites, and game resources |

## Requirements

- A C++ compiler
- SFML development libraries (Graphics, Window, and Audio)
- The asset folders included in the repository

## Build and Run

The uploaded repository snapshot contains the C++ source and assets but does not include a portable build script or a checked-in Visual Studio solution/project file.

To build it locally:

1. Install SFML for your compiler and operating system.
2. Create or configure an IDE project that includes the `.cpp` files in `Sonic Classic Heroes/`.
3. Configure the SFML include and library paths.
4. Link the SFML graphics, window, system, and audio libraries.
5. Preserve the relative asset folder structure when running the executable.

Because the source uses relative asset paths, run the game with a working directory that can resolve the bundled resources.

## Controls

Check the in-game menu or source configuration for the exact key bindings. They may vary by character or game state.

## Notes

This repository is a university game-development project. A reproducible CMake or IDE build configuration would make setup easier for other contributors.

## Repository

[ArslanFeroz/Sonic-](https://github.com/ArslanFeroz/Sonic-)
