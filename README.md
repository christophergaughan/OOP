# Object-Oriented Programming (OOP) Explorations

## Overview

This repository explores the core principles of Object-Oriented Programming (OOP) using Python. It’s meant to be a hands-on, beginner-friendly resource with practical code examples and Jupyter notebooks that walk through the fundamentals step by step.

It’s not meant to be perfect or exhaustive — just a genuine effort to make this sometimes-confusing topic a little more approachable. If it helps even one person wrap their head around classes, inheritance, or `@property`, then it's doing its job.

Whether you're new to OOP or brushing up your Python skills, this repo lays the groundwork for more advanced object-oriented design and software architecture.

## Repository Structure

| File/Notebook               | Description                                      |
|----------------------------|--------------------------------------------------|
| `7.1-class_property.py`    | Demonstrates class properties.                   |
| `7.2-representation.py`    | Explores object string representations.          |
| `7.3-representation.py`    | Continues work on object representation.         |
| `7.3-state.py`             | Covers managing object state.                    |
| `7.5-inheritance.py`       | Explains and demonstrates inheritance.           |
| `7.6-properties.py`        | Shows the use of `@property` decorators.         |
| `Class_cards.py`           | Implements card game logic using classes.        |
| `cards.py`                 | Supporting module for the card game example.     |
| `OOP_introduction.ipynb`   | Gentle notebook intro to OOP concepts.           |
| `OOP-tutorial.ipynb`       | Tutorial-style walkthrough of key OOP patterns.  |

## Objectives

- Build intuition for classes, instances, and methods.
- Understand encapsulation, inheritance, and polymorphism.
- Use decorators like `@property` for clean interfaces.
- Apply OOP concepts to practical, reusable code examples.

## Getting Started

To try things out locally:

```
# Clone the repo
git clone https://github.com/christophergaughan/OOP.git
cd OOP
```

# Optional: create a virtual environment
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

# Install dependencies if needed
`pip install -r requirements.txt`

# Run a Python script
`python 7.1-class_property.py`

# Or open notebooks
`jupyter notebook`

## Learning Outcomes

By working through this repo, you will:

- Write custom classes with meaningful `__init__`, `__str__`, and `__repr__` methods.
- Use inheritance to reduce redundancy and extend functionality.
- Protect and expose internal data cleanly using `@property` decorators.
- Build confidence writing clean, modular, and reusable code.

## External References

- Check out [Coding with Lewis](https://www.youtube.com/c/CodingwithLewis) for clear and engaging explanations of OOP concepts. for high-quality explanations of related concepts.
- This repo was inspired in part by lessons from structured online courses and has been adapted with personal insights and full respect for original creators.

### License
This project is licensed under the **MIT License**. See the LICENSE file for more details.
