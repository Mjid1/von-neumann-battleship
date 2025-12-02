# Von Neumann Battleship  
A functional implementation of the classic **Battleship** game written in Assembly Language. This project runs on the **Von Neumann Simulator** (Simulador Von Neumann), an educational tool for visualizing processor architecture.  
![image](https://github.com/Mjid1/BATTLESHIP_Assembly-_Game/assets/94358027/e4e2a165-ecff-4bf6-b509-68e4a389a74b)  
## 📋 Project Overview

This project simulates a strategy game using low-level machine architecture concepts. It demonstrates:
* **Memory-Mapped I/O:** Interacting with a visual display and keyboard buffer.
* **Interrupt Handling:** Managing user input via hardware interrupts.
* **Assembly Logic:** Subroutines for coordinate validation, board drawing, and hit/miss logic.
* **Direct Memory Access:** Writing directly to video memory addresses to render graphics.

## 🎮 How to Play

1.  **Objective:** Find the ships hidden on the 6x6 grid.
2.  **Input:** When the screen says `ENTRA COORD` (Enter Coordinate), type a location using the simulated keyboard (e.g., `a1`, `b4`, `c2`).
3.  **Color Codes:**
    * **Blue:** Water / Unknown
    * **Red:** Hit (Ship found)
    * **Green:** Cursor / Selection  

## 👤 Author
**Abdelmajid Ghaiati**

---
*Developed for the Computer Architecture course.*
