<div align="center">

<img src="./assets/blackamp-icon.png" width="40%" alt="Blackamp Theme Logo"/>

_BLACKAMP is a dark VS Code theme inspired by loud vintage amplifiers._

[![Version](https://img.shields.io/badge/version-0.0.1-c8a368?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=kt.blackamp)
[![License](https://img.shields.io/badge/license-MIT-c8a368?style=for-the-badge)](./LICENSE)
[![VS Code](https://img.shields.io/badge/VS%20Code-1.60+-1b1b1c?style=for-the-badge)](https://code.visualstudio.com/)

</div>

## SCREENSHOTS

<div align="center">
<img src="./assets/c-example.png" width="80%" alt="C/C++ Example showing tube amplifier design calculator"/>
<br></br>
<br></br>
<img src="./assets/python-example.png" width="80%" alt="Python Example showing advanced language features"/>
</div>

## INSTALLATION

### VS Code Marketplace

1. Open **Extensions** (`Ctrl+Shift+X` / `Cmd+Shift+X`)
2. Search for **"Blackamp"**
3. Click **Install**
4. Select **"Blackamp"** from the theme dropdown

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
  "workbench.colorTheme": "blackamp",
  "editor.semanticHighlighting.enabled": true,
  "editor.fontFamily": "Fira Code",
  "editor.lineHeight": 1.5
}
```

## CONFIGURATION

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

## RECOMMENDED FONT

**Primary**: [Fira Code](https://github.com/tonsky/FiraCode) with ligatures

## CONTRIBUTING

Absolutely welcome contributions!

## LICENSE

MIT License - see [LICENSE](./LICENSE) for details.

## INSPIRATION

I built this originally off the base of [Safira](https://github.com/yinzdev/safira-vscode) which is a long running favorite theme of mine.
