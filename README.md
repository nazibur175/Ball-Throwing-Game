# Ball Throwing Game

## 1.1. Project Overview

This project involves the development of a simple yet engaging ball-throwing game using Unity. The player interacts with the game by clicking and dragging to throw a ball toward a target. The goal is to score points by hitting the target, and the game automatically ends after 10 attempts. Each throw's trajectory is determined by the player's input, simulating a real-world throwing experience using Unity's physics engine.

The game features multiple game objects such as the ball, ground, stand, and target, all of which are tagged and organized for easy management within the Unity Editor. The ball’s movement is controlled by adding force based on the mouse drag input, and the collision system is used to detect hits and misses. The score is updated based on successful hits, and the player is given visual feedback through an on-screen score display.

The project serves as a demonstration of key Unity functionalities, including handling user inputs, implementing realistic physics-based interactions, and managing game state transitions such as score counting and automatic game termination.

## 1.2. Purpose of the Project

The primary purpose of this project is to apply and demonstrate key game development concepts using Unity, focusing on player interaction, physics simulation, and game logic. The goal is to create a simple and intuitive game where users can interact with the environment by throwing a ball toward a target, simulating real-world physics.

This project aims to enhance skills in:

- **Unity’s Physics Engine**: Applying forces and managing physical interactions.
- **User Input Handling**: Capturing and interpreting mouse input.
- **Game State Management**: Tracking scores, resetting objects, and controlling game flow.
- **Collision Detection**: Implementing hit detection logic and score updates.
- **Game Mechanics Design**: Developing intuitive and responsive gameplay.

This project is both a learning tool and a base for more advanced Unity-based games in the future.


## 1.3. Project Scope

This project focuses on the design and implementation of a ball-throwing game using Unity and includes:

- **Game Mechanics**: The player throws a ball toward a target to earn points. After 10 attempts, the game ends automatically.
- **User Interaction**: Click and drag the mouse to control the direction and strength of the throw.
- **Physics Simulation**: Unity’s physics engine simulates realistic ball motion and collisions.
- **Score Management**: Scores are tracked and displayed after each hit.
- **Game State Control**: The ball resets after each throw. The game ends after 10 throws.
- **Collision Response**: Differentiates between target hits, ground, and stand impacts.

This version supports a single level and a fixed attempt limit but can be extended for more features and platforms using Unity’s cross-platform capabilities.


## 1.4. Hardware and Software Requirements

### Hardware Requirements

- **Processor**: Intel Core i5 or higher
- **RAM**: Minimum 8 GB (16 GB recommended)
- **Graphics**: Dedicated GPU (e.g., NVIDIA GTX 1050 or better)
- **Storage**: At least 10 GB free space
- **Display**: Full HD (1920x1080) or higher
- **Input Devices**: Keyboard and mouse

### Software Requirements

- **Operating System**: Windows 11 (64-bit) or macOS 10.15+
- **Game Engine**: Unity 2021.3.x LTS or newer
- **Preferred IDE**: **Visual Studio 2019 or later** (Recommended for full Unity integration)
- **Unity Packages**:
  - Unity Physics Engine (built-in)
  - TextMeshPro (for UI/score display)
- **Version Control**: Git or GitHub (optional)
- **Additional Software**:
  - .NET SDK (required for C#)
  - Unity Hub (for project management)


## 1.5. Installation and Running Process

### Step 1: Install Unity and Visual Studio

- Download and install **Unity Hub** from [https://unity.com/download](https://unity.com/download).
- In Unity Hub, install **Unity Editor 2021.3.x LTS** or newer.
- During installation, **select Visual Studio** as the preferred IDE (ensure the “Game development with Unity” workload is checked).

### Step 2: Clone or Download the Project

```bash
git clone https://github.com/your-username/ball-throwing-game.git
```
Or download the ZIP and extract it.

### Step 3: Open the Project in Unity
- Open Unity Hub.
- Click "Open" and navigate to the project folder.
- Unity will import assets and configure the environment.

### Step 4: Set Visual Studio as External Script Editor
- In Unity: Go to Edit > Preferences > External Tools.
- Set External Script Editor to Visual Studio.
  
### Step 5: Run the Game
- Open the MainScene (or the appropriate scene).
- Click the Play button in the Unity Editor.
- Click and drag the ball to aim at the target.
- The game ends automatically after 10 throws.
