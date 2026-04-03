# 🕹️ Tetris Game

A sleek, lightweight, and fully responsive Tetris clone built with vanilla JavaScript and HTML5 Canvas. This version features a modern UI, mobile-friendly controls, and customizable keybindings.

## 🔗 [**🚀 Click Here to Play the Live Demo**](https://jingzhe0915.github.io/tetris-game/)




---



## ✨ Features

* **Smooth Gameplay:** High-performance rendering using `requestAnimationFrame`.
* **Mobile Ready:** Dedicated touch controls for playing on the go.
* **Customization:** Fully editable key bindings via the settings gear icon for only desktop.
* **Advanced Mechanics:**
    * **Ghost Piece:** Preview exactly where your piece will land.
    * **Hold System:** Save a piece for later use (C key).
    * **7-Bag Randomization:** Ensures a fair distribution of pieces.
    * **Wall Kicks:** Pieces can rotate even when pressed against walls.
* **Persistent Best Score:** Tracks your all-time high score during the session.

---

## 🎮 How to Play

### Desktop Controls (Default)
| Action | PC Key | Mobile Button |
| :--- | :--- | :--- |
| **Move Left / Right** | `←` / `→` | Left / Right Arrows |
| **Rotate Clockwise** | `↑` | Rotate Right Icon |
| **Rotate Counter-CW** | `Z` | Rotate Left Icon |
| **Soft Drop** | `↓` | Down Arrow |
| **Hard Drop** | `Space` | "Drop" Icon |
| **Hold Piece** | `C` | "Hold" Icon |
| **Pause / Resume** | `P` or `Esc` | Pause Icon |
| **Restart Game** | `R` | — |

### Mobile Controls
Use the on-screen buttons below the game board:
* **Arrows:** Move and Soft Drop.
* **Blue/Purple Buttons:** Rotate Left/Right and Hold.
* **Drop Icon:** Instant Hard Drop.




### 📈 Scoring System
Your score is multiplied by your current **Level**:
* **1 Line:** $100 \times \text{Level}$
* **2 Lines:** $300 \times \text{Level}$
* **3 Lines:** $500 \times \text{Level}$
* **4 Lines (Tetris):** $800 \times \text{Level}$


  
---

## 🚀 Installation & Deployment

Since this project is built with standard web technologies, no compiler or server is required.

1.  **Open the game:**
    Simply double-click the `index.html` file in your browser.

2.  **Deploy to GitHub Pages:**
    Push your code to a GitHub repository, go to **Settings > Pages**, and select the main branch to host your game for free.


---

## 🛠️ Technical Details

* **Canvas API:** Used for drawing the game grid, pieces, and "Next/Hold" previews.
* **CSS Grid & Flexbox:** Ensures the UI scales perfectly from desktop monitors to mobile screens.
* **Local Logic:** The game uses a 2D array (Matrix) to handle collision detection and line clearing.

---

## 📝 License

This project is open-source and available under the **MIT License**. Feel free to fork it and add your own features!
