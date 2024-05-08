# Angry Birds Clone Game

The **Angry Birds Clone Game** project is a physics-based game created using p5.js and Matter.js libraries, inspired by the classic Angry Birds game. The objective of the game is to launch birds from a slingshot to knock down all boxes within a limited time frame.

## Project Overview

In this Angry Birds clone game, you will find the following key elements and functionalities:

- **Physics Engine (Matter.js)**:
  - Utilizes Matter.js to simulate physics interactions between game elements such as birds, boxes, and ground.
  
- **Gameplay Mechanics**:
  - Launch birds from a slingshot by adjusting the angle and velocity using the keyboard.
  - Knock down boxes by colliding birds with them.
  - Use a countdown timer (60 seconds) to track the remaining time for completing the game objectives.
  
- **Interactive Controls**:
  - Press 'r' to reset the slingshot.
  - Press 'b' to create a new bird for launching.

- **Visual Feedback**:
  - Displays a GAME OVER message with the corresponding outcome (win or lose) based on game conditions (e.g., timer expiration or successful box removal).

## Development Details

The game leverages the following concepts and techniques:

- **Collision Detection**:
  - Detects collisions between birds and boxes to determine game progress and outcomes.

- **Physics Simulation**:
  - Uses Matter.js physics engine to simulate realistic object interactions (e.g., gravity, collisions).

- **User Interaction**:
  - Implements keyboard controls for adjusting the slingshot angle and launching birds.

- **Countdown Timer**:
  - Integrates a countdown timer mechanism to create time-limited gameplay.

## Gameplay Instructions

1. **Launch Birds**:
   - Adjust the angle of the slingshot using the LEFT and RIGHT arrow keys.
   - Press 'b' to create a new bird for launching.
   
2. **Reset Slingshot**:
   - Press 'r' to reset the slingshot if needed during gameplay.

3. **Objective**:
   - Knock down all boxes within 60 seconds to win the game.
   - If the timer runs out before all boxes are removed, the game ends with a "GAME OVER" message.

## Conclusion

The Angry Birds Clone Game project provides a fun and interactive implementation of physics-based gameplay using p5.js and Matter.js libraries. Players can enjoy launching birds and strategizing to complete the game objectives within the given time limit.

For further enhancements, I will consider adding additional game elements, levels, or graphical improvements to enrich the gaming experience.
