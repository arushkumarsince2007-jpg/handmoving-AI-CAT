# AI Hand Mirroring Cat 🐱

## Overview
This project uses MediaPipe and a webcam to track the user's hand movement and animate a cat on a canvas. The cat's paw follows the user's hand in real-time.

## Features
- Real-time hand tracking using MediaPipe
- Animated cat that mirrors the user's hand movement
- Canvas rendering for smooth animation

## Code Structure
- `index.html`: The main HTML file containing the video and canvas elements
- `script.js`: The JavaScript code for hand tracking and animation

## How it Works
1. The user's webcam feed is captured and displayed on the video element.
2. MediaPipe's Hand tracking API is used to detect the user's hand landmarks.
3. The cat is drawn on the canvas, with its paw following the user's hand movement.
4. The animation is updated in real-time using `requestAnimationFrame`.

## Setup
1. Clone the repository
2. Open `index.html` in a web browser
3. Allow access to the webcam

## Dependencies
- MediaPipe Hand tracking API
- Camera Utils library

## Notes
- This project is for demonstration purposes only.
- Make sure to allow webcam access when prompted.

Would you like me to add any specific details to the README?
