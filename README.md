# 🐱Kitty Run

A charming 2D pixel-style platformer game built with vanilla HTML5 Canvas and JavaScript – no external libraries required! Help Whisker the cat collect all the fish across three unique levels while avoiding pesky mice and mastering wall jumps, double jumps, and tricky platform challenges.

![Game Screenshot](https://github.com/your-username/whiskers-fish-feast/assets/your-user-id/xxxxxxx) <!-- 替换为实际截图链接 -->

## ✨ Features

- **3 Unique Levels**: Grassland meadow, underground cave, and sky/cloud environments
- **Smooth Gameplay Mechanics**:
  - Responsive controls (keyboard + touch support for mobile)
  - Wall jumps and double jumps (unlocked in level 2)
  - Variable jump height (hold jump for higher jumps)
  - Wall sliding
- **Dynamic Elements**:
  - Moving platforms with animated indicators
  - Disappearing platforms (level 3)
  - Enemies (mice) that patrol and can be stomped for extra points
  - Collectible fish with satisfying sound effects and particle effects
- **Immersive Audio**: Procedurally generated sound effects using Web Audio API (no audio files!)
- **Visual Polish**:
  - Parallax backgrounds with environment-specific details (clouds, crystals, hills)
  - Particle effects (dust, sparkles, confetti)
  - Smooth camera follow with screen shake
  - Responsive design (works on desktop and mobile)
  - Touch controls for mobile devices
- **Game State Management**: Title screen, level transitions, victory/defeat states, lives system

## 🎮 How to Play

### Controls (Desktop)
- ←/A or →/D: Move left/right
- Space/W/↑: Jump (hold for higher jump, double tap for double jump)
- Wall Jump: Jump while sliding against a wall (press jump + opposite direction)

### Controls (Mobile)
- On-screen touch buttons for left/right movement
- Jump button (single tap for jump, double tap for double jump)
- 2x button for quick double jump

### Objective
1. Collect all fish in each level to unlock the exit
2. Avoid enemies (mice) or stomp on them from above
3. Reach the exit to progress to the next level
4. Complete all 3 levels to win!

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required – just open the HTML file!

### Local Play
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/whiskers-fish-feast.git
   cd whiskers-fish-feast
   ```
2. Open `index.html` in your web browser (double-click the file or use a local server)
3. Start playing!

### Live Demo
[Play Now](https://your-username.github.io/whiskers-fish-feast/) <!-- 替换为 GitHub Pages 链接 -->

## 🛠️ Technical Details

- **Built with**: Pure HTML5 Canvas + Vanilla JavaScript (ES6+)
- **Audio**: Web Audio API for procedural sound effects (jump, collect fish, hurt, victory, etc.)
- **Rendering**: Custom particle system, parallax backgrounds, sprite animations
- **Collision Detection**: Axis-aligned bounding box (AABB) collision with platform resolution
- **Responsive Design**: Dynamic canvas resizing with touch control fallback for mobile devices

## 📱 Mobile Support

The game includes fully functional touch controls that appear automatically on mobile devices:
- Left/right movement buttons (bottom left)
- Jump button (bottom right)
- Double jump shortcut button

## 🎨 Art Style

All graphics are rendered procedurally with Canvas API (no image assets!):
- Hand-drawn cat character with animated features (blinking, tail movement, running animation)
- Stylized fish with subtle animations
- Environment-specific backgrounds (clouds, hills, crystals, stars)
- Particle effects (dust when landing, sparkles when collecting fish, confetti for level completion)

## 🎵 Audio

All sound effects are generated in real-time using the Web Audio API:
- Jump sound (square wave with pitch ramp)
- Fish collection (dual sine wave arpeggio)
- Hurt/death sounds (sawtooth wave with pitch fall)
- Victory fanfare (multi-note square wave sequence)
- UI click sound

## 📋 Roadmap

Possible future improvements:
- [ ] Additional levels with new mechanics
- [ ] Save/load high scores
- [ ] Settings menu (audio toggle, control customization)
- [ ] More enemy types with unique behaviors
- [ ] Power-ups (speed boost, invincibility)
- [ ] Level editor
- [ ] Leaderboard system

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classic 2D platformers like Super Mario, Celeste, and Hollow Knight
- Built with love for retro game design and modern web technologies
- Special thanks to the Canvas API and Web Audio API communities

---

Made with ❤️ using vanilla JavaScript – no frameworks, no dependencies, just pure web fun!
