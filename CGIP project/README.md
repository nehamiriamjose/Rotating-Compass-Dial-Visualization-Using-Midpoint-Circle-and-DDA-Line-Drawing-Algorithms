# Rotating Compass Dial - CGIP Animation

A Java-based animated visualization of a rotating compass dial using classical computer graphics algorithms.

## Features

- **Animated Compass**: Watch a continuously rotating compass dial with smooth animation
- **Midpoint Circle Algorithm**: Uses the efficient midpoint circle algorithm to draw circular shapes
- **DDA Line Algorithm**: Implements the Digital Differential Analyzer (DDA) line drawing algorithm for precision
- **Multi-layered Design**: Features multiple concentric circles and rotating cardinal direction indicators
- **Pause at Intervals**: The compass pauses briefly at 45-degree intervals for visual emphasis

## Requirements

- Java 8 or higher
- Swing library (included in standard Java distribution)

## How to Run

```bash
javac CompassDial.java
java CompassDial
```

## Project Structure

- **CompassDial.java**: Main application file containing all components
  - `CompassDial`: Main JFrame window
  - `CompassPanel`: Custom JPanel for rendering graphics
  - `MidpointCircle`: Implements the midpoint circle drawing algorithm
  - `DDALine`: Implements the DDA line drawing algorithm

## Technical Details

- Window Size: 800x800 pixels
- Center: (400, 400)
- Animation Speed: 2 degrees rotation per frame (30ms refresh rate)
- Features gradient background and anti-aliased rendering

## Author

CGIP Project - Computer Graphics and Image Processing Animation

