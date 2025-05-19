# QR Code Generator

This Node.js application prompts the user to enter a URL, generates a QR code for that URL, saves the QR code as a PNG file, and writes the original URL to a text file.

## Functionality

- Accepts a URL input from the user via command-line prompt
- Generates a QR code in PNG format using the `qr-image` package
- Saves the generated QR code as `qr_img.png`
- Saves the input URL in a text file named `url.txt`
