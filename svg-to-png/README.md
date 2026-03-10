# SVG to PNG Converter

[Explore the Live Tool »](https://s17labs.github.io/tools/svg-to-png)

A high-performance, browser-based utility for converting vector graphics (SVG) into transparent PNG images. This tool processes all files locally on your hardware, ensuring your designs never leave your device.

## Features

* **Batch Conversion**: Drop multiple SVG files to convert them all at once into a single ZIP archive.
* **Smart Scaling**: Define a custom output width, and the tool automatically calculates the height to preserve the original aspect ratio.
* **Transparency Support**: High-fidelity PNG output that respects the alpha channels and transparency of the original vector.
* **Privacy Focused**: No server uploads or tracking. All rendering is handled by the browser's Canvas API.
* **Midnight Theme**: Consistent UI design matching the s17 Labs ecosystem.

## Technical Details

Built using vanilla HTML5 and modern JavaScript APIs:
- **JSZip**: Handles the creation of batch archives for multiple files.
- **Blob & URL API**: Manages memory-efficient image rendering.
- **Canvas API**: Performs the rasterization of vector data into pixel-based images.
- **Aldrich Font**: Utilized for a cohesive tech-driven aesthetic.

## Usage
Simply open the index.html file in any modern browser or visit the [live page](https://s17labs.github.io/tools/svg-to-png).

## License
This project is released under the terms of the MIT License. See the [LICENSE](https://github.com/s17labs/tools/blob/main/LICENSE) for further information.

---
Part of the [s17 Labs Tools](https://github.com/s17labs/tools) collection.
