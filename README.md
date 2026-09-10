# ASCII Art Studio

A browser-based tool that converts images into ASCII art. Upload an image, pick a style, and get text art you can copy or download — all client-side, no backend or dependencies required.

## Features

- **Multiple render styles** — Classic ASCII, Matrix (katakana rain effect), Braille (dot-matrix), and Emoji
- **Color mode** — render output as colored HTML spans matching the source image's pixel colors
- **Adjustable output** — control output width, contrast, and inversion in real time
- **Drag & drop / paste support** — drop an image file or paste one from the clipboard
- **Adjustable font size** — zoom the rendered output in or out
- **Copy & download** — copy ASCII text to clipboard or download it as a `.txt` file

## Usage

1. Open `index.html` in any modern browser (no build step, no server needed).
2. Upload an image by clicking the upload zone, dragging a file in, or pasting from clipboard.
3. Choose a style (Classic / Matrix / Braille / Emoji) from the style selector.
4. Adjust width, contrast, invert, and color toggles to fine-tune the result.
5. Use **Copy** to copy the ASCII text, or **Download** to save it as a `.txt` file.

## Tech stack

Plain HTML, CSS, and vanilla JavaScript — no frameworks, no build tools, no external JS dependencies. Fonts (Inter, JetBrains Mono) are loaded from Google Fonts via CDN.

## Project structure

```
.
└── index.html   # Entire app: markup, styles, and logic in one file
```

## License

Not yet specified.
