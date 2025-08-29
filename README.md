# 🚀 Space Shooter Game  

A classic **2D Space Shooter Game** built in **C++** using the `graphics.h` library.  
Control your spaceship, destroy incoming enemies, and survive as long as possible!  

---

## 🎮 Gameplay Overview  

- 🛸 Control your spaceship with **Arrow Keys**  
- 🔫 Shoot bullets with the **Spacebar**  
- 💥 Destroy enemies before they reach the bottom  
- ⭐ Score points for every enemy destroyed  
- ❤️ Game ends when enemies cross the bottom or you lose all health  

---

## ⚙️ System Requirements  

- C++ Compiler with `graphics.h` support (e.g., **Turbo C++** or compatible)  
- Operating System: Windows (with DOSBox for Turbo C++) or any system supporting `graphics.h`  
- Screen Resolution: **800x600** pixels  

---

## 🚀 How to Run  

1. Compile the source code:  
   ```bash
   g++ "space shooter.cpp" -o space_shooter
(Or use Turbo C++ compiler if preferred)

Run the executable:

./space_shooter


Controls:

   ⬅️ Move Left
   
   ➡️ Move Right
   
   ⬆️ Move Up
   
   ⬇️ Move Down
   
   Spacebar → Shoot

🛠️ Features

✔️ Spaceship and enemies drawn with triangles using graphics.h
✔️ Smooth movement & shooting mechanics
✔️ Scoring system to track destroyed enemies
✔️ Health & Level system for progression
✔️ Game Over screen when enemies reach the bottom

📂 Main Functions

spaceship() → Draws the player's spaceship

enemy() → Draws enemy spaceships

Start() → Initializes game window & title screen

Game_over() → Displays Game Over screen

main() → Runs the game loop, input handling, collisions, scoring, and level progression
