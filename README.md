# QR Studio

A lightweight, browser-based QR code maker. Enter a link or text, choose a style, and download a square PNG ready for print or sharing.

## Features

- Live QR code generation as you type
- Custom foreground and background colours
- Three QR sizes: small, medium, and large
- Adjustable error-correction level
- Four presentation styles:
  - Classic
  - SCAN ME
  - Sticker
  - Dark card
- Square 720 × 720 PNG downloads that include the selected style

## Run locally

No installation or build step is needed.

1. Open [index.html](./index.html) in a modern web browser.
2. Enter a URL or any text in the input box.
3. Adjust the colours, size, correction level, and design style.
4. Select **Download PNG** to save the QR design.

## Notes

- The app loads the QR generation library and fonts from public CDNs, so an internet connection is needed when opening the page.
- Use a strong contrast between the foreground and background colours for the most reliable scanning.
- Higher error correction makes QR codes more resilient but can make them denser.

## Project structure

```text
qr code maker/
├── index.html   # Application UI, styles, and QR generation logic
└── README.md    # Project documentation
```
