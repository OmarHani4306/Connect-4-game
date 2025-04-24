# Connect-4 Game

This project implements the popular **Connect Four** game. The game is developed in **C** language and includes multiple files to run the game smoothly.

### Features:

    🧠 Game Modes: Two-player (PvP) and One-player (PvC) with random move logic

    🎮 Interactive Grid Display: Colored ASCII grid with live updates on turns, moves, scores, and time

    🧾 Main Menu: Start new game, load game, view top players, and exit

    ⚙️ Configurable Settings: Board height, width, and high score limit via XML file

    💾 Save & Load System: Binary save files for up to 3 games, selectable via menu

    🔁 Undo & Redo: Navigate move history with undo/redo, cleared upon new move

    🏆 Score & Ranking System: Detects connected-fours, updates score, tracks top players

    📂 High Score File Management: Reads/writes sorted scores with minimal file access and name handling

    ❌ Robust Error Handling: Handles corrupt/missing config files with fallback defaults
### Files:
- **main.c**: The C language code for the game logic.
- **main.exe**: The executable file to run the game.
- **parameters.xml**: The XML configuration file containing parameters such as width, height, and the top player.

### Demo Video:
[Watch the demo](https://drive.google.com/drive/folders/1ROUL7hbz6P6fkFX3q3stheTJHB8dhuA1?usp=sharing)
