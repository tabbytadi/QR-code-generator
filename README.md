# QR Code Generator

This project is a simple Node.js application that generates a QR code from a user-entered URL and saves both the QR code image into an image file and the URL into a text file.

## Features
- Uses the [`inquirer`](https://www.npmjs.com/package/inquirer) npm package to prompt the user for a URL.
- Uses the [`qr-image`](https://www.npmjs.com/package/qr-image) npm package to generate a QR code from the given URL.
- Saves the generated QR code as an image file.
- Stores the user-entered URL in a text file.
