# 🐍🎲 Snakes and Ladders Game (Python)

## 📌 Project Overview
This project is a **console-based Snakes and Ladders game** developed using **Python**.  
It simulates the classic board game where players roll a dice, climb ladders, and slide down snakes until someone reaches position 100.

---

## 🎯 Objectives
- Implement game logic using Python
- Practice control flow, loops, and functions
- Use data structures like dictionaries for snakes and ladders mapping
- Simulate dice rolls and player turns

---

## 🛠️ Technologies Used
- **Language:** Python  
- **Concepts:**  
  - Loops & Conditionals  
  - Functions  
  - Random module  
  - Dictionaries  
  - Input/Output handling  

---

## 🗺️ Game Rules
- The board has positions from **1 to 100**
- Rolling a **dice (1–6)** decides the move
- **Ladders** move the player up
- **Snakes** move the player down
- Exact roll is required to reach **100**
- First player to reach 100 **wins**

---

## 🧩 Snakes & Ladders Mapping
```python
snakes = {
    99: 54,
    70: 55,
    52: 42,
    25: 2,
    95: 72
}

ladders = {
    6: 25,
    1
