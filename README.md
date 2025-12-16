
Classic Snake game built using Python’s turtle module.

# 🐍 Python Snake Game

A modern, object-oriented version of the classic **Snake** game, built in Python using the `turtle` graphics module.  
This project is part of my **100 Days of Code** journey, where I’m creating real projects to build my skills and track my progress.

---

## 🎮 Gameplay Features

### 🐍 Smooth Snake Movement
- Snake made up of multiple segments  
- Follows the head smoothly  
- Grows each time it eats food  

### 🍎 Random Food Spawning
- Food appears in random locations  
- Each food eaten increases the snake length  
- Each food gives **+1 score**

### 💥 Collision Detection
The game ends when:
- Snake hits a wall  
- Snake hits its own tail  

### 📊 Live Scoreboard
- Score updates instantly  
- Resets when game restarts  
- High contrast for visibility 

### 💾 High Score Persistence
- The game tracks and saves the highest score achieved
- High score data is stored locally in a `data.txt` file
- The high score persists between game sessions

---

## 🧱 OOP Structure

The project is organized into separate classes to keep the code clean and modular:

- **`Snake`** → creates the snake, controls movement, and adds segments  
- **`Food`** → handles random food placement  
- **`Scoreboard`** → displays and updates score  
- **`main.py`** → runs game logic and ties everything together
- **`data.txt`** → stores and persists the high score 

This structure made debugging and improvements easier, and helped me understand real-world OOP patterns.

---

## 🧠 What I Learned

- Object-Oriented Programming with multiple classes  
- Using `turtle` for animations and movement  
- Detecting collisions with coordinates  
- Managing game loops and updates  
- Refactoring code into clean, reusable components  
- Multi-file Python project organization  

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/bukolaomole415-blip/python-pong-game.git
Navigate into the folder:
cd python-pong-game
Run the game:
python main.py
Python comes with the turtle module built in. No extra installations needed.

📦 Coming Soon
I plan to add:

Difficulty settings

Speed increase as score grows

A “Game Over” animation

A downloadable .exe version

💡 Part of My Python Learning Journey
This Snake game builds on the foundation from earlier projects like Pong and Turtle Crossing, helping me strengthen logic, OOP skills, and game design fundamentals.

