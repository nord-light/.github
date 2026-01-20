# Nord Light

A light theme based on the [Nord](https://www.nordtheme.com/) color palette, adapted for light backgrounds.

## About

Nord is a popular color palette known for its elegant arctic-inspired colors, originally designed for dark themes. Nord Light brings the same aesthetic to light theme lovers, with carefully adjusted colors to ensure proper contrast and readability on light backgrounds.

## Color Palette

### Base Colors (Nord Snow Storm)

These colors are used for backgrounds and UI elements:

| Name | Hex | Usage |
|------|-----|-------|
| Nord 4 | `#D8DEE9` | Selection, borders, secondary backgrounds |
| Nord 5 | `#E5E9F0` | Sidebar, toolbar, inactive backgrounds |
| Nord 6 | `#ECEFF4` | Main editor background |

### Text Colors (Nord Polar Night)

| Name | Hex | Usage |
|------|-----|-------|
| Nord 0 | `#2E3440` | Main text, identifiers |
| Nord 1 | `#3B4252` | Secondary text |
| Nord 2 | `#434C5E` | Tertiary text |
| Nord 3 | `#4C566A` | Comments base, punctuation |

### Accent Colors

The original Nord accent colors are designed for dark backgrounds. For the light theme, we darkened them significantly to ensure proper contrast and readability.

| Element | Original Nord | Nord Light | Description |
|---------|---------------|------------|-------------|
| Classes/Types | `#8FBCBB` (nord7) | `#1D7A79` | Teal - class names, type references |
| Functions | `#88C0D0` (nord8) | `#0D7D8C` | Cyan - function declarations and calls |
| Tags | `#81A1C1` (nord9) | `#4B6C8C` | Light blue - HTML/XML tags, operators |
| Keywords | `#5E81AC` (nord10) | `#3B5E85` | Blue - language keywords |
| Strings | `#A3BE8C` (nord14) | `#6B8B4F` | Green - string literals |
| Numbers | `#B48EAD` (nord15) | `#8B5E84` | Purple - numeric literals |
| Constants | `#EBCB8B` (nord13) | `#B8941E` | Yellow - constants, enums |
| Fields | `#D08770` (nord12) | `#A5614A` | Orange - instance/static fields |
| Errors | `#BF616A` (nord11) | `#BF616A` | Red - errors (unchanged) |

### Color Rationale

- **Darkening factor:** ~25-40% darker than original Nord colors
- **Saturation:** Maintained or slightly increased for vibrancy
- **Contrast ratio:** All colors meet WCAG AA standards against `#ECEFF4` background

## Credits

- Based on [Nord Theme](https://www.nordtheme.com/) by [Sven Greb](https://github.com/svengreb)

## License

MIT License

## Available Ports

- [JetBrains IDEs](https://github.com/nord-light/jetbrains) (PhpStorm, IntelliJ IDEA, WebStorm, etc.)

## Author

Created by [Vincenzo Petrucci](https://nahi.me/) ([@nahime0](https://github.com/nahime0)) as part of [Illegal Studio](https://illegal.studio/).
