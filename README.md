# Simple GUI Project Using Tkinter

A collection of simple desktop applications built with **Python** and the **Tkinter** GUI framework. These projects are part of a daily learning challenge (Days 29–31).

## Projects

| File | Application |
|------|-------------|
| `day29.py` | Greeting App — enter your name and get a personal greeting |
| `day30.py` | Click Counter — count clicks with reset and exit buttons |
| `day31.py` | BMI Calculator — calculate your Body Mass Index and weight status |

## Features

### day29.py — Greeting App
- Enter your name and click **Greet Me** to see a personalized greeting
- **Reset** clears the name field and the greeting
- Validates empty input and prompts you to enter a name

### day30.py — Click Counter
- **Click Me** increments the counter
- **Reset** sets the counter back to 0
- **Exit** closes the application

### day31.py — BMI Calculator
- Inputs: weight in kilograms (kg) and height in meters (m)
- Computes BMI and shows the corresponding weight status:
  - Underweight (< 18.5)
  - Normal weight (18.5 – 24.9)
  - Overweight (25 – 29.9)
  - Obesity (≥ 30)
- Shows an error message if the input is invalid or non-positive

## Requirements

1. [Python 3](https://www.python.org/downloads/) (3.x)
2. Tkinter — included with the Python standard library on most installations

## How to Run

Clone the repository and run any script:

```bash
git clone https://github.com/Plabon-Basak/Simple_GUI_Project.git
cd Simple_GUI_Project

python day29.py
python day30.py
python day31.py
```

## Components

1. Python
2. Tkinter Framework Library