# Webcam to ASCII

> Live webcam ASCII art generator - transforms your video feed into text-based visuals in real-time.

Turn your webcam into a live ASCII art generator. Point the camera at anything and watch it render in text characters. Classic hacker movie effect, right in your browser.

## Features

- **Side-by-Side View** - Compare webcam feed and ASCII output simultaneously
- **Character Palettes** - Binary (01), ASCII (@#$%&), Blocks (█▓▒░), or Custom
- **Color Themes** - Matrix Green, White, Amber, Blue, Red
- **Density Control** - Adjust how many characters from the palette are used
- **Brightness Inversion** - Flip the light/dark mapping
- **Fullscreen Mode** - Full viewport ASCII experience
- **Screenshot** - Save current frame as `.txt` file

## Quick Start

1. Open `index.html` in your browser
2. Allow camera access when prompted
3. Enjoy the ASCII art!

No dependencies, no installation needed.

## Usage

| Control | Description |
|---------|-------------|
| Palette | Choose character set: Binary, ASCII, Blocks, or Custom |
| Density | Adjust character range (0-100%) |
| Color | Switch themes: Green, White, Amber, Blue, Red |
| Invert | Flip brightness mapping |
| Fullscreen | Toggle full viewport display |
| Side by Side | View webcam and ASCII output together |
| Screenshot | Download current frame as text file |

## How It Works

1. Captures video from your webcam
2. Converts each frame to grayscale (brightness values 0-255)
3. Maps brightness to characters - dark areas get dense characters, bright areas get light ones
4. Renders in real-time (~60fps)

## Tech

Pure HTML, CSS, and JavaScript. Runs entirely client-side. Zero dependencies.

## License

Free to use.
