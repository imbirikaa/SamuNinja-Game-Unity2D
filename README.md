# SamuNinja

## What is the Game?

**SamuNinja** is a thrilling 2D game where you control a player character who defends against enemies coming from both the left and right sides. The player's **health starts at 100**, but every hit from an enemy reduces the health by **20 points**. Survive as long as you can while avoiding enemy attacks and utilizing power-ups!

---

## Game Information

### **Controls**:
- **Left Arrow Key**: Move left
- **Right Arrow Key**: Move right
- **Up Arrow Key**: Jump
- **Space Key**: Attack
- **B Key**: Throw Arrows

### **Gameplay Mechanics**:
1. **Health Recovery**: When the player collects an **apple**, their health resets to **100**.
2. **Special Ability**: When the player collects a **dragon fruit**, they gain the ability to throw arrows by pressing the **B key**.

### **Random Elements**:
- Apples and dragon fruits spawn randomly on the scene, giving the player opportunities to recover health or unlock new abilities.

---

## How to Play
1. Use the arrow keys to move and jump to avoid enemies.
2. Press **Space** to attack enemies and defend yourself.
3. Look out for power-ups:
   - **Apple**: Restores your health.
   - **Dragon Fruit**: Grants you the ability to throw knives.

---
## Try the Game
Enjoy playing **SamuNinja**, and may your reflexes guide you to victory!

<a href="https://imbirika.itch.io/samuninja" target="_blank">Play The Game</a>



## Team Members and Contributions

### **Group Member #1 ALI IMBIRIKA - 21360859217 **
- **Player Movement**: Handles horizontal movement of the player.  
  - Script: `PlayerMovement`, Line 47
- **Ground Contact Check**: Checks if the player is in contact with the ground.  
  - Script: `PlayerMovement`, Line 103
- **Interaction and Attack on Enemy**: Manages interactions and attacks on Enemy while staying in range.  
  - Script: `PlayerMovement`, Line 110
- **Player Attack**: Executes player attack actions.  
  - Script: `PlayerMovement`, Line 137
- **Enemy Movement Towards Player**: Moves enemies toward the player's position.  
  - Script: `EnemyControls`, Line 46
- **Sprite Flipping**: Changes the enemy's direction based on movement.  
  - Script: `EnemyControls`, Line 60
- **Enemy Attack**: Executes the enemy's attack while staying in range of the player.  
  - Script: `EnemyControls`, Line 88

### **Group Member #2 MUAZ RADWAN - 22360859370 **
- **Arrow Shooting**: Controls the player's arrow shooting mechanic.  
  - Script: `PlayerMovement`, Line 194
- **Health Loss**: Reduces the player's health when damaged.  
  - Script: `PlayerMovement`, Line 154
- **Player Death**: Executes the logic when the player dies.  
  - Script: `PlayerMovement`, Line 174
- **Health Restoration**: Restores the player's health upon collecting specific items.  
  - Script: `Consume`, Line 27
- **Enemy Spawning**: Spawns enemies at intervals.  
  - Script: `Spawn`, Line 31
- **Apple Spawning**: Spawns apples at intervals.  
  - Script: `Spawn`, Line 49
- **Dragon Fruit Spawning**: Spawns dragon fruits at intervals.  
  - Script: `Spawn`, Line 67
- **Stop Spawning**: Stops spawning objects under certain conditions.  
  - Script: `Spawn`, Line 85
