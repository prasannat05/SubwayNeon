# Subway Neon: Grid Arena

A fast-paced, neon-styled arcade game built with pure HTML5 Canvas. Battle up to 4 players locally in an endless subway runner arena with stunning cyberpunk aesthetics.

## 🎮 Features

- **Multiplayer Local Gaming**: Support for 1-4 players on a shared keyboard
- **Dynamic 3D Perspective**: Perspective-based rendering engine creating depth and immersion
- **Neon Cyberpunk Aesthetic**: Vibrant gradient backgrounds, glowing effects, and thematic UI
- **Obstacle Variety**: Multiple obstacle types including barriers, low obstacles, and trains
- **Coin Collection System**: Collect coins to build your score while avoiding hazards
- **Physics Engine**: Realistic jumping, sliding, and gravity mechanics
- **Particle Effects**: Dynamic burst effects on collision and coin collection
- **Procedural Generation**: Randomly generated obstacle patterns for infinite replayability

## 🎯 Game Mechanics

### Player Controls

| Player | Move Left | Move Right | Jump | Slide |
|--------|-----------|-----------|------|-------|
| **P1 (Cyan)** | A | D | W | S |
| **P2 (Magenta)** | ← Arrow | → Arrow | ↑ Arrow | ↓ Arrow |
| **P3 (Yellow)** | J | L | I | K |
| **P4 (Lime)** | F | H | T | G |

### How to Play

1. Launch the game and select the number of players (1-4)
2. Click "Launch Match" to start
3. Navigate your character across three lanes to collect coins
4. Use **jump** to clear obstacles and trains
5. Use **slide** to fit under low obstacles
6. Avoid train collisions and barriers
7. Colliding with other players causes both to lose coins
8. Last player alive or highest coin count wins!

### Scoring

- **Collect Coins**: +1 coin per collection
- **Collision Penalty**: -1 coin when hitting another player
- **Survival**: Avoid obstacles to stay in the game

## 🛠️ Technical Stack

- **HTML5 Canvas**: Rendering engine
- **Vanilla JavaScript**: Game logic and physics
- **CSS3**: Responsive UI and animations
- **Pure Frontend**: No dependencies or build tools required

## 📊 Game Elements

### Obstacles
- **Barriers** (Red): High obstacles that require jumping
- **Low Obstacles** (Orange): Low obstacles that require sliding
- **Trains** (Dark): Large vehicles that must be jumped over or avoided

### Collectibles
- **Coins** (Gold): Rotating coins that increment your score

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/prasannat05/SubwayNeon.git
   ```

2. Open `index.html` in your web browser:
   ```bash
   open index.html
   # or simply double-click the file
   ```

3. Select your player count and start playing!

## 📁 Project Structure

```
SubwayNeon/
└── index.html          # Complete game (HTML + CSS + JavaScript)
```

The entire game is contained in a single HTML file for easy deployment and distribution.

## 🎨 Design Highlights

- **Neon Color Palette**: Cyan, Magenta, Yellow, and Lime player colors with vibrant glows
- **Perspective Projection**: 3D effect using z-depth calculations
- **Smooth Animations**: Easing functions for lane switching and character movement
- **Visual Feedback**: Particle effects, shadows, and glow effects enhance player feedback

## ⚙️ Game Settings

- **Base Game Speed**: Starts at 6.5 units/frame and gradually increases
- **Lane Count**: 3 playable lanes with perspective-based positioning
- **Spawn Rate**: Adaptive obstacle spawning based on game speed
- **Physics**: Gravity acceleration (0.7), jump velocity (-12.5), slide duration (22 frames)

## 🎮 Browser Compatibility

Works on all modern browsers supporting:
- HTML5 Canvas
- ES6 JavaScript
- CSS3 Gradients and Effects

## 💡 Tips for Players

- **React Quickly**: Speed increases as the game progresses
- **Plan Ahead**: Anticipate obstacle patterns
- **Use Slide Strategically**: Perfect timing on slides avoids collisions
- **Lane Awareness**: Watch other players and adjust your lane
- **Combo Coins**: Collect coin clusters for quick score boosts

## 📝 License

This project is open source and available for personal and educational use.

## 🤝 Contributing

Feel free to fork, modify, and enhance the game! Some ideas:
- Add sound effects and music
- Implement power-ups
- Create different game modes
- Add difficulty levels
- Develop a scoring leaderboard

## 👨‍💻 Author

**prasantat05** - Game Developer

---

**Enjoy the neon! 🎮✨**
