# Animated Flower Project with Turtle

This project generates an animated flower using the **Turtle** library in Python. It is based on the original project [Flor-Amarilla](https://github.com/victorllcrc/Flor-Amarilla/tree/master), but we added a new functionality that allows displaying an animated text in the center of the flower.

## Description

The original project generates a flower with colorful petals and a pattern in the center using circles and mathematical formulas. Our modification adds the ability to write a name or text in the center of the flower, and it appears with an animation, letter by letter.

## Features

- **Flower Generation**: Using loops and the `circle()` function from Turtle, colorful petals are created around a center based on the Fermat spiral sequence.
- **Text Animation**: We added a new functionality to display custom text in the center of the flower. The text appears gradually, letter by letter, with a small delay between each letter.

## Libraries Used

- **Turtle**: Used to draw graphics on the screen.
- **Colorsys**: Converts HSV values to RGB to generate custom colors.
- **Math**: For mathematical calculations used in the design of the flower's center and petals.

## How It Works

1. **Petals**: Petals are drawn around a central point using nested loops to create multiple colorful curves.
2. **Flower's Center**: The center is generated using the Fermat spiral sequence to simulate a pattern similar to the arrangement of seeds in sunflowers.
3. **Animated Text**: After the flower is drawn, the program writes custom text in the center. The text appears letter by letter, creating an animation effect.

## Instructions

To run the program, you need to have **Python 3.x** installed along with the **Turtle** library, which is included by default in Python.

Run the Python file containing the code to see the generated flower and the text animation.

## Modifications

This project is based on the original [Flor-Amarilla](https://github.com/victorllcrc/Flor-Amarilla/tree/master) project. We have added a new feature to animate custom text in the center of the flower. The rest of the code, such as the generation of petals and the flower's center, remains similar to the original project.
