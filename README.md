# QR Code Generator

This is a simple **QR Code Generator** web application built using HTML, CSS, and JavaScript. It allows users to generate a QR code for any given text or URL input. The QR code is generated using a public API and is displayed dynamically on the page.

## Features
- Enter any text or URL to generate a QR code.
- QR code will be displayed instantly upon clicking the "Generate QR Code" button.
- Responsive and modern design with animation effects.
- Error feedback for empty input.
- Styled using **Google Sans** font and a clean interface.

## Demo

You can view the working demo of the project here: [Demo Link](#)

## Preview
![QR Code Generator Screenshot](#) <!-- Add image link -->

## Technologies Used
- **HTML5** for structure.
- **CSS3** for styling and layout.
- **JavaScript** for dynamic QR code generation.
- **QR Code API** from [QRServer](https://goqr.me/api/) to generate QR codes.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/SoumyaEXE/QRCode.git
   ```
2. Navigate to the project directory:
   ```bash
   cd QRCode
   ```
3. Open the `index.html` file in your browser to use the QR Code Generator.

## Code Explanation

### HTML
The basic structure of the webpage includes:
- A text input field to accept the text or URL.
- A button that triggers the QR code generation.
- An image box that displays the generated QR code.

### CSS
- The page is styled using custom fonts, colors, and a modern layout.
- Animations are used for error handling when no text is entered.
- The layout is responsive to different screen sizes.

### JavaScript
- A function `generateQR()` is used to handle the QR code generation.
- The input value is sent to the **QR Code API** to fetch the generated QR code.
- Basic error handling is implemented when the input field is empty.

## File Structure

```
QRCode/
├── index.html        # Main HTML file
├── style.css         # Stylesheet for the app
└── README.md         # Project documentation
```

## Screenshots
Add some screenshots to show how the app looks!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author
**Soumya**  
GitHub: [SoumyaEXE](https://github.com/SoumyaEXE)
