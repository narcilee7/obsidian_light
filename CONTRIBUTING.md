# Contributing to Obsidian Light Theme

Thank you for your interest in contributing to the Obsidian Light theme! This document provides guidelines and information for contributors.

## Ways to Contribute

### 🐛 Reporting Issues
- Use the [GitHub Issues](https://github.com/narcilee7/obsidian-light-theme/issues) to report bugs
- Provide detailed steps to reproduce the issue
- Include screenshots if applicable
- Mention your VS Code version and operating system

### 💡 Feature Requests
- Open a [GitHub Issue](https://github.com/narcilee7/obsidian-light-theme/issues) with the "enhancement" label
- Describe the proposed feature clearly
- Explain why this feature would be useful

### 🎨 Color Improvements
- Submit color suggestions through GitHub Issues
- Provide color hex codes and rationale for changes
- Consider accessibility (contrast ratios, color blindness)

### 🔧 Code Contributions
- Fork the repository
- Create a feature branch
- Make your changes
- Test thoroughly
- Submit a pull request

## Development Setup

### Prerequisites
- VS Code 1.74.0 or later
- Git

### Getting Started
1. Fork and clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/obsidian-light-theme.git
   cd obsidian-light-theme
   ```

2. Open in VS Code:
   ```bash
   code .
   ```

3. Install recommended extensions (they will be suggested automatically)

4. Test the theme:
   - Press `F5` to open Extension Development Host
   - Test the theme in the new window

### Testing Changes
- Test with different file types (JavaScript, TypeScript, Python, HTML, CSS, Markdown, etc.)
- Check in both light and dark mode compatibility
- Verify syntax highlighting accuracy
- Test UI elements (sidebar, status bar, panels, etc.)

## Color Guidelines

### Primary Colors
- **Background**: Pure white (#ffffff) for maximum readability
- **Primary Text**: Dark gray (#2e2e2e) for optimal contrast
- **Secondary Text**: Medium gray (#666666) for less important text

### Accent Colors
- **Purple** (#8957e5): Keywords, storage types, operators
- **Green** (#0a6a3d): Strings, comments
- **Blue** (#0550ae): Variables, functions, links
- **Orange** (#b33e00): Numbers, constants
- **Teal** (#1d4ed8): Types, classes

### Contrast Requirements
- All text should maintain a contrast ratio of at least 4.5:1
- Consider accessibility for users with visual impairments

## File Structure
```
obsidian-light/
├── .vscode/                 # VS Code configuration
├── images/                  # Theme icons and assets
├── themes/                  # Color theme definitions
├── CHANGELOG.md            # Version history
├── CONTRIBUTING.md         # This file
├── LICENSE                 # MIT license
├── package.json           # Extension manifest
└── README.md              # Project documentation
```

## Pull Request Process
1. Ensure your changes follow the existing code style
2. Update documentation if necessary
3. Test your changes thoroughly
4. Write clear commit messages
5. Submit a pull request with a detailed description

## License
By contributing to this project, you agree that your contributions will be licensed under the same MIT License that covers the project.

## Questions?
If you have any questions about contributing, feel free to:
- Open a [GitHub Discussion](https://github.com/narcilee7/obsidian-light-theme/discussions)
- Contact the maintainer directly

Thank you for helping make Obsidian Light theme better! 🎨
