# Manim Animation Project

This project demonstrates the use of **Manim** (Mathematical Animation Engine) to create mathematical and visual animations using Python.

## Features

* Basic shape animations (Circle → Square transformations)
* Smooth transitions and object transformations
* Integration with **manim-voiceover** for narrated animations
* Visualization of mathematical concepts (e.g., Multiplicative Weights Update)

## Setup

Install dependencies:

```bash
sudo apt update
sudo apt install libcairo2-dev libpango1.0-dev ffmpeg freeglut3-dev pkg-config
pip install manim
```

(Optional for voiceover):

```bash
pip install manim-voiceover[gtts]
```

## Usage

Run a Manim scene:

```bash
manim -pql script.py SceneName
```

Or in Jupyter Notebook:

```python
%%manim -qm SceneName
```

## Contents

* Basic animation examples
* Voiceover-enabled scenes
* Mathematical visualization (Multiplicative Weights Algorithm)

## Goal

To explore **visual storytelling for mathematics and algorithms** using animations.

