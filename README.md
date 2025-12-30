# Standard Notes - Ivory Theme

A warm, high-contrast ivory theme for Standard Notes, inspired by Proton Mail's Ivory theme and featuring SF Pro Text font.

![Theme Preview](thumbnail.png)

## Features

- 🎨 Warm ivory/cream color palette for reduced eye strain
- 🔤 SF Pro Text Regular font (loaded from GitHub)
- ♿ High contrast for better accessibility
- 📖 Optimized for long reading and writing sessions
- 🎯 Clear visual hierarchy with distinct UI elements

## Color Palette

The theme uses a carefully selected warm color scheme:

- **Background**: `#fffef8` - Soft ivory white
- **Foreground**: `#1a1a1a` - Deep charcoal
- **Secondary**: `#f5f3ed` - Light cream
- **Tertiary**: `#eae6dc` - Warm beige
- **Accent**: `#6b5d4f` - Muted brown
- **Border**: `#d4d0c8` - Subtle tan

## Installation

### Method 1: Direct Import (Recommended)

1. Open Standard Notes
2. Go to **Preferences** > **General** > **Advanced Settings**
3. Click on **Install Custom Extension**
4. Enter the following URL:
   ```
   https://morningjon.github.io/hshtg-sn-ivory/ext.json
   ```
5. Click **Install**

### Method 2: Manual Installation

1. Download the theme files:
   - `ivory-theme.css`
   - `ext.json`

2. Open Standard Notes
3. Go to **Preferences** > **General** > **Advanced Settings**
4. Click on **Import Extension**
5. Select the `ext.json` file

### Method 3: Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/morningjon/hshtg-sn-ivory.git
   cd hshtg-sn-ivory
   ```

2. Host the files locally or on your preferred server

3. In Standard Notes, install using your hosted URL

## Files Included

- **ivory-theme.css** - Main theme stylesheet with all color definitions and SF Pro Text font import
- **ext.json** - Extension metadata for Standard Notes (use this URL to install)
- **theme.json** - Additional theme metadata
- **package.json** - Package information for distribution
- **README.md** - This documentation

## Font

The theme uses **SF Pro Text Regular** from Apple, loaded directly from:
```
https://morningjon.github.io/hshtg-fonts/SF-Pro-Text-Regular.otf
```

If the font fails to load, the theme will gracefully fall back to system fonts.

## Customization

You can customize the theme by editing the CSS variables in `ivory-theme.css`:

```css
:root {
  --sn-stylekit-background-color: #fffef8;  /* Main background */
  --sn-stylekit-foreground-color: #1a1a1a;  /* Main text */
  --sn-stylekit-info-color: #6b5d4f;        /* Links and accents */
  /* ... more variables ... */
}
```

## Compatibility

- **Standard Notes**: 3.x and higher
- **Platform**: Web, Desktop (Windows, macOS, Linux), Mobile (iOS, Android)
- **Layer Version**: 1

## Support

If you encounter any issues:

1. Check that the font URL is accessible
2. Verify Standard Notes is up to date
3. Try reinstalling the theme
4. Open an issue on GitHub

## License

MIT License - Feel free to modify and share!

## Credits

- Theme inspired by **Proton Mail's Ivory theme**
- Font: **SF Pro Text** by Apple Inc.
- Created by **morningjon**

## Changelog

### Version 1.0.0 (Initial Release)
- High-contrast ivory color scheme
- SF Pro Text font integration
- Complete Standard Notes theme support
- Optimized scrollbars and UI elements
- Syntax highlighting for code blocks
- Accessibility improvements

## Screenshots

### Note Editor
Clean, distraction-free writing experience with warm ivory tones.

### Note List
Easy-to-scan note list with clear hover and selection states.

### Tags
Subtle tag styling that doesn't overpower your content.

---

**Enjoy your new theme! If you like it, consider starring the repo ⭐**
