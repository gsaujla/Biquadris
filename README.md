# 🌟 **Biquadris** 🌟

Welcome to **Biquadris** – a competitive twist on the classic game Tetris! Built as a project for **CS246 (Fall 2024)** at the University of Waterloo, this game brings a strategic, turn-based, two-player experience to life using C++ and object-oriented design principles.

## 🎮 **Game Overview**

Biquadris is played on **two boards**, each **11 columns wide** and **15 rows high**. Players take turns dropping **tetrominoes** (blocks of 4 cells) onto their boards. The key twist? **It's not real-time** – you can take your time to strategize your moves. The first player to run out of space loses!

### **Key Differences from Tetris:**
- ⏳ **Turn-Based Play**: No rush! Plan your moves carefully.
- 🥳 **Special Actions**: Clear multiple rows at once to trigger actions that disrupt your opponent!
- 🌊 **Dynamic Difficulty**: Choose from multiple levels, each with unique challenges.

## 📈 **Features**

- 📏 **Multiple Difficulty Levels:**
  - **Level 0**: Non-random blocks from sequence files for predictable gameplay.
  - **Level 1-4**: Increasing randomness and additional challenges like "heavy" blocks and obstructive single-cell blocks!

- 🛠️ **Special Actions:**
  - **blind**: Hide part of your opponent’s board with question marks!
  - **heavy**: Make your opponent’s blocks fall faster!
  - **force**: Choose the next block your opponent must play!

- 📺 **Dual Display Modes:**
  - **Text-Based**: Simple and clean ASCII rendering.
  - **Graphical**: Color-coded blocks with a visually pleasing UI.

- 🕹️ **Flexible Command System:** Supports command shortcuts and multipliers (e.g., `3ri` to move right three times).

- 🤖 **AI Bot:** Compete against a bot built using **Design Patterns** like **Decorator**, **Observer**, and **Factory Method** for intelligent and dynamic gameplay.

## 🔢 **Gameplay Commands**
- `left`, `right`, `down`: Move blocks.
- `clockwise`, `counterclockwise`: Rotate blocks.
- `drop`: Drop the current block to the bottom.
- `levelup`, `leveldown`: Adjust game difficulty.
- `restart`: Restart the game.
- `I`, `J`, `L`, `O`, `S`, `Z`, `T`: Replace the current block with a specific type.

### **Multipliers & Shortcuts:**
Use multipliers to repeat actions (e.g., `3ri` moves right 3 times). Partial commands like `lef` for `left` are supported.

## 🌟 **Scoring System**
- **Line Clears**: `(current level + number of lines cleared)²`
- **Block Clears**: `(level when block was generated + 1)²`
- **High Score**: Persisted until the game exits.

## 💡 **Potential Enhancements**
If you’ve mastered the base game, consider adding:
- New block types or levels.
- Additional special actions.
- Enhanced graphical features or animations.

## 🚀 **Getting Started Tips**
- Start with **text-based mode** to test core game mechanics.
- Gradually implement **graphics** after the logic is solid.
- Test frequently to ensure stable progress.

## 📅 **Project Info**
- **Course**: CS246 - Object-Oriented Programming in C++
- **Term**: Fall 2024
- **Instructors**: Godfrey, Lushman, Schmitz

---

🚀 **Ready to challenge your friends?** Let the Biquadris battles begin!

📉 **License**: [Specify your license here]

📢 **Feedback & Contributions:** PRs and suggestions are welcome!

---

⚠️ **Note:** As per university guidelines, sharing or distributing the source code is prohibited.

