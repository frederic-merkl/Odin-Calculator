# Odin Calculator

[![Live Demo](https://frederic-merkl.github.io/Odin-Calculator/)

A functional, state-based calculator built with Vanilla JavaScript. This project focuses on implementing robust calculation logic and handling user inputs via both DOM events and a global keyboard interface.

## Core Features

- **Mathematical Operations:** Full implementation of basic arithmetic (addition, subtraction, multiplication, division).
- **State Management:** Logical separation of `firstNumber`, `secondNumber`, and `operator` to support chained operations.
- **Input Validation:** - 9-digit limit to prevent layout overflows.
  - Dynamic decimal point logic to prevent multiple entries.
  - Division-by-zero protection with error handling.
- **Advanced Logic:** Integrated percentage calculation and sign toggling (±).

## Technical Implementation

### Event Handling & Keyboard Support
The project utilizes a central `handleInput` function that processes both physical clicks and global `keydown` events. Mapping is handled via `value` attributes and CSS selectors, ensuring a DRY (Don't Repeat Yourself) approach for different input sources.

### Display Control
- **Dynamic Formatting:** The `updateDisplayText` function manages string manipulation and ensures proper truncation for long results.
- **Visual Feedback:** The `addGlow` logic provides immediate visual confirmation for every input (flash effect).
- **Context-Sensitive UI:** Dynamic switching between `AC` (All Clear) and `C` (Clear) based on the current input state.

### UI Design
- **Layout:** Grid-based button matrix for structural stability.
- **Responsiveness:** Optimized interface for various viewport sizes.

## Installation & Usage

1. Clone the repository:
   ```bash
   git clone [https://github.com/frederic-merkl/Odin-Calculator.git](https://github.com/frederic-merkl/Odin-Calculator.git)
