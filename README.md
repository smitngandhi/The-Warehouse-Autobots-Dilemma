# The_Outliers

**Hackathon Project: DoseHack**

This repository showcases our solution for efficient and intelligent pathfinding for single and multiple autonomous bots using both classical and reinforcement learning methods.

---

## 📌 Project Modules

### 🚶‍♂️ Movement of Single Bot – `Movement_single.ipynb`

This module implements the **A\*** algorithm to determine the shortest path for a single bot moving from a given source to a destination on a grid.

- The bot starts facing **upward**.
- Movement instructions include:
  - **Forward**: Move in the current direction.
  - **Left**: Rotate 90° counterclockwise.
  - **Right**: Rotate 90° clockwise.
- When a direction change is required, the bot first rotates appropriately before moving forward.
- The A\* algorithm calculates the optimal path while avoiding obstacles, ensuring an efficient route to the destination.

---

### 🤖 Coordinated Movement of Dual Bots – `dual_bots.ipynb`

This notebook implements the **A\*** algorithm to coordinate movement between **two bots** from their respective sources to destinations.

- Collision avoidance is handled by allowing one bot to **wait** if a collision is predicted, ensuring safe and efficient parallel movement.

---

### 🖼️ GUI Display of Dual Bots – `gui_dual.ipynb`

A Tkinter-based GUI visualization of the dual bot A\* algorithm.

- Offers a visual interface for tracking the real-time pathfinding and movements of the bots on a grid.

---

### 🧠 Q-Learning for Multi-Bots – `q_learning_bot.ipynb`

This module applies **Q-Learning** for pathfinding involving a **dynamic number of bots**:

- Users can input the number of bots dynamically.
- Each bot finds its own path toward its destination using reinforcement learning.
- The process stops as soon as the first successful path is found, saving both **time** and **resources**.

---

### 🏁 Final Optimized Q-Learning Model – `q_learning.ipynb`

This notebook contains our **final implementation** of the Q-Learning approach with optimized performance metrics.

- Output includes:
  - ⏱️ **Time Taken**
  - 📊 **Average Steps**
  - 👣 **Each Bot's Individual Steps**

---

## 🚀 Tech Stack

- Python
- A* Algorithm
- Q-Learning (Reinforcement Learning)
- Tkinter (for GUI)

---

## 💡 Developed at

**DoseHack** Hackathon – Team: *The_Outliers*

---

## 📂 Repository Structure

```bash
├── Movement_single.ipynb         # A* for single bot
├── dual_bots.ipynb               # A* for dual bots with collision handling
├── gui_dual.ipynb                # GUI visualization for dual bots
├── q_learning_bot.ipynb          # Q-Learning for multi-bots (dynamic)
├── q_learning.ipynb              # Final Q-Learning optimized solution
├── README.md                     # Project documentation
```

---

## ✨ Contributors

- [Dhruvil Joshi](https://github.com/Dhruvil-Joshi)
- [Prachi Desai](https://github.com/Prachidesai2506)
---
