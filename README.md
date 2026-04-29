# 🚀 Space Shooter

A 2D space shooter game built with Unity and exported as a WebGL build — playable directly in the browser.

## 🎮 Play the Game

▶️ **[Play Now](https://brandonshrt.github.io/space-shooter/)**

## 📖 About

Space Shooter is a classic arcade-style 2D game where you pilot a spaceship and blast through waves of enemies. Built in Unity and deployed as a WebGL build for easy, install-free play in any modern web browser.

## 🕹️ Controls

| Action | Key |
|--------|-----|
| Move | `W A S D` or Arrow Keys |
| Shoot | `Spacebar` or `Left Click` |

> *(Update these controls to match your actual game!)*

## 🛠️ Built With

- **Unity** — Game engine
- **C#** — Game scripting
- **WebGL** — Browser export target

## 📁 Project Structure

```
space-shooter/
├── Build/          # Unity WebGL build output
├── TemplateData/   # WebGL template assets (loader, styles)
├── index.html      # Entry point for the WebGL player
└── README.md
```

## 🚀 Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/brandonshrt/space-shooter.git
   ```
2. Open `index.html` in a local server (required for WebGL). You can use [VS Code Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) or Python's built-in server:
   ```bash
   python -m http.server 8000
   ```
3. Navigate to `http://localhost:8000` in your browser.

> ⚠️ WebGL builds won't run if you open `index.html` directly as a file — you need a local server.

## 📝 License

This project is open source. Feel free to fork, modify, and learn from it!

---

Made by [brandonshrt](https://github.com/brandonshrt)
