# Fun with HTML5 Canvas

This project demonstrates the power and versatility of the HTML5 Canvas element by creating a fun, interactive drawing application. Users can draw colorful lines on the canvas, where the color and line width dynamically change as they draw. Additionally, the canvas can be easily reset using the provided reset button or by pressing the `Esc` key.

## Features

- **Dynamic Drawing**: Draw on the canvas with your mouse, and watch as the line's color (hue) changes dynamically.
- **Adaptive Line Width**: The line width adjusts as you draw, cycling between thin and thick strokes.
- **Full-Screen Canvas**: The canvas dynamically resizes to fill the entire browser window.
- **Reset Options**: Clear the canvas by clicking the "Reset" button or pressing the `Esc` key.
- **Custom Styling**: The reset button is styled with a modern, sleek design.

## How to Use

1. Open the project in any modern browser.
2. Draw on the canvas by clicking and dragging the mouse.
3. To reset the canvas:
   - Click the **Reset** button in the top-right corner, or
   - Press the `Esc` key on your keyboard.

## Key Files

- **`index.html`**: Contains the structure and basic layout of the page, including the canvas and reset button.
- **`style`**: Inline CSS styles that provide the visual design for the reset button and canvas.
- **`script`**: JavaScript code that handles:
  - Drawing on the canvas.
  - Dynamically changing line color and width.
  - Canvas reset functionality.

## How It Works

1. **Drawing on the Canvas**:
   - The mouse movements are tracked using event listeners (`mousemove`, `mousedown`, `mouseup`, `mouseout`).
   - A dynamic `hsl` color value is applied to each stroke.
   - Line width increases or decreases cyclically between 1 and 100 pixels.

2. **Reset Functionality**:
   - Clicking the "Reset" button clears the canvas using `clearRect()`.
   - Pressing the `Esc` key triggers the same function to reset the canvas.

## Screenshot

![Drawing App Preview](<HTML5 Canvas.png>)

## Browser Compatibility

This project is compatible with all modern browsers that support the HTML5 Canvas API and ES6 JavaScript.

## Future Enhancements

- Add touch support for mobile devices.
- Allow users to change colors and line width manually.
- Implement an undo/redo feature for drawings.
- Save the drawing as an image (e.g., PNG or JPG).

## License

This project is open-source and free to use under the [MIT License](LICENSE).