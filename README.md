# Machine Monospace Font

Machine is designed for good readability and legibility. It is ideal for code, terminal, and other monospace applications, including machine reading.

## Font Information

The font follows the [Google Fonts specification](https://github.com/googlefonts/gf-docs) and includes:

- `DESCRIPTION.en_us.html` - Font description and details
- `FONTLOG.txt` - Detailed font history and acknowledgments
- `machine.css` - CSS for web usage
- `Machine-Regular.glyphs` - Glyphs file
- `Machine-Regular.ttf` - TrueType font file
- `METADATA.pb` - Font metadata for Google Fonts
- `OFL.txt` - SIL Open Font License v1.1

## Development

The font source is in TTF format and can be opened and modified using:

- [Glyphs](https://glyphsapp.com)
- [FontForge](https://fontforge.org)
- [FontLab](https://fontlab.com)
- Any other font editor that supports TTF format

To modify the font:

1. Install a font editor
2. Open the `Machine-Regular.glyphs` file
3. Make your changes and export the font files

Please note that some glyphs are composed of multiple glyphs. However, in TTF format they are exported as decomposed glyphs. Avoid editing the TTF file to maintain consistency. TTF is only for exporting glyphs.

## Usage

### Importing the font

```css
@font-face {
  font-family: "machine";
  src: url(Machine-Regular.ttf) format("truetype");
  font-display: swap;
}
```

### CDN

CSS import of the latest version

```css
@font-face {
  font-family: "machine";
  src: url(https://cdn.jsdelivr.net/gh/rastislavcore/machine/Machine-Regular.ttf) format("truetype");
  font-display: swap;
}
```

CSS with Minor updates and patch fixes within a major version

```css
@font-face {
  font-family: "machine";
  src: url(https://cdn.jsdelivr.net/gh/rastislavcore/machine@1/Machine-Regular.ttf) format("truetype");
  font-display: swap;
}
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1. See the [OFL.txt](OFL.txt) file for full details.

## Funding

If you find this project useful, please consider supporting it:

- [GitHub Sponsors](https://github.com/sponsors/rastislavcore)

List of sponsors: [![GitHub Sponsors](https://img.shields.io/github/sponsors/rastislavcore?label=Sponsors&logo=githubsponsors&color=EA4AAA)](https://github.com/sponsors/rastislavcore)
