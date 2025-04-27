# 🚀 Tower Dodge

**Tower Dodge** is a 2D endless arcade-style game made with Unity, where you control a flying plane and try to dodge towers as long as possible while scoring points. As the score increases, the game gets faster and more challenging!

---

## 🎮 Gameplay Overview

- **Objective**: Survive by dodging vertical towers and earn the highest possible score.
- **Mechanic**: Tap or press to make the plane fly upward—gravity pulls it down continuously.
- **Difficulty**: Increases dynamically—the longer you last, the faster the obstacles move.

---

## 🕹️ Controls

- **PC**:
  - `Spacebar` or Left Mouse Click – Make the plane go up
- **Mobile**:
  - Tap the screen to fly upward

---

## 📈 Scoring System

- Points are earned by passing between towers (through scoring zones).
- Every 15 points, obstacle speed increases, making the game harder.
- The **High Score** is saved between sessions using Unity’s `PlayerPrefs`.

---

## ⚙️ Key Scripts

### `GameManager.cs`
- Manages the game state: start, pause, game over.
- Handles score and high score logic.
- Controls UI elements like the play button and game over screen.

### `Player.cs`
- Manages player movement and gravity.
- Detects input for upward motion.
- Handles collisions with obstacles and scoring zones.

### `Solids.cs`
- Controls the behavior of the moving tower obstacles.
- Automatically destroys towers when they leave the screen.

### `Spawner.cs`
- Spawns tower obstacles at regular intervals with random vertical offsets.
- Adjusts spawn behavior dynamically based on speed and difficulty.

### `Parallex.cs`
- Creates a scrolling background effect for visual depth.

---

## 🖼️ UI Elements

- **Score Display**: Updates in real time.
- **High Score Text**: Shows your best score ever.
- **Play Button**: Starts or restarts the game.
- **Game Over Panel**: Appears when the player crashes.

---

## 🛠️ How to Run

1. Open Unity and load the Tower Dodge project.
2. Open the `MainScene` from the `Scenes` folder.
3. Press the Play button in Unity Editor or build to desktop/mobile.
4. Enjoy dodging those towers!

---

## 📝 Credits

Created by **Elio Germanos** as part of a Unity game development project.  
Designed using C# and Unity Engine (2D).

---

## 📌 Notes

- This game was developed to showcase knowledge of Unity scripting, object spawning, parallax effects, and basic UI management.
- Code is modular and beginner-friendly for educational purposes or enhancements.

---

