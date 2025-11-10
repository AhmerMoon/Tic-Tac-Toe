# Tic Tac Toe - Paper Style Edition 🎮

A beautifully designed, responsive Tic Tac Toe game with a paper-style aesthetic and Urdu language support. Built with pure HTML, CSS, and JavaScript.

![Tic Tac Toe](https://img.shields.io/badge/Game-Tic%20Tac%20Toe-blue) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features

- 🎨 **Paper-style Design**: Clean, minimalist interface with paper-inspired borders
- 🌍 **Urdu Language Support**: Fully localized with Urdu text and instructions
- 📱 **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- 🎯 **Interactive Gameplay**: Smooth animations and visual feedback
- 🎉 **Win Celebrations**: Confetti animation and winning line highlight
- 👥 **Player Names**: Customizable player names with input modal
- 🔄 **Demo Mode**: Automatic demo animation on the start screen
- ⚡ **No Dependencies**: Pure vanilla JavaScript (except Tailwind CSS for styling)

## 🎮 How to Play

1. **Start the Game**: Click "Khelain!" (Play) button
2. **Enter Names**: Input player names (optional - defaults to "Khiladi 1" and "Khiladi 2")
3. **Take Turns**: 
   - Player 1 (X) goes first with red-pink symbols
   - Player 2 (O) follows with light blue symbols
4. **Win Condition**: Get three of your symbols in a row (horizontal, vertical, or diagonal)
5. **Celebrate**: Watch the confetti and winning line animation when someone wins!
6. **Play Again**: Click "Dobara Khelain" to restart

## 🛠️ Technologies Used

- **HTML5**: Semantic structure and game layout
- **CSS3**: 
  - Custom animations and transitions
  - Responsive grid layout
  - Paper-style border design
  - Dark theme with vibrant colors
- **JavaScript (ES6)**: 
  - Game logic and state management
  - DOM manipulation
  - Event handling
  - Animation controllers
- **Tailwind CSS**: Utility-first CSS framework for rapid styling

## 🎨 Design Features

### Visual Elements
- **Dark Theme**: Easy on the eyes with `#1a1b26` background
- **Color Scheme**: 
  - X Symbols: `#f7768e` (Red-pink)
  - O Symbols: `#7dcfff` (Light blue)
  - Winning Elements: `#9ece6a` (Green)
  - Accent Colors: `#bb9af7` (Purple)
- **Typography**: Inter font family for clean readability
- **Animations**: 
  - Pulsating title
  - Smooth symbol transitions
  - Winning line drawing
  - Confetti celebration

### Responsive Design
- **Flexible Grid**: CSS Grid with `clamp()` for responsive sizing
- **Mobile-First**: Optimized for touch interactions
- **Adaptive Text**: Responsive font sizes and spacing

## 🚀 Installation & Usage

### Quick Start
Simply open the `index.html` file in any modern web browser!

### For Development
1. Clone or download the project files
2. Open `index.html` in your preferred code editor
3. Make modifications as needed
4. Test in your browser

### File Structure
```
tic-tac-toe/
├── index.html          # Main game file
└── README.md          # Project documentation
```

## 🎯 Game Logic

### Win Conditions
The game checks for 8 possible winning combinations:
```javascript
const winConditions = [
    [0, 1, 2], [3, 4, 5], [6, 7, 8], // Rows
    [0, 3, 6], [1, 4, 7], [2, 5, 8], // Columns
    [0, 4, 8], [2, 4, 6]             // Diagonals
];
```

### Features
- **Smart State Management**: Tracks game state, current player, and cell occupancy
- **Input Validation**: Prevents invalid moves and overwrites
- **Draw Detection**: Automatically detects tied games
- **Player Turn Management**: Alternates between players seamlessly

## 🌐 Browser Compatibility

- ✅ Chrome (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile Browsers

## 🔧 Customization

### Easy Modifications
- **Language**: Change text content in HTML and JavaScript
- **Colors**: Modify CSS custom properties in the `<style>` section
- **Animations**: Adjust timing and effects in CSS `@keyframes`
- **Game Rules**: Modify win conditions in the `winConditions` array

### Styling Options
- Change color scheme in the CSS variables
- Modify board size by adjusting `clamp()` values
- Update animations in the `@keyframes` sections
- Customize confetti colors and behavior

## 🤝 Contributing

Feel free to fork this project and submit pull requests for:
- Additional language translations
- New game modes
- Enhanced animations
- Sound effects
- Score tracking features

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🎊 Enjoy Playing!

Whether you're a casual player or a developer looking to learn, this Tic Tac Toe implementation offers both fun gameplay and clean, educational code. Happy gaming! 🎮

---

*Built with 💜 using vanilla web technologies*
