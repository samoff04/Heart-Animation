# Python Heart Animation

A colorful heart animation built with Python's Turtle graphics and mathematical heart equations.

## Features

* Mathematical heart curve
* Radial drawing animation
* Randomized colors
* Starburst effect
* No external dependencies

## Tech Stack

**Python · Turtle · Math · Random**

## Run Locally

```bash
git clone https://www.github.com/samoff04/Heart-Animation.git
cd Heart-Animation
python main.py
```

## How It Works

The heart shape is generated using a mathematical parametric equation:

```text
x = 16sin³(t)

y = 13cos(t) - 5cos(2t) - 2cos(3t) - cos(4t)
```

The program calculates points around the curve and uses Turtle to draw lines from the center, creating the colorful heart effect.

## Project Structure

```text
Heart-Animation/
├── heart_animation.py
├── README.md
└── .gitignore
```

## Author

Samarth Varshney