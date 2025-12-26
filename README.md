# Ludo Python Game

This project is a complete Ludo board game implemented in Python using Tkinter. It provides a playable Ludo experience with a graphical interface, dice rolling, token movement, turn management, and win detection. All core game mechanics are handled in code, and the game runs locally as a desktop application.

---

## Overview

The game uses Tkinter to render the board and gameplay interface, along with image assets for dice blocks and the application icon. Players take turns rolling the dice and moving pieces around the board. The logic controls valid movements, piece traversal on the board and inside home paths, overlapping conditions, and winner determination.

The project is packaged as a single Python script with supporting image assets.

---

## Features

* Fully playable Ludo board game in Python
* Graphical user interface built with Tkinter
* Dice roll functionality using random generation
* Game board rendering and token movement
* Turn management and movement rules handling
* Start and traversal logic for all player colors
* Winner and runner-up detection logic
* Custom window title and visual assets included

---

## Tech Stack

* **Language:** Python
* **GUI:** Tkinter
* **Image Handling:** Pillow
* **Other Libraries:** `time`, `random`

---

## Project Structure

```
Ludo-Python-main/
│
├── Ludo_game.py          # Main game implementation
├── Images/
│   ├── 1_block.png
│   ├── 2_block.png
│   ├── 3_block.png
│   ├── 4_block.png
│   ├── 5_block.png
│   ├── 6_block.png
│   └── ludo_icon.ico
```

---

## Installation

1. Ensure Python is installed on your system.
2. Install the required dependency:

```bash
pip install pillow
```

Tkinter is included with standard Python installations on most systems.

---

## Running the Game

Run the main script:

```bash
python Ludo_game.py
```

The game window will open, and you can start playing.

---

## Notes

* The game relies on the image assets in the `Images` folder, so the directory structure must remain intact.
* The application runs as a standalone local desktop game.

---

## License

No license file is included in this project.
