# Enemy Defense Game (Unity)

## Overview
Enemy Defense Game is a simple 2D game developed in Unity. The player must protect the base by clicking on enemies before they reach it. The game features multiple enemy types, score tracking, random enemy spawning, a special shockwave cooldown ability to attack on enemies and a game over screen with a play again button.

## Features
- 2D Unity game
- Multiple enemy types
- Random enemy spawning
- Click-to-destroy enemies
- Live score display
- Final score on Game Over screen
- Play Again button
- Simple and clean UI

## Built With
- Unity
- C#
- TextMeshPro

## Gameplay
1. Enemies spawn from the top of the screen.
2. The player clicks(left click on mouse) enemies to destroy them.
3. Player can activate a ShockWave(Right click on mouse).
4. ShockWave destroys all enemies spawnning in it's way(It has preset cooldown time).
5. Each destroyed enemy increases the score.
6. Enemy attacks reduces the Base Health.
7. Once the Base Health reaches zero, the game immediately ends.
8. And a Game Over screen is displayed
9. The final score is displayed, and the player can restart the game.

## Project Structure
```
Assets/
├── Scripts/
├── Prefabs/
├── Scenes/
├── Sprites/
├── UI/
└── Audio/
```

## How to Run
1. Clone this repository.
2. Open the project in Unity Hub.
3. Open the Main Scene.
4. Press Play to start the game.

## Future Improvements
- Sound effects and background music
- Multiple levels
- Power-ups
- High score saving
- Difficulty levels
