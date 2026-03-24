# Odin Calculator

Preview: https://frederic-merkl.github.io/Odin-Calculator/

This is my second independent frontend project that I implemented entirely on my own.

A functional, calculator built with Vanilla JavaScript. This project focuses on implementing calculation logic and handling user inputs via both DOM events and a global keyboard interface.

## Core Features

- **Mathematical Operations:** Full implementation of basic arithmetic (addition, subtraction, multiplication, division).

## Technical Implementation

### Event Handling & Keyboard Support
The project utilizes a central `handleInput` function that processes both physical clicks and global `keydown` events. Mapping is handled via `value` attributes and CSS selectors.

### Display Control
- **Dynamic Formatting:** The `updateDisplayText` function manages string manipulation and ensures proper truncation for long results.
- **Visual Feedback:** The `addGlow` logic provides immediate visual confirmation for every input (flash effect).


### UI Design
- **Layout:** Flexbox-based button matrix.
- **Responsiveness:** Optimized interface for various viewport sizes.


