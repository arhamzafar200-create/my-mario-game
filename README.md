# ChromaQuest Platformer 🎮

A complete 2D platformer game inspired by classic Super Mario, built with **HTML5, JavaScript, and Phaser 3**. Play directly in your browser with smooth 60 FPS gameplay, mobile support, and original assets.

## 🌟 Features

### Core Gameplay
- ✅ **10 Handcrafted Levels** with increasing difficulty
- ✅ **Smooth Player Movement** - Run, jump, double-jump, wall slides
- ✅ **3-Heart Health System** with temporary invincibility
- ✅ **Checkpoint System** - Continue from last checkpoint
- ✅ **Coin & Score System** - Collect coins, gems, and treasures

### Enemy Types & AI
- ✅ **Walking Enemies** - Patrol platforms with AI
- ✅ **Flying Enemies** - Chase player in air
- ✅ **Jumping Enemies** - Jump to reach player
- ✅ **2 Boss Fights** - Every 5 levels (Levels 5 & 10)
- ✅ **Enemy Defeat** - Jump on enemies to defeat them

### Level Features
- ✅ **Platforms** - Static and dynamic
- ✅ **Moving Platforms** - Follow paths
- ✅ **Falling Platforms** - Crumble when stepped on
- ✅ **Hazards** - Spikes, lava, moving saws
- ✅ **Hidden Areas** - Secret rooms and treasures
- ✅ **Goal Flag** - Reach the end to complete level

### Power-Ups & Collectibles
- 🔷 **Double Jump** - Extended air control
- 🛡️ **Shield** - One hit protection
- ⚡ **Speed Boost** - Temporary speed increase
- 🔥 **Fireball** - Shoot projectiles
- 🧲 **Magnet** - Auto-collect coins
- 👤 **Extra Lives** - Additional lives
- ❤️ **Health Pickups** - Restore health
- 🔑 **Keys** - Unlock hidden areas
- 💎 **Gems** - Collectible treasures
- 🪙 **Coins** - Primary currency

### Controls

**Desktop:**
- `Arrow Keys` or `WASD` - Move
- `Space` - Jump
- `Shift` - Sprint
- `X` - Attack/Shoot
- `P` - Pause

**Mobile:**
- Virtual Joystick - Move
- Jump Button - Jump
- Attack Button - Attack
- Pause Button - Pause

## 🚀 Quick Start

### Play Online
1. Open `index.html` in your web browser
2. Click "Start Game"
3. Complete levels and defeat bosses
4. Collect coins and power-ups

### Local Development
```bash
git clone https://github.com/arhamzafar200-create/my-mario-game.git
cd my-mario-game
open index.html
```

## 📁 Project Structure

```
scripts/
├── constants.js              # Game configuration
├── game.js                   # Main game setup
├── utils/                    # Utility classes
│   ├── AssetManager.js
│   ├── SaveManager.js
│   ├── AudioManager.js
│   ├── ParticleManager.js
│   ├── AnimationManager.js
│   └── LevelManager.js
├── entities/                 # Game entities
│   ├── Player.js
│   ├── Enemy.js
│   ├── WalkingEnemy.js
│   ├── FlyingEnemy.js
│   ├── JumpingEnemy.js
│   ├── Boss.js
│   ├── Collectible.js
│   ├── Platform.js
│   ├── Hazard.js
│   ├── PowerUp.js
│   └── ProjectileLaser.js
├── ui/                       # UI components
│   ├── HUD.js
│   ├── Menu.js
│   ├── MobileUI.js
│   ├── PauseMenu.js
│   ├── GameOverScreen.js
│   ├── VictoryScreen.js
│   ├── LevelSelector.js
│   └── SettingsMenu.js
└── scenes/                   # Game scenes
    ├── BootScene.js
    ├── MenuScene.js
    ├── LevelScene.js
    ├── GameOverScene.js
    ├── VictoryScene.js
    ├── LevelSelectScene.js
    └── SettingsScene.js
```

## 🎮 How to Play

1. **Collect Coins** - Gather coins for points
2. **Defeat Enemies** - Jump on enemies or use power-ups
3. **Avoid Hazards** - Don't touch spikes or lava
4. **Find Power-Ups** - Unlock special abilities
5. **Reach Goal** - Complete each level
6. **Boss Fights** - Defeat bosses on levels 5 and 10

## 🎨 Graphics & Audio

All graphics and audio are **original** - no copyrighted Nintendo assets used.

## 📊 Statistics

- 10 Levels
- 5 Enemy Types
- 10+ Power-Ups
- 5+ Hazard Types
- 20+ Sound Effects
- 5000+ Lines of Code
- Mobile Optimized ✅
- 60 FPS Performance ✅

## 🌐 Browser Support

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile Browsers ✅

## 📄 License

Open source - Free to use and modify

---

**Ready to play? Open `index.html` now!** 🎮✨