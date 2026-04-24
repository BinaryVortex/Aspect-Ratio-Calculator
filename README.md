# Aspect Ratio Calculator

A simple, lightweight Aspect Ratio Calculator built using HTML, CSS and JavaScript.

This small tool helps you calculate the matching width or height for a given aspect ratio. Enter a ratio (e.g. 16:9) and change either the width or height — the other value is calculated automatically.

## Preview

![App Screenshot](./Screenshot 2024-04-26 092237.png)

## Features

- Live calculation: enter width or height and the other value updates automatically.
- Supports custom aspect ratios (change the ratio width/height inputs).
- Small, dependency-free single-page app (HTML/CSS/JavaScript).

## How it works

The calculator keeps track of three values:
- Ratio width (e.g. 16)
- Ratio height (e.g. 9)
- One of the actual dimensions (width or height)

When you change the width or height input, the script uses the ratio (ratioWidth / ratioHeight) to calculate the corresponding value with two decimal precision.

## Usage

1. Clone or download the repository.
2. Open `index.html` in your browser.
3. Change the aspect ratio using the top inputs (defaults to 16:9).
4. Type a value into either the "Width" or "Height" field — the other field will update automatically.

## Files

- `index.html` — markup and structure
- `style.css` — styling
- `script.js` — calculation logic
- `Screenshot 2024-04-26 092237.png` — app preview used in this README

## Contributing

Contributions, suggestions and fixes are welcome. If you find an issue or want to add a feature (e.g., presets for common ratios, copy-to-clipboard, or responsive layout improvements), please open an issue or submit a pull request.

## License

No license specified. Add a `LICENSE` file to define the project's license.
