# 🎮 Simon Game

A browser-based implementation of the classic Simon memory game built with JavaScript and jQuery.

## 📖 About

Simon is a memory game where players must repeat an increasingly long sequence of colors. The game generates a random color pattern, and the player must click the colored buttons in the correct order. Each successful round adds another color to the sequence, making it progressively more challenging.

## ✨ Features

- **Progressive Difficulty**: Each level adds one more step to the sequence
- **Visual Feedback**: Buttons flash and animate when pressed
- **Audio Cues**: Each color has a unique sound effect
- **Game Over Animation**: Visual feedback when the player makes a mistake
- **Keyboard Start**: Press any key to begin the game
- **Level Tracking**: Displays current level to track progress

## 🎯 How to Play

1. Press any key to start the game
2. Watch the sequence of colors that flash
3. Click the colored buttons in the same order
4. Each round adds one more color to remember
5. The game ends when you click the wrong color
6. Press any key to restart after game over

## 🛠️ Technologies Used

- **HTML5**: Structure and layout
- **CSS3**: Styling and animations
- **JavaScript (ES5)**: Game logic and functionality
- **jQuery**: DOM manipulation and event handling

## 📁 Project Structure

simon-game/
│
├── index.html # Main HTML file
├── styles.css # CSS styling and animations
├── game.js # Game logic (this file)
└── sounds/ # Audio files directory
├── red.mp3
├── blue.mp3
├── green.mp3
├── yellow.mp3
└── wrong.mp3


## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Audio files (red.mp3, blue.mp3, green.mp3, yellow.mp3, wrong.mp3) in the `sounds/` directory

### Installation

1. Clone the repository:
cd simon-game-javascript

3. Open `index.html` in your web browser

Or simply visit the live demo: [Add your GitHub Pages link here]

## 🎮 Game Logic

- **Pattern Generation**: Uses `Math.random()` to select colors randomly
- **Input Validation**: Compares user clicks with the game pattern in real-time
- **Level Progression**: Automatically advances after successful sequence completion
- **State Management**: Tracks game state, level, and patterns using global variables

## 🔧 Key Functions

- `nextSequence()`: Generates the next color in the pattern and advances the level
- `checkAnswer()`: Validates user input against the game pattern
- `playSound()`: Plays audio feedback for button presses
- `animatePress()`: Provides visual feedback for button interactions
- `startOver()`: Resets the game state for a new round

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](link-to-issues).

## 📝 License

This project is [MIT](LICENSE) licensed.

## 👤 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)

## 🙏 Acknowledgments

- Inspired by the classic Simon electronic game (1978)
- Sound effects: [Add source if applicable]
- Built as part of [course/tutorial name if applicable]

## 📸 Screenshots

[Add screenshots of your game here]

---

⭐ **Star this repository if you found it helpful!**
