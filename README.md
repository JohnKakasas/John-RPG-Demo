# Unreal Engine 5 RPG Project

A third-person RPG prototype built using **Unreal Engine 5**.  
The project demonstrates the development of core RPG systems including **combat mechanics, player progression, AI enemies, quest systems, dynamic environments, and save/load functionality**.

The goal of this project is to create a structured RPG framework using **Blueprint-based development**, while exploring the capabilities of Unreal Engine 5 for modern game design.

---

## Overview

This project focuses on designing and implementing a functional RPG gameplay system in Unreal Engine 5.

Main objectives include:

- Implementing real-time combat mechanics
- Creating a character progression system
- Building AI-driven enemies
- Designing quest and dialogue systems
- Developing an open-world environment
- Implementing a dynamic day-night cycle
- Creating save and load functionality
- Integrating UI, animations, and visual effects

---

## Features

### Player Movement
- Locomotion system
- Blendspaces
- Crouching
- Procedural leaning
- Vaulting using motion warping
- Climbing mechanics
- Ledge climbing and mantling
- Swimming mechanics

### Combat System
- Real-time melee combat
- Sword trace damage detection
- Hit reaction system
- Target lock-on
- Dodge roll mechanics
- Blocking and block damage
- Bow and arrow system
- Stamina-based combat actions

### Player Progression
- Health and stamina system
- Experience (XP) system
- Leveling system
- Level-up animations and effects

### Equipment and Inventory
- Equipment system
- Equipment UI with slots
- Shield and bow equipment
- Armor system
- Inventory management

### AI System
- Behavior Trees for enemy AI
- Patrol system
- Detection and chase mechanics
- Melee enemy combat
- Boss AI behavior
- Civilian AI
- Animal AI
- AI distraction mechanics

### Quest System
- Quest data structure
- Active quest selection
- Quest objectives
- Dialogue system
- Quest completion logic

### World and Environment
- Open-world level setup
- Oasis environment
- Enemy fortress area
- Market towns
- Area entry notifications
- Dynamic day-night cycle
- Environmental effects and atmosphere

### UI and Audio
- Main menu
- Pause menu
- UI sound effects
- Environmental sounds
- HUD for player statistics

### Animation and Visual Effects
- Foot IK system
- Collision detection during uncrouch
- Head look-at system using Control Rig
- Niagara particle effects
- Level-up visual effects

### Save and Load System
- Save game system
- Multiple save slots
- Player stat persistence
- Inventory persistence
- Quest progress persistence
- Day-time persistence

### Cinematics and Gameplay Flow
- Intro cinematic scene
- Death and respawn system
- Controller support
- Character mesh customization

---

## Technologies Used

- Unreal Engine 5.3
- Blueprint visual scripting
- Optional C++ for optimization
- Behavior Trees for AI
- Niagara for particle effects
- Lumen for dynamic lighting
- Nanite for high-detail geometry
- World Partition for large environments

---

## Development Tools

### Engine and Programming
- Unreal Engine 5.3.1
- Visual Studio Code

### Design Tools
- Blender 3.6
- Adobe Photoshop 2023

### Audio Tools
- Audacity 3.4.2

### Unreal Plugins
- Water Plugin
- Landmass Plugin

---

## Development Hardware

Operating System: Windows 10 Pro 64-bit  
CPU: Intel Core i7-10700K  
RAM: 32 GB DDR4  
GPU: NVIDIA GeForce RTX 3070  
Storage: 1 TB SSD

---

## Assets

Assets used in the project were sourced from the following platforms:

- Unreal Marketplace
- Quixel Megascans
- Mixamo animations
- Freesound audio library

These assets were customized and integrated into the Unreal Engine environment.

---

## Core Systems

### Combat System
The combat system is built around **real-time gameplay**, allowing players to attack, block, dodge, and use ranged weapons. Damage is calculated based on player statistics and enemy attributes.

### Save System
A custom **SaveGame Blueprint** stores:

- Player position
- Health values
- XP and level
- Inventory items
- Quest progress
- Time of day

### Day-Night Cycle
The environment includes a dynamic day-night cycle using:

- Directional light for the sun
- Sky system for atmosphere
- Fog adjustments
- Real-time lighting using Lumen

### AI Behavior
Enemy AI uses **Blueprint logic and Behavior Trees** to manage:

- Patrol routes
- Detection
- Combat engagement
- Boss encounters

---

## Optimization

Performance improvements include:

- Level of Detail (LOD)
- World Partition streaming
- Occlusion culling
- Asset optimization
- Continuous playtesting and debugging

---

## Future Improvements

Potential improvements include:

- Expanded combat abilities
- Larger skill trees
- Advanced enemy AI
- More quests and story content
- Larger open-world environments
- Additional enemy types and bosses
- Auto-save functionality
- Expanded NPC interaction systems

---

## Project Goals

This project aims to:

- Build a functional RPG gameplay framework
- Explore Blueprint-based development workflows
- Combine gameplay systems with visual storytelling
- Create a scalable project structure
- Deliver an immersive player experience

---

## How to Run the Project

1. Clone the repository
2. Open the `.uproject` file using **Unreal Engine 5.3 or later**
3. Enable required plugins if prompted
4. Compile project files if necessary
5. Launch the project

---



## References

- Unreal Engine Documentation
- Quixel Megascans
- Unreal Marketplace
- Game design literature and resources

---

## Notes

This project serves as an example of developing a **complete RPG gameplay framework in Unreal Engine 5**, combining gameplay systems, AI, environment design, and visual effects.
