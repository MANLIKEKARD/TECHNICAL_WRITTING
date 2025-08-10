# Markdown Generator - Example README

```markdown
# 🚀 Markdown Generator [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A CLI tool for generating beautiful markdown documentation

## 🌟 Features
- **Easy syntax conversion** - Transform plain text to markdown
- **Live preview** - See changes in real-time
- **Export options** - Save as PDF/HTML/Markdown
- **Custom templates** - Create reusable document structures

## 📦 Installation
```bash
# Using npm
npm install -g markdown-generator

# Using yarn
yarn global add markdown-generator
```

## 🛠️ Usage
```javascript
const mdGen = require('markdown-generator');

// Create a new document
const doc = mdGen.createDocument();

// Add elements
doc.addHeader('Introduction', 2)
   .addParagraph('Welcome to Markdown Generator!')
   .addCodeBlock('console.log("Hello Markdown!");', 'javascript')
   .addList(['Feature 1', 'Feature 2', 'Feature 3'])
   .addTable([
     ['Option', 'Default', 'Description'],
     ['--theme', 'light', 'Color scheme'],
     ['--format', 'gfm', 'Markdown flavor']
   ]);

// Export to file
doc.export('README.md');
```

## ⚙️ Configuration
| Environment Variable | Description          | Default     |
|----------------------|----------------------|-------------|
| `MD_THEME`           | Editor color theme   | `light`     |
| `MD_AUTOSAVE`        | Auto-save interval   | `30` (sec)  |
| `MD_FORMAT`          | Markdown flavor     | `gfm`       |

## 📋 Keyboard Shortcuts
| Shortcut             | Action               |
|----------------------|----------------------|
| `Ctrl + S`           | Save document        |
| `Ctrl + P`           | Toggle preview       |
| `Ctrl + B`           | Toggle bold          |
| `Ctrl + L`           | Insert link          |

## 🧪 Running Tests
```bash
npm test
```

## 🤝 Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add awesome feature'`)
4. Push to branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

---
> Made with ❤️ by Dev Team • [Documentation](https://docs.mdgen.com) • [Report Issue](https://github.com/your/repo/issues)
```

## Rendered Output Preview

# 🚀 Markdown Generator [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A CLI tool for generating beautiful markdown documentation

## 🌟 Features
- **Easy syntax conversion** - Transform plain text to markdown
- **Live preview** - See changes in real-time
- **Export options** - Save as PDF/HTML/Markdown
- **Custom templates** - Create reusable document structures

## 📦 Installation
```bash
# Using npm
npm install -g markdown-generator

# Using yarn
yarn global add markdown-generator
```

## 🛠️ Usage
```javascript
const mdGen = require('markdown-generator');

// Create a new document
const doc = mdGen.createDocument();

// Add elements
doc.addHeader('Introduction', 2)
   .addParagraph('Welcome to Markdown Generator!')
   .addCodeBlock('console.log("Hello Markdown!");', 'javascript')
   .addList(['Feature 1', 'Feature 2', 'Feature 3'])
   .addTable([
     ['Option', 'Default', 'Description'],
     ['--theme', 'light', 'Color scheme'],
     ['--format', 'gfm', 'Markdown flavor']
   ]);

// Export to file
doc.export('README.md');
```

## ⚙️ Configuration
| Environment Variable | Description          | Default     |
|----------------------|----------------------|-------------|
| `MD_THEME`           | Editor color theme   | `light`     |
| `MD_AUTOSAVE`        | Auto-save interval   | `30` (sec)  |
| `MD_FORMAT`          | Markdown flavor     | `gfm`       |

## 📋 Keyboard Shortcuts
| Shortcut             | Action               |
|----------------------|----------------------|
| `Ctrl + S`           | Save document        |
| `Ctrl + P`           | Toggle preview       |
| `Ctrl + B`           | Toggle bold          |
| `Ctrl + L`           | Insert link          |

## 🧪 Running Tests
```bash
npm test
```

## 🤝 Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add awesome feature'`)
4. Push to branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

---
> Made with ❤️ by Dev Team • [Documentation](https://docs.mdgen.com) • [Report Issue](https://github.com/your/repo/issues)

## Key Markdown Elements Used
1. **Headers**: `# H1`, `## H2`
2. **Badges**: `![License: MIT](...)`
3. **Lists**: `- Item` for bullet points
4. **Code Blocks**: Triple backticks with language specification
5. **Tables**: Pipe syntax with alignment
6. **Links**: `[Text](URL)`
7. **Emphasis**: `**Bold**`, `*Italic*`
8. **Blockquotes**: `> Text`
9. **Horizontal Rules**: `---`
10. **Emojis**: `:rocket:`, `:memo:`, `:gear:`

This example demonstrates practical usage of essential Markdown syntax in a real-world README scenario.
