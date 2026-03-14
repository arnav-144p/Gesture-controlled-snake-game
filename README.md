# Nokia Snake Game - Gesture Control

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://python.org)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.8+-green.svg)](https://opencv.org)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-0.10+-orange.svg)](https://mediapipe.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


A classic Nokia Snake game controlled by hand gestures via webcam using MediaPipe and OpenCV. 

## Features

### Classic Nokia Snake Game
- **Authentic Nokia-style graphics** with green monochrome theme
- **Grid-based movement** with rectangular snake segments
- **Growing snake** mechanics - snake grows when eating fruit
- **Collision detection** - game ends when hitting walls or self
- **Score tracking** - earn points by eating fruit
- **Smooth animations** with particle effects

### Hand Gesture Controls
- **MediaPipe hand tracking** for real-time gesture recognition
- **Swipe gestures** - move hand up/down/left/right to control snake direction
- **Pinch gesture** - bring thumb and index finger together for speed boost
- **Face detection** - shows your face in the gesture window
- **Visual feedback** - see hand landmarks and current direction

### Dual Window Interface
- **Game Window** - Classic Nokia Snake gameplay
- **Gesture Window** - Live webcam feed with hand tracking visualization


## Controls

### Hand Gestures
| Gesture | Action |
|---------|--------|
| **Swipe Up** | Move snake up |
| **Swipe Down** | Move snake down |
| **Swipe Left** | Move snake left |
| **Swipe Right** | Move snake right |
| **Pinch** (thumb + index) | Speed boost |

### Game Controls
- **ESC** - Quit game
- **Show UP gesture** when game over - Restart game
- **Q** in gesture window - Quit

## Game Mechanics

### Snake Behavior
- Snake moves continuously in the current direction
- Cannot move directly backward (prevents instant death)
- Speed increases when pinch gesture is detected
- Snake grows by one segment when eating fruit

### Scoring
- **+10 points** per fruit eaten
- Score displayed in top-left corner
- Final score shown on game over screen

### Game Over Conditions
- Snake hits the wall boundaries
- Snake collides with its own body
- Show UP gesture to restart

