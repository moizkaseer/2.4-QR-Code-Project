# QR Code Generator

A simple Node.js application that generates QR codes from URLs.

## Features

- Takes user input for any URL
- Generates a QR code image in SVG format
- Saves the original URL in a text file

## Installation

1. Clone this repository
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project directory
   ```bash
   cd your-repo-name
   ```
3. Install dependencies
   ```bash
   npm install
   ```

## Usage

1. Run the application
   ```bash
   node index.js
   ```
2. Enter the URL you want to convert to a QR code
3. The application will generate:
   - `i_love_qr.svg` - The QR code image
   - `url.txt` - The original URL text file

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer) - For user input
- [qr-image](https://www.npmjs.com/package/qr-image) - For QR code generation

## License

This project is open source and available under the [MIT License](LICENSE).
