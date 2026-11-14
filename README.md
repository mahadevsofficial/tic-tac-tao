# Tic Tac Toe — Calm Edition

A clean, eye-friendly Tic Tac Toe game built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies, no build step — just open the file and play.

![Tic Tac Toe Preview](https://img.shields.io/badge/status-ready%20to%20play-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## ✨ Features

- 🎮 **Classic 3×3 Tic Tac Toe** — two players, X starts first
- 👁️ **Easy on the eyes** — soft muted palette, gentle shadows, no harsh glows
- 📱 **Fully responsive** — works on desktop, tablet, and mobile
- 🏆 **Win detection** — highlights the winning line with a soft golden glow
- 🤝 **Draw detection** — announces a tie when the board is full
- 🔄 **One-click reset** — start a new game instantly
- ⚡ **Zero dependencies** — no frameworks, no libraries, no build tools
- 🎨 **Pure HTML/CSS/JS** — a single file you can open in any browser

---

## 🚀 How to Use

**Anyone can use it — no coding required!**

1. **Download** the `index.html` file (or copy the code from this repo).
2. **Open** it in any modern browser (Chrome, Firefox, Safari, Edge).
3. **Play!** Click any empty cell to place your mark.

That's it. No installation, no npm, no setup.

### Optional: Clone the repo

```bash
git clone https://github.com/your-username/tic-tac-toe-calm.git
cd tic-tac-toe-calm
```

Then just open `index.html` in your browser.

---

## 🎯 How to Play

| Step | Action |
|------|--------|
| 1 | The game starts with **X** |
| 2 | Click any empty cell to place your mark |
| 3 | Players alternate turns: **X → O → X → O …** |
| 4 | First to get **3 in a row** (horizontal, vertical, or diagonal) **wins** |
| 5 | If all 9 cells fill with no winner, it's a **draw** |
| 6 | Click **"New Game"** to reset and play again |

---

## 🎨 Customization

Want to tweak the look? The CSS is well-commented and easy to change:

- **Colors:** Update the hex values in the `.cell.x-move`, `.cell.o-move`, and `.cell.win` classes.
- **Board size:** Adjust the `max-width` on `.game-container`.
- **Font sizes:** Change the `font-size` in `.cell`.
- **Background:** Modify the `background` on `body`.

No JavaScript changes needed for most visual tweaks.

---

## 🧠 How It Works (For Curious Minds)

The game logic lives in a single IIFE (Immediately Invoked Function Expression):

- **State:** A `board` array of 9 cells, `currentPlayer`, `gameActive`, and `winnerInfo`.
- **Render:** `renderBoard()` rebuilds the grid on every move.
- **Win check:** After each move, `checkGameState()` loops through 8 winning patterns.
- **Click handler:** Validates the move, updates state, re-renders, and switches players.

Clean, readable, and beginner-friendly — perfect for learning or forking.

---

## 📁 File Structure

```
tic-tac-toe-calm/
└── index.html    ← Everything: HTML + CSS + JS in one file
```

---

## 🌐 Browser Support

| Browser | Supported |
|---------|-----------|
| Chrome  | ✅ Yes |
| Firefox | ✅ Yes |
| Safari  | ✅ Yes |
| Edge    | ✅ Yes |
| Opera   | ✅ Yes |

Requires a modern browser with support for `backdrop-filter` (all current browsers have it).

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

- 🐛 Report bugs via [Issues](https://github.com/your-username/tic-tac-toe-calm/issues)
- 💡 Suggest features
- 🎨 Submit design improvements
- 🔧 Open a Pull Request

Please keep the code dependency-free and the design calm and accessible.

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and share for personal or commercial projects.

```
MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
```

---

## ⭐ Show Your Support

If you find this useful, give it a ⭐ on GitHub — it helps others discover the project!

---

**Made with ❤️ for anyone who wants a simple, calm, and accessible game.**
