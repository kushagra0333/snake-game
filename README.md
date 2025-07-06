# 🐍 Snake Game

A responsive, visually enhanced **Snake Game** built with vanilla HTML, CSS, and JavaScript. The game includes score tracking, high score persistence via `localStorage`, keyboard and mobile touch controls, and a restart button UI overlay.

---

## 🎮 Live Demo

👉 **[Try the Game Live](https://kushagra0333.github.io/snake-game/)** (Replace with your hosted link if deployed)

---

## ✨ Features

* Responsive grid-based game board
* Smooth animations with CSS transitions
* Dynamic scoring and persistent high score using `localStorage`
* Restart game button overlay on game over
* Mobile-friendly controls with arrow buttons
* Custom visuals for:

  * Snake body and head with gradient styles
  * Pulsing food animation
* Game auto-starts on first movement input

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3**
* **JavaScript (ES6+)**
* **Bootstrap Icons** (for mobile arrow buttons)

---

## 📱 Controls

### On Desktop (Keyboard):

* `Arrow Up` → Move Up
* `Arrow Down` → Move Down
* `Arrow Left` → Move Left
* `Arrow Right` → Move Right

### On Mobile:

Use the **on-screen arrow buttons** to control the snake.

---

## 🧠 How It Works

* The game uses a `19x19` CSS Grid to create the board.
* Snake movement is handled with a JavaScript `setInterval()` loop running every 150ms.
* Food appears randomly in any grid cell not occupied by the snake.
* If the snake collides with the wall or itself, the game ends.
* The `Score` and `High Score` are shown above the game board.
* `High Score` is stored in the browser's local storage and persists between sessions.
* A restart button (`↻`) appears in the center after game over.

---

## 🚀 Getting Started

To run this game locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/snake-game.git
   cd snake-game
   ```

2. Open the `index.html` file in your browser:

   ```bash
   open index.html
   ```

*No build tools or installation required.*

---

## 📂 Folder Structure

```
snake-game/
├── index.html     # Main HTML file with all CSS & JS inline
└── README.md      # Project documentation
```

---

## 🎨 Customization Ideas

* Add difficulty levels (speed changes)
* Implement sound effects
* Add pause/resume functionality
* Change snake/food styles using themes
* Support swipe gestures on mobile

---

## 🙌 Acknowledgements

* Inspired by the classic **Nokia Snake Game**
* Bootstrap Icons CDN used for mobile UI

