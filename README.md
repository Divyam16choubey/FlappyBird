# Flappy Bird — Python & Pygame

A simple recreation of the classic Flappy Bird game built using Python and Pygame. The goal is to guide the bird through gaps between pipes, avoid collisions, and score as many points as possible.

This project helped me explore game development fundamentals, including keyboard input, sprite rendering, collision detection, game loops, and basic physics.

## 🎮 Gameplay

The game starts with a welcome screen. Once you begin, control the bird and try to pass through the gaps between moving pipes without hitting them or the ground.

Each successfully passed pipe increases your score. The game ends when the bird collides with a pipe, hits the ground, or moves outside the playable area.

## ✨ Features

- **Classic gameplay:** A simple, challenging Flappy Bird experience.
- **Keyboard controls:** Control the bird using the Spacebar or Up Arrow.
- **Gravity and movement:** The bird falls naturally and moves upward when you flap.
- **Random pipe generation:** Pipe positions vary to keep each run challenging.
- **Collision detection:** Detects collisions with pipes and the ground.
- **Score tracking:** Displays the current score during gameplay.
- **Sound effects:** Audio feedback for flapping, scoring, and collisions.
- **Start and replay flow:** Return to the welcome screen after a game ends and start another round.

## 🛠️ Tech Stack

- **Language:** Python
- **Library:** Pygame
- **Assets:** Image sprites and audio files

## 📁 Project Structure

```text
FlappyBird/
├── gallery/
│   ├── sprites/
│   │   ├── bird.png
│   │   ├── background.png
│   │   ├── pipe.png
│   │   ├── base.png
│   │   ├── message.png
│   │   └── 0.png ... 9.png
│   └── audio/
│       ├── die.wav
│       ├── hit.wav
│       ├── point.wav
│       ├── swoosh.wav
│       └── wing.wav
├── proj.py
└── README.md
```

The `gallery` directory contains the images and sounds used by the game. Keep the asset paths intact when running the program.

## 🚀 Getting Started

### Prerequisites

- Python 3 installed on your computer.
- pip, Python's package installer.

### 1. Clone the repository

```bash
git clone https://github.com/Divyam16choubey/FlappyBird.git
cd FlappyBird
```

### 2. Install the dependency

Install Pygame using pip:

```bash
python -m pip install pygame
```

On Windows, if `python` is not recognized, you can try:

```powershell
py -m pip install pygame
```

### 3. Run the game

From the project root, execute:

```bash
python proj.py
```

On Windows, you can also use:

```powershell
py proj.py
```

The game window should open with the welcome screen.

## 🕹️ Controls

| Key | Action |
|---|---|
| `Space` | Start the game or flap the bird |
| `↑` Up Arrow | Start the game or flap the bird |
| `Esc` | Exit the game |

**Tip:** Timing is important. Flap carefully to keep the bird between the pipes.

## 🧠 What I Learned

Working on this project provided practical experience with:

- Creating and managing a game loop using Pygame.
- Handling keyboard events and user input.
- Loading and rendering image and audio assets.
- Implementing gravity, vertical movement, and pipe movement.
- Detecting collisions between game objects.
- Generating random obstacles.
- Tracking and displaying a player's score.

## 🔮 Future Improvements

Some ideas for future development include:

- Saving the highest score between sessions.
- Adding difficulty levels and adjustable game speed.
- Improving animations and gameplay feedback.
- Adding a pause and restart option.
- Making the game playable in a web browser.

## 👨‍💻 Author

**Divyam Kumar Choubey**

- GitHub: [@Divyam16choubey](https://github.com/Divyam16choubey)
- Project Repository: [FlappyBird](https://github.com/Divyam16choubey/FlappyBird)

## 📄 License

No license is currently specified in the repository. Please check the repository's licensing terms before redistributing or reusing the code and assets.
