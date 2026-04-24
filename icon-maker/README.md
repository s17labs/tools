# Icon Maker

[Explore the Live Tool »](https://s17labs.github.io/tools/icon-maker)

Generate custom icons from Font Awesome, Noto Emoji, or Twemoji. Control colors, shape, and scale — export as SVG, PNG, or a full Android launcher package.

## Features

* **Font Awesome**: Type any Font Awesome icon name (e.g. circle-check, star, bolt, github) — it auto-tries fas, far, and fab prefixes.
* **Noto Emoji**: Paste or type any emoji (😀 🎉 🔥 🇺🇸 👨‍💻), fetches from cdn.jsdelivr.net/gh/googlefonts/noto-emoji. Codepoint conversion strips ZWJ and VS16 to match Noto's file naming.
* **Twemoji**: same input, fetches from cdn.jsdelivr.net/gh/jdecked/twemoji@15.1.0. Keeps ZWJ sequences intact (needed for things like 👨‍💻 family emoji) and only strips VS16 on non-ZWJ emoji.
* **Preview**: Live icon maker preview with colors, shapes, etc.
* **Colors**: Independent color pickers for icon color and background color, with live hex display.
* **Background Shapes**: 4 background shapes: None (transparent), Circle, Rounded Square, Square.
  * Icon scale slider (30–90%) to control padding.
* **Export**: 8 resolution presets: 16, 32, 64, 128, 256, 512, 1024, 2048px.
  * Custom W×H inputs for any size.
  * **SVG**: pure vector, resolution-independent.
  * **PNG**: rasterized at exact pixel dimensions; transparent when background shape is set to "None".

## Technical Details

Built using vanilla HTML5, CSS3, and JavaScript, utilizing:
- **JSZip**: For client-side archiving.
- **FA SVG+JS**: For the icon → SVG path conversion, so exports are clean vectors rather than font renders.
- **Aldrich Font**: For that signature s17 Labs tech aesthetic.

## Usage
Simply open the index.html file in any modern browser or visit the [live page](https://s17labs.github.io/tools/icon-maker).

## License
This project is released under the terms of the MIT License. See the [LICENSE](https://github.com/s17labs/tools/blob/main/LICENSE) for further information.

---
Part of the [s17 Labs Tools](https://github.com/s17labs/tools) collection.

