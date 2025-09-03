# 🐍 Snake Game in Python

A classic **Snake Game** implemented in **Python** using the `tkinter` library. Guide the snake to eat food, grow longer, and avoid colliding with walls or itself. A fun and interactive way to learn Python GUI programming and game logic!  

---

## 🎮 Features

- Smooth gameplay with adjustable speed.
- Snake grows every time it eats food.
- Real-time score display.
- Game over screen when the snake collides with walls or itself.
- Arrow key controls for intuitive navigation.
- Simple and clean **Tkinter GUI**.

---

## 🖥️ Screenshot

![Snake Game Screenshot](screenshot.png)  
*(Replace with your own screenshot of the game)*

---

## ⚙️ How to Run

1. Ensure you have **Python 3** installed.
2. Clone the repository:

```bash
git clone https://github.com/your-username/snake-game.git
cd snake-game
```
3. Run the game:
```bash
python snake_game.py
```
4. Use the arrow keys to control the snake.

## 📝 Game Controls

| Key        | Action       |
|------------|-------------|
| Up Arrow   | Move Up     |
| Down Arrow | Move Down   |
| Left Arrow | Move Left   |
| Right Arrow| Move Right  |

---

## ⚡ How It Works

- The game is built using **Tkinter** for the GUI.  
- **Snake** and **Food** are separate classes:  
  - `Snake` handles the snake’s body, movement, and growth.  
  - `Food` spawns randomly on the grid.  
- The game updates every few milliseconds using `window.after()`.  
- Collision detection checks for:  
  - Snake hitting the wall.  
  - Snake colliding with itself.  
- The score increases as the snake eats the food.  

---

## 📦 Game Settings

| Setting        | Default Value |
|----------------|---------------|
| WIDTH          | 500           |
| HEIGHT         | 500           |
| SPEED (ms)     | 200           |
| SPACE_SIZE     | 20            |
| BODY_SIZE      | 2             |
| Snake Color    | #00FF00       |
| Food Color     | #FFFFFF       |
| Background     | #000000       |

*You can easily tweak these values in the code to customize the game.*

---

## 🛠️ Tech Stack

- Python 3  
- Tkinter for GUI  
- Random module for food placement  

---

## 🤝 Contributions

Contributions are welcome! You can improve the game by adding:  

- Multiple levels or increasing speed over time.  
- Sound effects and music.  
- Obstacles or special food items.  
- Mobile or web version of the game.  
