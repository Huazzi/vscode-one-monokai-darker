# 🎨 One Monokai Darker

A beautiful dark theme for Visual Studio Code inspired by the classic Monokai color scheme, enhanced with bold keywords and a refined color palette for superior code readability.

![Theme Preview](https://via.placeholder.com/800x400/1e2227/ffffff?text=One+Monokai+Darker+Theme+Preview)

## ✨ Features

- **🎯 Enhanced Bold Keywords**: Important keywords like `if`, `for`, `class`, `function` are bold for better code structure visibility
- **🌙 Dark & Comfortable**: Easy on the eyes during long coding sessions
- **🎨 Refined Color Palette**: Carefully selected colors that provide excellent contrast and readability
- **📝 Comprehensive Language Support**: Optimized for JavaScript, TypeScript, Python, HTML, CSS, and more
- **🔧 Consistent UI**: Harmonious interface colors that complement the syntax highlighting

## 🚀 Installation

### Via VS Code Marketplace
1. Open **Extensions** sidebar panel in VS Code (`Ctrl+Shift+X`)
2. Search for `One Monokai Darker`
3. Click **Install**
4. Click **Reload** to reload VS Code
5. Go to **File > Preferences > Color Theme** and select **One Monokai Darker**

### Via Command Line
```bash
code --install-extension your-publisher-name.one-monokai-darker
```

## 🎨 Color Palette

| Element | Color | Usage |
|---------|-------|-------|
| **Background** | `#1e2227` | Editor background |
| **Foreground** | `#abb2bf` | Default text |
| **Keywords** | `#e06c75` | Control flow, storage keywords (bold) |
| **Strings** | `#e5c07b` | String literals |
| **Functions** | `#98c379` | Function names (bold) |
| **Classes** | `#61afef` | Class names, types (bold) |
| **Constants** | `#56b6c2` | Built-in constants (bold) |
| **Numbers** | `#c678dd` | Numeric values |
| **Comments** | `#676f7d` | Code comments |

## 🔥 What's Special

### Bold Keywords for Better Structure
- **Control Flow**: `if`, `else`, `for`, `while`, `return`, `break`, `continue`
- **Declarations**: `var`, `let`, `const`, `function`, `class`
- **Built-in Constants**: `true`, `false`, `null`, `undefined`, `this`
- **Import/Export**: `import`, `export`, `from`
- **HTML Tags**: All HTML/XML tag names

### Optimized for Modern Development
- Perfect for React, Vue, Angular development
- Excellent TypeScript support
- Great for Python, Go, Rust, and other languages
- Markdown support with proper emphasis

## 📸 Screenshots

### JavaScript/TypeScript
```javascript
// Bold keywords make structure clear
class UserService {
  constructor(private apiUrl: string) {
    this.apiUrl = apiUrl;
  }

  async getUser(id: number): Promise<User> {
    if (!id) {
      throw new Error('User ID is required');
    }

    const response = await fetch(`${this.apiUrl}/users/${id}`);
    return response.json();
  }
}
```

### Python
```python
# Clean and readable Python code
class DataProcessor:
    def __init__(self, data_source: str):
        self.data_source = data_source

    def process_data(self, filters: dict) -> list:
        if not filters:
            return []

        for item in self.data:
            if self._matches_filter(item, filters):
                yield self._transform_item(item)
```

## 🛠️ Customization

You can customize this theme by adding the following to your `settings.json`:

```json
{
  "editor.tokenColorCustomizations": {
    "[One Monokai Darker]": {
      "comments": "#your-color-here"
    }
  }
}
```

## 🤝 Contributing

Found a bug or have a suggestion? Please open an issue on [GitHub](https://github.com/your-username/vscode-one-monokai-darker/issues).

## 📄 License

This theme is licensed under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Inspired by the original Monokai theme
- Color palette influenced by One Dark Pro and Atom One Dark
- Thanks to the VS Code community for feedback and suggestions

---

**Enjoy coding with One Monokai Darker!** 🚀

If you like this theme, please consider:
- ⭐ Starring the [GitHub repository](https://github.com/your-username/vscode-one-monokai-darker)
- 📝 Leaving a review on the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=your-publisher-name.one-monokai-darker)
- 🐦 Sharing it with your developer friends
