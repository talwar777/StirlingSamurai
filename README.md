# 🥷 Stirling Samurai – 2D Platformer Game  
**CSCU9N6 – Games Development Assignment**  
**Language:** Java  
**IDE:** NetBeans / Eclipse  

---

## 🎮 About the Game

**Stirling Samurai** is a Java-based 2D platformer where you play as a heroic samurai who must survive enemy attacks, collect coins, and conquer two dynamic levels filled with animated dangers.

The game demonstrates animation, enemy AI, sound effects, smart collision detection, tile maps, player health, scoring, and parallax scrolling — all in Java.

---

## 🧩 Game Features

✅ Animated player and enemy sprites  
✅ Smart wolf AI with health system  
✅ Collision detection (tile, fire, rock, enemy)  
✅ Two complete levels with seamless transition  
✅ Coins and hearts (for scoring and health)  
✅ Rock and fire tile hazards  
✅ Jump, block, and attack mechanics  
✅ Game states: Start, Pause, Game Over, Victory  
✅ Sound effects + MIDI background music  
✅ Parallax backgrounds per level  
✅ Debug mode & fullscreen toggle  

---

## 🎮 Controls

| Key           | Action                  |
|---------------|-------------------------|
| `↑` UP        | Jump                    |
| `→` RIGHT     | Move Right              |
| `←` LEFT      | Move Left               |
| `A`           | Attack (sword)          |
| `D`           | Block                   |
| `P`           | Pause/Resume            |
| `F`           | Toggle Fullscreen       |
| `ESC`         | Exit                    |
| `Mouse Click` | Start / Restart Game    |
| `B`           | Toggle Debug Mode       |

---

## 📂 Project Structure


├── game2D/
│   ├── Game.java              # Main game logic                      |  
│   ├── GameCore.java          # Abstract game loop                   |
│   ├── Animation.java         # Sprite animation manager             |
│   ├── Sprite.java            # All character logic                  |
│   ├── TileMap.java           # Tile map loading + drawing           |
│   ├── Tile.java              # Tile attributes                      |
│   ├── Sound.java             # Sound effect player                  |
│   └── Velocity.java          # (Optional) Movement logic            |

---

## 🔊 Audio & Music

- 🎵 Background music: `arabNight.mid` (plays automatically)
- 🗡️ Sword: `sword.wav`
- 💥 Hurt: `hurt.wav`
- 🪙 Coin: `coin_recieved.wav`
- ❤️ Heart: `heart_collect.wav`
- ☠️ Death: `death.wav`
- 🐦 Jump: `jumping.wav`

---

## ⚙️ How to Run

1. Install **Java 17+**
2. Open project in NetBeans or Eclipse
3. Ensure folders:
   - `maps/`
   - `images/`
   - `sounds/`
   are inside your project root.
4. Run `Game.java`
5. Enjoy the journey of Stirling Samurai!

---

## 🧪 Known Issues

- Rare animation overlap when player collides rapidly with multiple wolves.
- Rock may occasionally stop if reset too fast.
- Repeated inputs can cause animation flicker.

---

## 🔮 Future Improvements

- More enemy types and boss fights  
- Menu + level selector  
- Save/load feature  
- Inventory / power-ups  
- Touch controls for mobile

---

## 🏅 Credits

Developed by **Mohamed Zaki**  
All assets used are for academic use only and were sourced from open or royalty-free game art platforms.

---

## 📝 License

This project is part of **CSCU9N6 - Games Development** coursework  
Use permitted for academic, non-commercial evaluation.

---
