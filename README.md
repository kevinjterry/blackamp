<div align="center">

<img src="https://raw.githubusercontent.com/kevinjterry/blackamp-theme/main/assets/blackamp-icon.png" width="40%" alt="Blackamp Theme Logo"/>

_Blackamp is a dark VSCode theme inspired by loud vintage amplifiers_

[![Version](https://img.shields.io/badge/version-0.1.0-c8a368?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=kevinterry.blackamp)
[![License](https://img.shields.io/badge/license-MIT-c8a368?style=for-the-badge)](./LICENSE)
[![VS Code](https://img.shields.io/badge/VS%20Code-1.67+-1b1b1c?style=for-the-badge&logo=visual-studio-code)](https://code.visualstudio.com/)

</div>

---

## Screenshots


<img src="https://raw.githubusercontent.com/kevinjterry/blackamp-theme/main/assets/screenshot.png" width="80%" alt="Blackamp Dark theme screenshot"/>


---

## Installation

### VS Code Marketplace

1. Open **Extensions** (`Ctrl+Shift+X` / `Cmd+Shift+X`)
2. Search for **"Blackamp"**
3. Click **Install**
4. Select **"Blackamp Dark"** from the theme dropdown

### Manual Installation

```bash
# Clone the repository
git clone https://github.com/kevinjterry/blackamp-theme.git

# Copy to VS Code extensions folder
# Windows: %USERPROFILE%\.vscode\extensions
# macOS: ~/.vscode/extensions
# Linux: ~/.vscode/extensions
```

### Quick Setup

```json
// settings.json
{
  "workbench.colorTheme": "Blackamp Dark",
  "editor.semanticHighlighting.enabled": true,
  "editor.fontFamily": "Fira Code, Monaco, 'Courier New', monospace",
  "editor.fontSize": 14,
  "editor.lineHeight": 1.5
}
```

---

## Configuration

### Recommended Settings

```json
{
  "editor.semanticHighlighting.enabled": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "editor.fontLigatures": true,
  "workbench.tree.indent": 16,
  "terminal.integrated.fontFamily": "Fira Code"
}
```

## Recommended Font

**Primary**: [Fira Code](https://github.com/tonsky/FiraCode) with ligatures

## Contributing

We welcome contributions!

## License

MIT License - see [LICENSE](./LICENSE) for details.

## Inspiration

Built from the base of Safira, a long-running favorite theme of mine.
