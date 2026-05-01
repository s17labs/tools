# QR Code Generator

[Explore the Live Tool »](https://s17labs.github.io/tools/qr-generator)

A privacy-focused, browser-based QR code generation tool. This utility allows you to generate QR codes from any text or URL with customizable colors and sizes—all processing happens locally on your device.

## Features

* **Text & URL Support**: Generate QR codes from any input, up to 2,953 characters.
* **Custom Colors**: Set a foreground and background color via a native color picker or hex input, both kept in sync.
* **Adjustable Size**: Scale the output from 128px to 512px using a simple slider.
* **Error Correction Control**: Choose from four correction levels (L / M / Q / H) to balance density and resilience.
* **Dual Export**: Download your QR code as a high-resolution PNG (2× for crispness) or a clean, scalable SVG.
* **Midnight Theme**: A sleek, high-contrast UI designed for the modern workspace.

## Technical Details

Built using vanilla HTML5, CSS3, and JavaScript, utilizing:
- **QRCodeJS**: For client-side QR code generation via canvas.
- **Canvas API**: For high-resolution PNG rendering and SVG module sampling.
- **Aldrich Font**: For that signature s17 Labs tech aesthetic.

## Usage
Simply open the index.html file in any modern browser or visit the [live page](https://s17labs.github.io/tools/qr-generator).

## License
This project is released under the terms of the MIT License. See the [LICENSE](https://github.com/s17labs/tools/blob/main/LICENSE) for further information.

---
Part of the [s17 Labs Tools](https://github.com/s17labs/tools) collection.
