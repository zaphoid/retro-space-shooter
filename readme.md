# Retro Space Shooter

![Retro Space Shooter](assets/screenshot.png)
*Replace with an actual screenshot of the game.*

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Game Mechanics](#game-mechanics)
- [Controls](#controls)
- [Getting Started](#getting-started)
- [Credits](#credits)

## Introduction

**Retro Space Shooter** is a classic-style space shooter game developed using [Phaser 3](https://phaser.io/). This game is built as a **flat file** with no modules, making it simple and straightforward to understand and modify. The game leverages sprite-based graphics and provides an engaging experience with various enemies, asteroids, and power-ups.

## Project Structure

The entire game is contained within a single HTML file, utilizing Phaser 3 via a CDN. Here's an overview of the project structure:


- **index.html:** Contains all the HTML, CSS, and JavaScript code for the game.
- **assets/:** Directory holding all sprite images and sound files used in the game.

## Game Mechanics

### **Player**
- **Movement:** The player controls a spaceship that can rotate left and right and thrust forward.
- **Shooting:** Pressing the spacebar fires projectiles (bullets) in the direction the spaceship is facing.
- **Health & Shields:** The player has a health system and can activate shields to absorb damage from collisions and enemy attacks.
- **Power-Ups:** Collect various power-ups to gain temporary abilities like increased fire rate, invisibility, and teleportation.

### **Enemies**
- **Behavior:** Enemies track and move towards the player's spaceship unless the player is invisible.
- **Combat:** Enemies can be destroyed by bullets, awarding points to the player.

### **Asteroids**
- **Sizes:** Asteroids come in large, medium, and small sizes, each with different health points.
- **Splitting Mechanism:** Destroying a large asteroid splits it into smaller ones, increasing the game's difficulty.

### **Power-Ups**
- **Types:**
  - **Shield:** Grants temporary invincibility.
  - **Fire Rate Booster:** Increases the player's firing speed.
  - **Invisibility Cloak:** Makes the player invisible to enemies for a short duration.
  - **Warp:** Teleports the player to a safe location on the map.
- **Spawning:** Power-ups spawn at predefined locations on the map and can be collected by navigating the spaceship over them.

### **Environmental Hazards**
- **Dust Storms & Fog:** Represented by semi-transparent overlays, these hazards can affect visibility and movement, adding an extra layer of challenge.

### **Levels & Progression**
- **Level Up:** Progressing through levels increases the number of enemies and asteroids, enhancing the game's difficulty.
- **Score System:** Players earn points by destroying enemies and asteroids, with the score displayed on the UI.

## Controls

Mastering the controls is key to surviving and achieving high scores in **Retro Space Shooter**. Here's a breakdown of the actions and corresponding controls:

### **Movement Controls**
- **W Key:**  
  **Action:** Thrust Forward  
  **Description:** Accelerates the spaceship in the direction it is currently facing, allowing the player to move around the map.

- **A Key:**  
  **Action:** Rotate Left  
  **Description:** Rotates the spaceship counterclockwise, changing its facing direction.

- **D Key:**  
  **Action:** Rotate Right  
  **Description:** Rotates the spaceship clockwise, altering its facing direction.

### **Shooting Control**
- **Spacebar:**  
  **Action:** Fire Projectiles  
  **Description:** Fires bullets from the spaceship in the direction it is facing. The firing rate can be increased by collecting fire rate booster power-ups.

### **Power-Up Controls**
- **Power-Ups are Activated Automatically:**  
  **Description:** When a power-up is collected, its effect is activated automatically for a limited duration. No additional key presses are required.

### **Game Control**
- **Starting the Game:**  
  **Action:** Press Spacebar  
  **Description:** On the start screen, pressing the spacebar begins the game.

- **Restarting After Game Over:**  
  **Action:** Press Spacebar  
  **Description:** After the game ends, pressing the spacebar restarts the game.

### **Summary of Controls**

| **Key**       | **Action**               | **Description**                                              |
|---------------|--------------------------|--------------------------------------------------------------|
| **W**         | Thrust Forward           | Accelerate the spaceship forward.                            |
| **A**         | Rotate Left              | Rotate the spaceship counterclockwise.                       |
| **D**         | Rotate Right             | Rotate the spaceship clockwise.                              |
| **Spacebar**  | Fire Projectiles / Start Game / Restart | Fire bullets, start the game from the start screen, or restart after game over. |

## Getting Started

Follow these steps to run and play **Retro Space Shooter**:

1. **Clone or Download the Repository:**
   - Clone the repository using Git:
     ```bash
     git clone https://github.com/yourusername/retro-space-shooter.git
     ```
   - Or download the ZIP file and extract it to your desired location.

2. **Ensure Assets are Present:**
   - Verify that the `assets/` folder contains all necessary images and sound files as outlined in the [Project Structure](#project-structure) section.

3. **Open the Game:**
   - Navigate to the project directory.
   - Open the `index.html` file in your preferred web browser (e.g., Chrome, Firefox).

4. **Start Playing:**
   - On the start screen, press the **Spacebar** to begin the game.
   - Use the **W**, **A**, **D**, and **Spacebar** keys to control your spaceship and engage enemies.

## Credits

- **Phaser 3:** [https://phaser.io/](https://phaser.io/)  
  The game is built using the Phaser 3 framework.

- **Assets:**  
  - **Images:** Player, enemies, asteroids, and power-up sprites.
  - **Sounds:** Sound effects for shooting, explosions, power-ups, and collisions.

- **Developed By:**  
  - [Your Name](https://github.com/yourusername)

## License

[MIT License](LICENSE)

