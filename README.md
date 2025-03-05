# Escape Web Game

Welcome to the **Escape Web** game repository! 🎮 This repository hosts the web version of the game, allowing players to enjoy it directly from their browsers.

## Play the Game
Play the game now: [Escape Web](https://bharath-bandaru.github.io/escape-web)

## About the Game
Escape Web is an exciting web-based game designed for an immersive experience. Hosted using **GitHub Pages**, this version ensures smooth performance and accessibility across devices.

## How It’s Hosted
This game is built using **Flutter Web** and deployed on GitHub Pages. To update or modify the game, follow these steps:

1. Build the web version:
   ```sh
   flutter build web --release
   ```
2. Push the `build/web` directory to the `gh-pages` branch:
   ```sh
   git checkout --orphan gh-pages
   git rm -rf .
   cp -r build/web/* .
   git add .
   git commit -m "Deploy Escape Web Game"
   git push origin gh-pages --force
   ```

## More Projects
Check out my portfolio and other projects here: [bharath-bandaru.github.io](https://bharath-bandaru.github.io)

---
### 📌 Stay tuned for updates and improvements!

