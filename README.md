# MyFlappyBird

A classic 2D Flappy Bird clone built using Python and Pygame. This project demonstrates core game development concepts including collision detection, sprite animation, and infinite scrolling backgrounds.

## 🚀 Features

* **Smooth Gameplay:** Responsive controls using keyboard input.
* **Dynamic Obstacles:** Randomized pipe generation for a unique experience every run.
* **Score Tracking:** Real-time score display and high-score persistence.
* **Asset Management:** Integrated custom sound effects and sprites.

## 🛠️ Tech Stack

* **Unity:** C#

## 📦 Installation & Setup

1. **Clone the repository:**
```bash
git clone https://github.com/R-J-N/MyFlappyBird.git
cd MyFlappyBird

```


2. **Install dependencies:**
Ensure you have Python installed, then install Pygame:
```bash
pip install pygame

```


3. **Run the game:**
```bash
python main.py

```



## 🎮 How to Play

* Press the **[SPACEBAR]** or **[UP ARROW]** to make the bird flap.
* Navigate through the gaps between the green pipes.
* The game ends if you hit a pipe or the ground.
* Try to beat your highest score!

## 📂 Project Structure

```text
.
├── gallery/           # Images, sprites, and audio assets
├── main.py            # Main game loop and logic
└── README.md          # Project documentation

```

## 🧠 Key Learnings

* Implementing a **Game Loop** (Initialize -> Event Handling -> Update -> Draw).
* Managing **Gravity and Velocity** physics for the bird's movement.
* Handling **Hitbox Collision** using Pygame's `Rect` objects.

---
