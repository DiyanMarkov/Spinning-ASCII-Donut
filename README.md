# `🍩 Spinning-ASCII-Donut 🍩`

## `Description`

Generates an animated 3D representation of a torus (a donut-shaped object) using ASCII characters and the Pygame library. The torus is created by applying mathematical transformations to calculate its 3D coordinates and projecting them onto a 2D screen.

## `Features`

* **Torus Generation:** The script computes the 3D coordinates of points on the surface of a torus by iterating over angles (theta and phi) and applying trigonometric functions. These coordinates are then projected onto a 2D screen using perspective projection.

* **Rendering:** ASCII characters are used to represent the surface of the torus. The luminance of each character is determined based on the angle of incidence of light hitting the torus. Characters with higher luminance are used to represent areas with more light, while characters with lower luminance represent darker areas.

* **Animation:** The script continuously updates the torus's rotation angles (A and B) to create an animated effect. The animation can be paused and resumed by pressing the space bar.

* **User Interaction:** The user can exit the application by closing the window or pressing the escape key.

## `Built with`

* **Python:** The core programming language used for scripting and logic implementation.

* **Pygame:** Pygame is a cross-platform set of Python modules designed for writing video games. It provides functionality for handling windowing, rendering, and user input, making it suitable for creating interactive graphical applications like this 3D torus animation.

* **Math Module:** The math module in Python provides mathematical functions for performing operations like trigonometry (e.g., cos, sin), which are essential for calculating the 3D coordinates of points on the torus surface.

* **Colorsys Module:** The colorsys module provides functions for converting between various color representations. In this script, it is used to convert colors from the HSV (Hue, Saturation, Value) color space to RGB (Red, Green, Blue) color space for rendering.

* **Operating System Module (os):** The os module provides a way of using operating system-dependent functionality. In this script, it's used to set the environment variable to center the Pygame window on the screen.

## `Dependencies`

* **Python:** Ensure you have Python installed on your system. You can download and install Python from the official Python website: python.org.
* **Pygame:** Optionally, if Pygame is not already installed on your system, you would need to install it using a package manager like pip:
`pip install pygame`
This command will install Pygame and its dependencies, allowing you to run the script successfully.

## Preview

![FPS_9 252024-02-0610-39-30-ezgif com-crop (1)](https://github.com/DiyanMarkov/Spinning-ASCII-Donut/assets/121679485/c3757cf3-159e-404e-96ad-e11fd398209f)

## 🧠 All the math explained:

### https://www.a1k0n.net/2011/07/20/donut-math.html
