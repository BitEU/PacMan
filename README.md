# 🚨 IMPORTANT ATTRIBUTION 🚨

## ⚡ THIS IS A LIGHTLY MODIFIED VERSION OF THE ORIGINAL REDDIT POST ⚡

**Original Source:** https://www.reddit.com/r/Batch/comments/lyj3i0/pacman_in_pure_batch/

This project is based on the amazing work shared by the original author on Reddit. All credit for the core implementation goes to the original creator. This repository contains only minor modifications to the original code.

---

# 🎮 PacMan in Pure Batch

A fully functional PacMan game implemented entirely in Windows Batch scripting! This project demonstrates the incredible capabilities of batch scripting by recreating the classic arcade game using only native Windows commands.

## 🌟 Features

- **Pure Batch Implementation**: Written entirely in Windows Batch (.bat) files
- **Full Game Mechanics**: 
  - Player movement with WASD controls
  - Ghost AI with different behaviors
  - Pellet collection and scoring
  - Power pellets that make ghosts vulnerable
  - Three difficulty levels (Easy, Normal, Hard)
- **Visual Effects**: 
  - Colorful ASCII graphics
  - Animated characters
  - Real-time score display
  - Game over screen
- **Advanced Batch Techniques**:
  - ANSI escape sequences for colors and positioning
  - Delayed variable expansion
  - Complex string manipulation
  - Multi-process architecture (separate control and game processes)

## 🎯 How to Play

1. **Run the Game**: Double-click `pacman.bat` or run it from the command line
2. **Select Difficulty**: 
   - Press `A` for Easy
   - Press `B` for Normal  
   - Press `C` for Hard
3. **Controls**:
   - `W` - Move Up
   - `A` - Move Left
   - `S` - Move Down
   - `D` - Move Right
4. **Objective**: 
   - Collect all the small pellets (•) to score points
   - Eat power pellets (○) to temporarily make ghosts vulnerable
   - Avoid the ghosts (unless they're vulnerable)
   - Try to achieve the highest score possible!

## 🚀 Getting Started

### Prerequisites

- Windows operating system
- Command Prompt or PowerShell
- No additional software required!

### Installation

1. Clone this repository:
   ```powershell
   git clone https://github.com/BitEU/PacMan.git
   cd PacMan
   ```

2. Run the game:
   ```powershell
   .\pacman.bat
   ```

## 🎨 Technical Highlights

This implementation showcases advanced batch scripting techniques:

- **ANSI Color Support**: Uses ANSI escape sequences for colorful graphics
- **Real-time Input**: Implements non-blocking input handling
- **Game Loop**: Maintains consistent frame timing
- **Collision Detection**: Handles wall and ghost collisions
- **AI Behavior**: Ghosts have different movement patterns
- **State Management**: Tracks game state, scores, and ghost modes

## 🎮 Game Elements

- **Player (█)**: Yellow Pac-Man character
- **Ghosts (▓)**: 
  - Blinky (Red)
  - Inky (Cyan) 
  - Pinky (Pink)
  - Clyde (Orange)
- **Pellets (•)**: Small dots worth 10 points each
- **Power Pellets (○)**: Large dots worth 50 points, make ghosts vulnerable
- **Walls (█)**: Blue maze boundaries

## 🏆 Scoring

- Small pellets: 10 points each
- Power pellets: 50 points each
- Eating vulnerable ghosts: 200 points each

## 🛠️ Code Structure

- **Main Game Loop**: Handles player input, ghost movement, and collision detection
- **Map Creation**: Dynamically generates the game maze
- **Control System**: Separate process for handling user input
- **Graphics Engine**: ANSI escape sequence-based rendering system

## 📝 License

I licensed this project under the MIT License - see the [LICENSE](LICENSE) file for details. ANY LICENSING BY THE ORIGINAL AUTHOR SUPERCEDES MY LICENSE.

## 🙏 Credits

**Original Implementation**: Created by the amazing developer who shared this on Reddit
- **Reddit Post**: https://www.reddit.com/r/Batch/comments/lyj3i0/pacman_in_pure_batch/
- **Original Author**: All credit goes to the original Reddit poster

**This Repository**: Contains only minor modifications and improvements to the original code.

## 🐛 Known Issues

- Game requires Windows with ANSI support (Windows 10 version 1511 or later)
- May not work properly in some terminal emulators
- Font size is automatically adjusted for optimal display

## 🤝 Contributing

Since this is based on someone else's original work, please:
1. Respect the original author's contribution
2. Submit pull requests for bug fixes or improvements
3. Credit the original Reddit post in any derivatives

## 📸 Screenshots

*Note: Screenshots may not properly display the colors and animations - the game looks much better when running!*

## 🎪 Fun Facts

- This game demonstrates that batch scripting can create surprisingly complex applications
- The entire game runs without any external dependencies
- Uses creative workarounds for batch scripting limitations
- Showcases the power of Windows batch for more than just simple automation

---

**Remember**: This is a modified version of the original Reddit post. Please check out the original link to appreciate the incredible work of the original author!
