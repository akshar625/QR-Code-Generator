# QR Code Generator

This is a simple command-line application that takes a user-entered URL and generates a QR code image from it using the `qr-image` npm package. Additionally, it utilizes the `inquirer` npm package for user input and the native `fs` module to save the user input to a text file.

## Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install the dependencies.

## Usage

1. Open your terminal or command prompt.
2. Navigate to the project directory.
3. Run `npm start` to start the application.
4. Follow the prompts to enter the URL.
5. Once you've entered the URL, a QR code image will be generated and saved as `qr-img.png` in the project directory.
6. Additionally, the user input will be saved to a text file named `user_input.txt`.

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer): A collection of common interactive command-line user interfaces.
- [qr-image](https://www.npmjs.com/package/qr-image): A QR code generator.

## File Structure

- `index.js`: Main JavaScript file containing the application logic.
- `qr-img.png`: Generated QR code image.
- `user_input.txt`: Text file containing the user-entered URL.


