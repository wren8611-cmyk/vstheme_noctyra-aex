# Deep Navy Cyan

A dark Visual Studio Code theme featuring a deep navy background, icy cyan text, and soft pastel syntax highlighting.

Designed for a comfortable coding experience with a consistent color palette across the editor, terminal, and VS Code interface.

## Features

- Deep navy editor background with icy cyan foreground
- Soft pastel syntax highlighting
- Rainbow bracket pair colorization
- Customized sidebar, tabs, terminal, and command palette
- Semantic highlighting support
- Tested with C++ and Python

## Color Palette

| Element | Color | Hex |
|---|---|---|
| Background | Deep Navy | `#0D1E30` |
| Foreground | Icy Cyan | `#B8DEE8` |
| Keywords | Lavender | `#B69BD8` |
| Types | Turquoise | `#78D8D2` |
| Functions | Warm Yellow | `#E5DCA0` |
| Strings | Soft Salmon | `#D09B88` |
| Numbers | Mint Green | `#A8D4B8` |
| Comments | Muted Blue | `#607F96` |
| Operators | Pale Blue | `#A6C9DC` |
| Namespaces | Bright Turquoise | `#85E5DF` |

## Installation

### Manual Installation

Clone the repository into your VS Code extensions directory:

```bash
git clone https://github.com/wren8611-cmyk/vstheme_deep-navy-cyan.git \
    ~/.vscode/extensions/local.deep-navy-cyan-0.0.1
```

Restart VS Code.

Open the Command Palette (`Cmd+Shift+P` on macOS or `Ctrl+Shift+P` on Windows/Linux) and select:

**Preferences: Color Theme → Deep Navy Cyan**

### Updating

To update the theme:

```bash
cd ~/.vscode/extensions/local.deep-navy-cyan-0.0.1
git pull
```

Then run **Developer: Reload Window** in VS Code.

## Supported Languages

The theme uses standard TextMate scopes and semantic token colors, making it compatible with multiple programming languages.

Syntax highlighting has been tested with:

- C++ (Microsoft C/C++ extension)
- Python

## Customization

The theme configuration is located at:

```text
themes/deep-navy-cyan-color-theme.json
```

Modify the colors in this file and reload VS Code to apply changes.

## License

See the `LICENSE` file for licensing information, if provided.
