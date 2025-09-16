# Simple Web Calculator

## Developer Details
**NAME**: P.Vineela
**Institution**: Ashoka womens engineering college
**Roll Number**:222T1A3144

A clean, responsive calculator built with HTML, CSS, and JavaScript that supports both mouse clicks and keyboard input.

![Calculator Demo](https://img.shields.io/badge/demo-live-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Features

- ✨ **Clean Interface**: Simple, intuitive calculator layout
- 🖱️ **Mouse Support**: Click buttons to perform calculations
- ⌨️ **Keyboard Support**: Type numbers and operators directly
- ↵ **Enter Key**: Press Enter to calculate results
- 🧮 **Math.js Integration**: Reliable mathematical expression evaluation
- 📱 **Responsive Design**: Works on desktop and mobile devices
- 🎨 **Custom Styling**: Professional blue theme with rounded buttons

## Demo

Try the calculator: [Live Demo](your-demo-link-here)

## Usage

### Mouse Input
- Click number buttons (0-9) to input digits
- Click operator buttons (+, -, *, /) for operations
- Click the decimal point (.) for floating-point numbers
- Click equals (=) or press Enter to calculate
- Click 'C' to clear the display

### Keyboard Input
- Type numbers (0-9) and operators (+, -, *, /) directly
- Press Enter to calculate the result
- The calculator automatically captures keyboard input when focused

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/simple-web-calculator.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd simple-web-calculator
   ```

3. **Open the calculator:**
   - Simply open `index.html` in your web browser
   - Or serve it using a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```

## Technologies Used

- **HTML5**: Structure and layout
- **CSS3**: Styling and responsive design
- **JavaScript**: Calculator logic and event handling
- **Math.js**: Mathematical expression evaluation library

## File Structure

```
calculator/
│
├── index.html          # Main calculator interface
├── README.md           # Project documentation
└── assets/             # (Optional) Images/screenshots
    └── screenshot.png
```

## Code Highlights

### Mathematical Expression Evaluation
The calculator uses the Math.js library for safe and accurate expression evaluation:

```javascript
function solve() {
    let x = document.getElementById("result").value
    let y = math.evaluate(x)
    document.getElementById("result").value = y
}
```

### Keyboard Event Handling
Supports both individual key presses and Enter key for calculation:

```javascript
function myFunction(event) {
    if (event.key == '0' || event.key == '1' || /* ... other keys ... */) {
        document.getElementById("result").value += event.key;
    }
}
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Future Enhancements

- [ ] Scientific calculator functions (sin, cos, log, etc.)
- [ ] Memory functions (M+, M-, MR, MC)
- [ ] Calculation history
- [ ] Theme customization
- [ ] Unit conversions
- [ ] Parentheses support for complex expressions



⭐ If you found this project helpful, please give it a star!
