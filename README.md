# Calculator

A lightweight browser-based calculator built with vanilla JavaScript (`Calculator` class) that supports basic arithmetic, decimal input, digit deletion, all-clear reset, comma-formatted numbers, and a persistent dark/light theme toggle stored in `localStorage`.

## Features

- **Basic Arithmetic**: Addition (`+`), subtraction (`-`), multiplication (`×`), and division (`÷`), including chained operations when selecting a new operator.
- **Decimal & Backspace Support**: Prevents duplicate decimal points in the current operand and removes the last character with `delete()`.
- **Number Formatting**: Formats integer parts with thousands separators (`en` locale) while preserving decimal digits.
- **Persistent Theme Toggle**: Switches `dark-mode` on `document.body`, updates the sun/moon SVG icon, and saves the preference under `'calculator-theme'` in `localStorage`.
