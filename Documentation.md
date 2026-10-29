# Game Mechanic

---

**The player's movement controls both their character and enemy.**

In this game, as the player moves their character, the enemy will move in the opposite direction. For example, if the player moves to the right, the enemy will move to the left. Additionally, when the player jumps, the enemy jumps too. Gravity still applies to both of them.

# Objective Statement

---

**How does controlling two characters moving in opposite directions affect a player's ability to navigate a platforming puzzle?**

The objective of this prototype is to explore how inverting the enemy's movement with the player's inputs can transform traditional platforming into a puzzle-solving experience. Players will need to keep in mind how movement affects both characters, their own character and the enemy. They are encouraged by the game to consider careful positioning, timing, and jumps to reach the end of the level without colliding with the enemy.

With this prototype, we hope to determine whether this mechanic will encourage players to think strategically, rather than simply progressing through each level as if it were a conventional platformer.

# Design Rationale

---

The vision for this prototype is a 2D platformer game with puzzle elements. The player must navigate towards the end of each level without colliding with the enemy, and dying. Unlike traditional platformers, the player's movement will also affect the enemy, which moves in the opposite direction. Players will be encouraged to use critical thinking to plan their movements for how to avoid the enemy while making it to the end. Additional skills regarding their ability to move through levels will come into play as the player moves and jumps across platforms.

In future levels, the game may feature additional obstacles to make levels harder, as well as progressing difficulty in each level. For example, the first level starts easy as an introduction to the mechanics, then each level gets more challenging with more platforms or different enemy starting positions.

Our game is innovative in which it challenges the classic platformer by adding a puzzle element that players must overcome to reach the end. Players need to use logic in addition to being able to complete any movement challenges.

# Asset Register

---
## FREE Fantasy Platformer Asset Pack

**Creator:** Cryptid Pixel  
**Source:**  
[https://cryptid-pixel.itch.io/free-fantasy-platformer-asset-pack](https://cryptid-pixel.itch.io/free-fantasy-platformer-asset-pack)  
[https://kairosolo.itch.io/simple-pixel-art-spikes](https://kairosolo.itch.io/simple-pixel-art-spikes)  
**Accessed:** September 2026

### Project Use

Assets from this pack are being used to establish the visual style of the prototype, including:

- Player character artwork
- Platform tiles
- Dungeon/environment tiles
- Environmental decorations
- Hazards

### Modifications

Original sprites have been imported and configured for use within Unity.  
Additional modifications will be documented as development continues.

# Core Gameplay

---
### Controls:

- 'A' to move left
- 'D' to move right
- 'SPACEBAR' to jump

### Core Loop:

Progress through the levels by avoiding the enemy that will mimic movement opposite to the player's. Walk, jump, and navigate through each level while avoiding the enemy to reach the end.

# Characters

---
### Player Character

The player character is the character directly controlled by the player. Their movement is the primary input through which the player interacts with the environment and influences the enemy's position.

The player must use movement and jumping to navigate platforms, avoid hazards, and reach the end of each level. The visual design for this character is a knight. With this, players can easily identify who their character is during gameplay.

### Enemy Character

The enemy character is represented by a skeleton and acts as both an obstacle and central part of the puzzle mechanic. Instead of following the player independently, its movement is linked to the player's inputs and it will move in the opposite direction. It also jumps when the player jumps.

This means that the enemy is not an opponent the player can outrun, this character's behaviour is connected to the player's actions. Therefore, its position must be considered when planning movement through each level, so the player can progress without colliding with it.

The skeleton's visual design should help players differentiate it from the knight player character, while also making it recognizable as a threat to the player.

# Interface

---

Currently, there is no developed interface for this prototype, but in future iterations, should the game receive further development, it will include a retry button, start button, a game-over screen, settings menu, and potentially stage selection.

Primary player inputs are movement and jumping. Players should not experience much trouble with controls, so long as they are known or able to be identified (currently, controls are listed in our prototype's README and under Core Gameplay — Controls in this document).

# Audio

---

Audio is not currently a developed focus of this prototype, but future iterations could introduce sound effects for events like jumping, landing, or colliding with hazards, and completing a level. 

A sound track may also be considered in future iterations, with background music to better establish atmosphere, provided it does not distract from the central gameplay and puzzle solving.