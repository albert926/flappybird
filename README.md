# ⚔️ Flap — A Survival Flying Game (MakeCode Arcade)

**Flap** is a fast-paced survival game built with [Microsoft MakeCode Arcade](https://arcade.makecode.com/).  
Flap to stay alive while enemies chase, stab, and shoot at you.  
Collect candy for points, dodge attacks, and see how long you can survive!

🎮 **Play it online:**  
👉 [https://flap.alberttalkstech.com](https://flap.alberttalkstech.com)

---

## ✨ Features

- 🕹️ **Tap to fly** – press **A** to flap upward, release to fall  
- ⚔️ **Enemies spawn constantly** – avoid getting hit or stabbed  
- 🧠 **Dynamic enemy AI** – in harder modes, enemies actively follow the player  
- 🍬 **Collect candy** for score bonuses and fiery effects  
- 💯 **Score system**
  - +1 every few seconds you survive  
  - +5 for each candy collected  
- 🔊 **Background music** and scrolling scenery for an arcade vibe  
- 🔥 **Three difficulty levels:**
  - **Easy** – slower enemies  
  - **Medium** – balanced challenge  
  - **Impossible** – enemies move faster and *hunt you down*

---

## 🧩 Controls

| Button | Action |
|:-------:|:--------|
| **A (press)** | Flap upward |
| **A (release)** | Drop downward |
| **Avoid** | Getting hit by enemies |
| **Collect** | Candy for extra points |

---

## 🧠 Game Logic Overview

- The bird sprite (`bird`) flaps upward when **A** is pressed and falls when released.  
- Enemy sprites (`myEnemy`) spawn from the right and either move straight or *follow* the player.  
- Difficulty settings control:
  - Spawn rate of enemies and candy  
  - Enemy speed and movement type  
- Collision with enemies ends the game.  
- Candies appear randomly, drift left, and grant points when collected.

---

## 🚀 Importing the Project

You can open or remix this game in MakeCode Arcade.

### Option 1 — Open Online
1. Visit [https://arcade.makecode.com/](https://arcade.makecode.com/)
2. Click **Import → Import URL**
3. Paste:
   ```
   https://github.com/albert926/flappybird
   ```

### Option 2 — Add as an Extension
1. Go to **MakeCode Arcade → New Project**
2. Click the ⚙️ **gearwheel → Extensions**
3. Paste the same URL above.

## 📜 Metadata

for PXT/arcade
