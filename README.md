# 🧟 Zombie Survival — Sprite Edition

A simple **2D survival shooter** built with HTML5 Canvas and vanilla JavaScript.  
Fight off waves of zombies, werewolves, and robots while managing your **HP**, **stamina**, and **ammo**.  
Survive as many waves as you can and upgrade your stats in the shop!

---

## 🎮 Gameplay

- **Objective**: Survive 20 waves of increasingly difficult enemies.
- **Enemies**:
  - 🧟 Zombies — weak but plenty.
  - 🐺 Werewolves — faster and stronger.
  - 🤖 Robots — tanky and deadly.

- **Player Stats**:
  - **HP**: Health points. If it hits 0, game over.
  - **Stamina**: Used when sprinting. Regenerates slowly.
  - **Ammo**: Bullets for your gun. Can be refilled for money.
  - **Money**: Earned from killing enemies. Spend it in the shop.

---

## 🕹️ Controls

- `WASD` → Move
- `Shift` → Sprint (uses stamina)
- `Mouse` → Aim
- `Left Click` → Shoot
- `P` → Pause / Unpause
- `R` → Restart after death

---

## 🛒 Shop & Upgrades

Between certain waves, you can access the **shop**:

- **+20 Max Health** — Increase survivability.
- **+20 Max Stamina** — Sprint for longer.
- **+30 Max Ammo** — Carry more bullets.
- **Buy Better Gun** — Increases fire rate.

**Ammo Refill** is available **anytime** from the HUD for a fixed cost ($50).

---

## 🏠 Homepage

When you load the game, you’ll see the **homepage**:

- Title & Game Rules
- **Play Button** → Starts the game

---

## 🚀 How to Run

1. Clone or download this repository.
2. Make sure the `assets/sprites/` folder contains the required PNG files:
   - `player_64.png`
   - `zombie_64.png`
   - `werewolf_64.png`
   - `robot_64.png`
   - `grass_64.png`
   - `tree_64.png`
   - `rock_64.png`
   - `crate_64.png`
   - `pistol_64.png`
   - `rifle_64.png`
   - `shotgun_64.png`
3. Open the `index.html` file in your browser.
4. Start playing!

---

## 📂 Project Structure

├── index.html # Main game file
├── README.md # Project documentation
└── assets/
└── sprites/ # Game sprites (PNG files)

---

## ✨ Features

- Procedurally generated maps each run.
- Multiple enemy types with different behaviors.
- Upgrade system via shop.
- Responsive HUD with ammo refill button.
- Homepage with rules and play button.
- Smooth HTML5 canvas rendering.

---

## 🛠️ Tech Stack

- **HTML5** (Canvas)
- **CSS3**
- **JavaScript (Vanilla)**

---

## 📜 License

This project is free to use and modify for personal or educational purposes.  
Commercial use of the included sprite art depends on your own assets.

---
