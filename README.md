## 🐍 Snake Game

A classic Snake Game built using **HTML**, **CSS**, and **JavaScript** — no frameworks!
Play using your keyboard or mobile touch controls. Responsive, animated, and customizable.

---

### 🔗 Live Demo

[Click here to play the game](#)
*(Replace `#` with your deployed game link once available)*

---

### 📸 Screenshots

| Desktop                                    | Mobile                                   |
| ------------------------------------------ | ---------------------------------------- |
| ![snake-desktop](assets/snake-desktop.png) | ![snake-mobile](assets/snake-mobile.png) |

*(Optional: Add your own screenshots in `assets/` folder)*

---

### 🚀 Features

* 🎮 Playable on **keyboard** (desktop) and **touch buttons** (mobile)
* 🍎 Glowing food animation
* 🐍 Snake grows when it eats
* 💀 Game over if snake hits wall or itself
* 💾 Score & High Score saved in browser
* 🔄 Restart button with animated Bootstrap icon
* ⚡ Smooth animations & responsive grid layout
* 🎨 Fully styled with modern CSS (no Tailwind or Bootstrap)

---

### 📁 File Structure

```
snake-game/
├── index.html         # Game UI and structure
├── style.css          # Modern CSS for game board and controls
├── script.js          # Core logic for game movement, input, and collision
└── assets/            # (Optional) Screenshots, icons, etc.
```

---

### 🧠 How It Works

* The **snake** is represented as an array of `{x, y}` positions.
* It moves by adding a new head and removing the tail (unless it eats food).
* Direction is controlled via keyboard or mobile buttons.
* CSS Grid is used to layout the board.
* `setInterval()` updates the game every 150ms.
* Game resets when the player dies, and high score is stored in `localStorage`.

---

### 🧑‍💻 Technologies Used

* **HTML5**
* **CSS3** (Grid, Flexbox, Animations)
* **Vanilla JavaScript**
* **Bootstrap Icons** (via CDN)

---

### 📱 Controls

#### Desktop:

* `↑` `↓` `←` `→` keys to move the snake

#### Mobile:

* On-screen directional buttons will appear on smaller screens

---

### ✅ To Run Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/snake-game.git
   ```

2. Open `index.html` in your browser:

   ```bash
   cd snake-game
   open index.html
   ```

---

### 🛠 Customization Ideas

* Add levels or speed increase over time
* Add sound effects on eating and game over
* Add a pause button
* Use swipe gestures on mobile

---

### 👨‍🎓 Credits

Made with 💚 by \[Your Name]
Inspired by the classic Nokia Snake Game
Bootstrap Icons used under MIT license

---

### 📃 License

This project is licensed under the [MIT License](LICENSE).

---

Let me know if you'd like:

* A markdown file (`README.md`) ready to download
* GitHub deploy instructions
* Or if you want to convert it into a React or PWA version

Let’s level it up! 🚀
