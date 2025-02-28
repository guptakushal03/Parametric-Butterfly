# Parametric Butterfly Visualization

This project showcases an animated visualization of the **Parametric Butterfly Curve**. The curve is plotted using a polar equation, creating intricate patterns as it evolves over time. The animation runs on an HTML5 canvas and allows users to interact with it by pausing, resuming, and resetting the animation.

## Features

- **Interactive Animation**: Click to pause or resume the animation, and double-click to clear the canvas and start fresh.
- **Formula Display**: The butterfly curve's parametric equations are displayed, allowing users to understand the underlying math.
- **Dynamic Colors**: The curve's color changes dynamically, based on the progress of the animation, creating a visually appealing effect.

## Instructions

1. **Pause/Resume Animation**: Click anywhere on the canvas to pause or resume the animation.
2. **Reset Animation**: Double-click on the canvas to clear it and start fresh.
3. **Formula Info**: A button on the page shows the formula used to generate the butterfly curve.

## Parametric Butterfly Formula

The butterfly curve is generated using the following parametric equations:

- **Polar Equation**:
  \[
  r = e^{\sin(\theta)} - 2 \cos(4\theta) + \sin^5\left(\frac{2\theta - \pi}{24}\right)
  \]

- **Cartesian Coordinates**:
  \[
  x = r \cdot \cos(\theta)
  \]
  \[
  y = -r \cdot \sin(\theta)
  \]

Where:
- `r` is the radial distance from the center.
- `θ` is the angle in radians (θ = time variable for animation).
- `x` and `y` are the Cartesian coordinates calculated from the polar equation.

## How It Works

1. The canvas is initialized, and the animation starts on load.
2. The parametric equations are computed at each frame, generating the next point on the curve.
3. The animation uses **canvas 2D** drawing methods to render the points and connect them with lines.
4. The color of the curve changes dynamically to add a beautiful visual effect.

## Installation

To run the project, simply open the `index.html` file in a web browser. The visualization will run on full screen and adapt to your browser's size.

## License

This project is open-source and available under the MIT License.
