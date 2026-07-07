# Calculator_webJS

# Calculator

A simple, clean calculator web application built with HTML, CSS, and JavaScript.

## Overview

This is a functional calculator app that performs basic arithmetic operations. It features a modern dark theme with a light green background and intuitive button layout.

## Features

- **Basic Operations**: Addition (+), subtraction (-), multiplication (*), and division (/)
- **Number Input**: Buttons for digits 0-9
- **Decimal Support**: Ability to perform calculations with decimal numbers
- **Clear Function**: AC button to clear the entire display
- **Delete Function**: DEL button to remove the last entered digit
- **Equals Function**: Calculates and displays the result of your expression

## File Structure

```
Calculator/
├── index.html    # Main HTML file with calculator layout and functionality
├── style.css     # Styling for the calculator interface
└── README.md     # This file
```

## How to Use

1. Open `index.html` in your web browser
2. Click number buttons to enter values
3. Click operator buttons (+, -, *, /) to select an operation
4. Click "=" to calculate the result
5. Use "AC" to clear the display or "DEL" to remove the last digit

## Technical Details

- **HTML**: Defines the calculator layout using form inputs and buttons
- **CSS**: Provides styling with a dark theme (dark gray background with cyan-colored operators)
- **JavaScript**: Uses inline onclick handlers to manage button inputs and the `eval()` function to calculate results

## Design

The calculator features:
- Responsive dark theme with light green background
- Cyan-colored operator buttons for easy identification
- Large, clear display for easy number visibility
- Smooth button interactions with shadow effects

## Browser Compatibility

Works in all modern browsers that support HTML5, CSS3, and JavaScript ES5+.

## Note

The calculator uses the `eval()` function for calculation. For production use, consider implementing a proper expression parser for better security and error handling.
