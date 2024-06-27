# SpaceX Starship Lander Game

## Overview

Enhanced SpaceX Starship Lander is an exciting browser-based game where players control a SpaceX Starship, attempting to land it safely on a designated landing pad. Navigate through increasingly challenging levels, avoid obstacles, manage your fuel, and collect bonus items to achieve the highest score possible!

## Features

- **Progressive Difficulty**: Each level introduces more obstacles, providing an increasing challenge.
- **Lives System**: Players have three lives, allowing for multiple attempts per game.
- **Bonus Items**: 
  - Fuel canisters to replenish your starship's fuel
  - Score boosters to increase your point total
- **Realistic Physics**: Experience smooth rotation and movement based on thrust and gravity.
- **Dynamic Obstacles**: Navigate around randomly placed obstacles in each level.
- **Responsive Controls**: Precise control over your starship's main engine and RCS thrusters.

## How to Play

1. **Launch the Game**: Open the HTML file in a web browser to start the game.
2. **Controls**:
   - Use the **Up Arrow** or **Space Bar** to fire the main engine and counteract gravity.
   - Use the **Left** and **Right Arrow** keys to control horizontal movement and rotation.
3. **Objective**: Land the starship on the yellow-marked landing pad to complete each level.
4. **Landing Criteria**: 
   - Land with a slow vertical speed.
   - Ensure the starship is mostly upright (minimal rotation).
   - Center the starship on the landing pad.
5. **Collect Bonuses**:
   - Green orbs replenish 20% of your fuel.
   - Gold orbs award 500 bonus points.
6. **Avoid Obstacles**: Colliding with brown obstacles will result in a crash.
7. **Manage Fuel**: Keep an eye on your fuel gauge. Running out of fuel will end your attempt.

## Game States

- **Playing**: Actively controlling the starship.
- **Landed**: Successfully completed a level. Press Space to continue to the next level.
- **Crashed**: Collided with an obstacle or landed too hard. Press Space to retry if you have remaining lives.
- **Out of Fuel**: Ran out of fuel before landing. Press Space to retry if you have remaining lives.
- **Game Over**: Out of lives. Press R to restart the game from the beginning.

## Scoring

- Gain points for each second of flight time.
- Earn 1000 points multiplied by the current level for successful landings.
- Collect gold orbs for 500 bonus points each.
- Aim for the highest score across all your completed levels!

## Development

This game is developed using HTML5 Canvas and JavaScript. It's designed to run directly in web browsers without the need for additional plugins or installations.

### Future Enhancements

- Multiple spacecraft types with unique characteristics
- Power-ups with special abilities
- Global leaderboard
- Sound effects and background music
- Mobile touch controls

## Credits

Developed by Hayden. Email: contact+haydenk@pixelverse.tech.
For Hack Club Arcade.