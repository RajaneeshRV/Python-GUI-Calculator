# Python GUI Calculator

A basic desktop calculator built with Python and Tkinter. Supports clickable buttons and keyboard input.

## Features

- Addition, subtraction, multiplication, and division
- Decimal numbers
- Clear and backspace buttons
- Keyboard support
- Error messages for invalid expressions and division by zero

## Requirements

- Python 3
- Tkinter

## How to Run

Open a terminal in the project folder and run:

```bash
python calculator.py
```

## Keyboard Controls

| Key | Action |
|---|---|
| 0–9 and +, -, *, /, . | Enter an expression |
| Enter or = | Calculate |
| Backspace | Delete the last character |
| Escape | Clear the display |

## Testing

Manually tested arithmetic operations, decimal calculations,
division by zero, invalid expressions, backspace, clear,
and keyboard input.

## What I Learned

- Creating a graphical interface with Tkinter
- Arranging widgets using frames and grid layouts
- Connecting buttons to functions
- Handling keyboard events
- Updating the display with StringVar
- Handling errors with try and except

## Limitations

The calculator uses Python's eval() function to evaluate expressions.

## Acknowledgments

The initial calculator was based on Bro Code's tutorial:
https://www.youtube.com/watch?v=5UQZNHlaUVc

I extended it with keyboard support, backspace functionality, and changes to the button layout.