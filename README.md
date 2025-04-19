# Arduino Calculator

## Project Description

This is a mini-calculator built using Arduino that supports basic mathematical operations. The calculator includes an LCD display and a 4x4 keypad and can handle expressions with operator precedence (`+`, `-`, `*`, `/`). The device is capable of operating independently from battery power, making it portable and practical.


## Objectives

- Develop a working calculator on the Arduino platform
- Support operator precedence for arithmetic expressions
- Allow battery-powered standalone operation
- Provide a user interface through LCD and Keypad
- Dynamically evaluate user-entered expressions


## Key Features

- [x] Supports arithmetic operations: `+`, `-`, `*`, `/`
- [x] Handles operator precedence (`*` and `/` take precedence over `+` and `-`)
- [x] Clear input functionality using the `C` button
- [x] Displays the current expression and final result
- [x] Supports floating-point numbers (e.g., `2.5 + 1.3`)
- [x] Detects division by zero
- [x] User interface via LCD and 4x4 Keypad
- [x] Operates independently using battery power
- [x] Modular and structured code
- [x] Includes comments for main functions



## Sample Expressions

| Input             | Result  |
|------------------|---------|
| `2+3*4`          | `14`    |
| `6+4/2*3`        | `12`    |
| `10/0`           | `Error` |
| `5.5+2.25`       | `7.75`  |
| `1+2+3+4+5`      | `15`    |


## Hardware Components

- Arduino Uno or Nano
- 16x2 LCD Display (I2C interface)
- 4x4 Matrix Keypad
- Jumper Wires
- Breadboard
- Power Supply (Power Bank or 6V Battery Pack)



## Code Structure

```cpp
void loop() { ... }                    // Main program loop
evaluate()                            // Evaluates entire expression
processMulDiv() / processAddSub()     // Handles operator precedence
findStart() / findEnd()               // Locates numbers within the expression


## Examples
![photo_5195280316728732567_y](https://github.com/user-attachments/assets/f0b2be20-7510-4b71-8ec2-ac4f65b17e3b)

