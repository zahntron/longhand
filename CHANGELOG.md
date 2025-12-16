# Changelog

All notable changes to the Longhand syntax highlighting project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2025-12-15

### Added
- Initial release of Longhand syntax highlighting
- Kate text editor support (Linux, Mac, and Windows)
- GNOME Text Editor support (Linux)
- Scene heading highlighting in bold yellow/gold (#FFD700)
- Character name highlighting in blue with bold formatting
- Character extensions support (V.O., O.S., CONT'D) - stays blue when on same line
- Dialogue highlighting in bright blue (#5dade2)
- Parenthetical highlighting in gray italic
- Transition highlighting in purple/bold (CUT TO:, FADE TO:, etc.)
- Custom element highlighting for all-caps + colon in green (#00FF00)
- Section heading support (# markers)
- Synopsis support (= lines)
- Note support ([[text]])
- Boneyard/comment support (/* text */)
- Text formatting: bold (**text**), italic (*text*), underline (_text_)
- Page break support (===)
- Centered text support (>text<)
- Symbols sidebar integration for Kate (scene heading navigation)
- Python-inspired color palette for readability
- Comprehensive documentation (README, INSTALL, LICENSE)
- Logo design inspired by Bazzite/Universal Blue aesthetic

### Features
- **Python-inspired syntax**: Colors and styling influenced by Python syntax highlighting
- **Fountain spec compliance**: Full support for Fountain screenplay format
- **Cross-platform**: Works on both Linux and Windows
- **Multi-editor**: Support for Kate and GNOME Text Editor
- **Accessible colors**: High contrast, readable color choices
- **Professional workflow**: Table of contents navigation via Kate's Symbols sidebar

### Technical Details
- Kate syntax definition (XML format)
- GtkSourceView language definition (for GNOME Text Editor)
- MIT License for maximum compatibility
- Context-aware highlighting (dialogue follows character names)
- Regex-based pattern matching for screenplay elements
- Folding/region markers for structural navigation

### Design Philosophy
The name "Longhand" pays homage to the traditional way screenplays were written by hand, while bringing modern syntax highlighting to the digital age. The color scheme prioritizes:
- **Readability**: High contrast, eye-friendly colors
- **Consistency**: Python-like familiar color patterns
- **Clarity**: Visual hierarchy matching screenplay structure
- **Accessibility**: Colors work well in both light and dark themes

---

## Roadmap

### Planned for Future Releases

[1.1.0] - Proposed
* Auto insall.sh script
* Light theme color variant
* Dark theme color variant
* Additional Fountain elements (dual dialogue, title page, lyrics)
* Enhanced regex patterns for better element detection

[1.2.0] - Proposed
* Kate auto-completion snippets (separate snippet file)
* Additional text editor support (Gedit, Sublime Text)
* VS Code extension port

### Community Contributions Welcome
- Bug fixes
- Color scheme variants
- Additional editor support
- Documentation improvements
- Localization

---

## Version Numbering

This project uses [Semantic Versioning](https://semver.org/):
- **MAJOR**: Breaking changes to syntax definition or installation
- **MINOR**: New features, new editor support, backwards-compatible
- **PATCH**: Bug fixes, documentation updates, color tweaks

---

## How to Report Issues

If you find bugs or have feature requests:
1. Check existing [GitHub Issues](https://github.com/yourusername/longhand/issues)
2. Create a new issue with clear description
3. Include your OS, editor version, and steps to reproduce

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Code style
- Pull request process
- Testing requirements
- Documentation standards
