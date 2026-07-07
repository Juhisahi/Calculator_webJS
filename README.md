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

The calculator features a modern, polished dark theme with several visual enhancements:

- **Gradient Background**: Smooth gradient blend from soft green to light blue
- **Layered Shadows**: Multiple shadow layers create depth and dimension
- **Modern Buttons**: Rounded buttons with gradient backgrounds and smooth animations
- **Interactive Effects**: 
  - Hover effect lifts buttons up for visual feedback
  - Click effect depresses buttons for tactile feel
  - Smooth transitions (0.3s) for all interactions
- **Cyan Accent Color**: Operator buttons and equals button in vibrant cyan (#33ffd8)
- **Large Display**: Clear, easy-to-read large font (48px) with enhanced letter-spacing
- **Professional Polish**: Refined padding, improved typography, and modern aesthetics

## Styling Features

The calculator utilizes advanced CSS techniques:

- **Gradient Overlays**: Linear and radial gradients for visual depth
- **Box Shadows**: Inset and outer shadows for 3D effect
- **CSS Transitions**: Smooth animations on button interactions
- **Transform Effects**: translateY animations for button feedback
- **Backdrop Filters**: Subtle blur effects for a modern look
- **Font Weights**: Varied font weights (600-700) for visual hierarchy

## Browser Compatibility

Works in all modern browsers that support:
- HTML5 and CSS3
- JavaScript ES5+
- CSS Gradients and Transitions
- Transform and Animations

## Note

The calculator uses the `eval()` function for calculation. For production use, consider implementing a proper expression parser for better security and error handling.

The calculator displays numbers and operations clearly on a large, easy-to-read display with a dark theme interface.
