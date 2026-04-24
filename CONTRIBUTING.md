# 🤝 Contributing to Rick and Morty Theme

Thank you for your interest in contributing!

## 🌍 How to Contribute

### Reporting Bugs

1. Check if the issue already exists
2. Create a new issue with:
   - Clear title
   - Steps to reproduce
   - VS Code version
   - Theme version

### Proposing Features

1. Open a new issue with label `enhancement`
2. Describe the use case
3. Explain why it would be useful
4. Provide example workflow

### Submitting Pull Requests

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-awesome-feature`
3. Make your changes
4. Commit with clear messages: `git commit -m 'Add awesome feature'`
5. Push to your fork: `git push origin feature/my-awesome-feature`
6. Open a Pull Request

## 📋 Development Setup

```bash
# Clone the repo
git clone https://github.com/ivandf/rick-and-morty-theme.git
cd rick-and-morty-theme

# Install dependencies
npm install

# Package the extension
npm run package
```

## 🧪 Testing

Before submitting:
- Test your changes locally with VS Code
- Test both themes (Portal Gun Dark & Citadel Light)
- Test with different file types

## 📝 Code Style

- Use 2 spaces for indentation
- Keep theme JSON files consistent
- Add comments for new colors

## 🏷️ Labels to Use

- `bug` - Something isn't working
- `enhancement` - New feature request
- `documentation` - Improvements to docs
- `question` - Help needed

## 💬 Getting Help

- Open an issue for bugs/features
- Don't hesitate to ask questions!

---

**Quick Start**: 
```bash
npm install
code --install-extension rick-and-morty-theme.vsix
```