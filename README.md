# Coding Assignment 3 - Pac-Man Animation

## Overview

This project is a simple web-based animation featuring a Pac-Man character that moves horizontally across the screen, changing its appearance as it moves left and right. The project demonstrates the use of HTML, CSS, and JavaScript to create interactive web components.

## Features

- Starts the animation when the "START" button is clicked.
- The Pac-Man character moves back and forth across the screen.
- Changes its appearance during movement using two sets of images (one for moving right and one for moving left).

## Requirements

To run this project, you need:
- A web browser (Chrome, Firefox, Safari, etc.)
- Access to local files or a web server to serve the HTML file

## Files Included

- `index.html`: The main HTML file containing the structure and scripts for the game.
- `PacMan1.png`, `PacMan2.png`, `PacMan3.png`, `PacMan4.png`: Image files representing the Pac-Man character in various states.

## How to Run

1. Clone or download this repository to your local machine.
2. Ensure that the image files (`PacMan1.png`, `PacMan2.png`, `PacMan3.png`, `PacMan4.png`) are in the same directory as the `index.html`.
3. Open the `index.html` file in your web browser.
4. Click the "START" button to begin the animation.

## How It Works

- The JavaScript code initializes the image sources for the Pac-Man character and sets up intervals to update the character's position and image source continuously.
- The position of the character changes based on a velocity (`vel`) that reverses when the character reaches the edges of the window.
- Image sources are alternated based on the current movement direction of the character.

## Future Improvements

- Add keyboard controls to start or stop the animation.
- Include additional features like scoring or obstacles.
- Improve the visual design and layout of the game.

## License

This project is open-source and available for anyone to use and modify under the MIT License.
