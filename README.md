<div align="center">

<img src="./assets/blackamp-icon.png" width="40%" alt="Blackamp Theme Logo"/>

_Blackamp is a dark VSCode theme inspired by loud vintage amplifiers_

[![Version](https://img.shields.io/badge/version-1.0.0-c8a368?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=kt.blackamp)
[![License](https://img.shields.io/badge/license-MIT-c8a368?style=for-the-badge)](./LICENSE)
[![VS Code](https://img.shields.io/badge/VS%20Code-1.60+-1b1b1c?style=for-the-badge&logo=visual-studio-code)](https://code.visualstudio.com/)

</div>

---

## Screenshots

### C

<img src="./assets/c-example.png" width="80%" alt="C/C++ Example showing tube amplifier design calculator"/>

_C syntax_

### Python

<img src="./assets/python-example.png" width="80%" alt="Python Example showing advanced language features"/>

_Python syntax_

---

## Installation

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
  "editor.fontFamily": "Fira Code, Monaco, 'Courier New', monospace",
  "editor.fontSize": 14,
  "editor.lineHeight": 1.5
}
```

---

## Special Features

### **Constructor Highlighting**

```typescript
// Constructor calls are highlighted in signature orange
const color = new Color(255, 0, 0); // 🟠 Orange
const client = ApiClient.getInstance(); // 🟠 Orange
const vector = Vector3(1.0, 2.0, 3.0); // 🟠 Orange
```

### **Template String Magic**

```typescript
// Gold interpolation markers with proper nesting
const message = `Hello ${user.name}!`; // 🟡 Gold markers
const query = `SELECT * FROM ${table}`; // 🟡 Gold markers
```

### **Semantic Intelligence**

```python
# Smart highlighting based on context
def calculate_gain(self, voltage: float) -> float:
#   ^^^^^^^^^^^^^  ^^^^  ^^^^^^^  ^^^^^    ^^^^
#   Function       Self   Param    Type     Type
#   (blue-gray)   (teal) (gray)   (teal)   (teal)
```

---

## ⚙️ Configuration

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
We welcome contributions! Please see our [Contributing Guide](./CONTRIBUTING.md) for details.

## License
MIT License - see [LICENSE](./LICENSE) for details.

## Inspiration
Built from the base of Safira which is a long running favorite theme of mine.
