# turtle-drawing-lab

## Overview

**turtle-drawing-lab** is a Python repository dedicated to exploring and learning the basics of computer graphics using the Turtle module. Turtle graphics is a popular way for beginners to get hands-on experience with programming concepts such as loops, functions, and event handling, all while making creative and visually engaging drawings.

This repository is designed for anyone new to Python or computer programming, as well as educators looking for engaging ways to introduce computational thinking and creativity in the classroom. By working through a series of fun and interactive drawing exercises, you'll gain a solid foundation in Python and graphical programming.

---

## Features

- **Beginner Friendly:** Clear examples and well-commented code to help you get started with Turtle graphics.
- **Creative Drawing:** Learn to draw shapes, patterns, spirals, and even simple animations.
- **Modular Scripts:** Each drawing or project is kept in a separate file for easy exploration.
- **Challenges & Exercises:** Practice tasks to extend your learning and creativity.
- **GNU GPL v3 License:** Open source and free to use, modify, and share.

---

## Getting Started

### Prerequisites

- Python 3.x (preferably 3.6 or above)
- `turtle` module (comes pre-installed with standard Python distributions)

### Running a Drawing Script

1. **Clone the repository:**
    ```bash
    git clone https://github.com/avro1199/turtle-drawing-lab/
    cd turtle-drawing-lab
    ```

2. **Run a sample drawing:**
    ```bash
    python Turtle_Draw.py
    ```

   Or try out other scripts in the repository!

---

## Repository Structure

- `README.md`         — Project overview and instructions
- `LICENSE`           — GNU General Public License v3.0
- `star.py`           — Example: Draws a colorful star
- `spiral.py`         — Example: Draws a spiral pattern
- `shapes.py`         — Example: Draws basic shapes (square, triangle, circle)
- `my_creations/`     — Folder for your own art and experiments
- `exercises.md`      — List of practice exercises and challenges

---

## Sample: Drawing a Star

```python
import turtle

t = turtle.Turtle()
t.color("red")
t.speed(3)
for i in range(5):
    t.forward(100)
    t.right(144)
turtle.done()
```

---

## Contributing

Feel free to fork the repository, add your own scripts to the `my_creations/` folder, or submit pull requests with improvements, new shapes, or exercises!

---

## License

This project is licensed under the [GNU General Public License v3.0 (GPL-3.0)](LICENSE).

---

## Acknowledgements

- Python Software Foundation for the `turtle` module.
- Educators and students worldwide for sharing creative Turtle projects and inspiration!
