# Changelog

All notable changes to this project are recorded here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
Versioning follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Changed

- The integrated terminal uses the High Contrast palette from terminal-config, for both `Default High Contrast` and `Default High Contrast Light`. The theme stays on `Default High Contrast`; turning on `window.autoDetectColorScheme` switches to the light one in light mode. Bold text keeps its colour.
- Pull request branches are never pulled automatically (`githubPullRequests.pullBranch`), so checking out a pull request never changes the working tree on its own.
- `ACCESSIBILITY.md`: a note that the settings are preferences, a callout for the light high-contrast theme and a link to the shared accessibility statement.

### Added

- `bierner.markdown-mermaid` in `extensions.txt` and in the extensions guide, so Mermaid diagrams show in the markdown preview.
- Initial release: settings, keybindings for macOS and for Windows and Linux, global snippets,
  launch flags and a curated extension list
- Launch and task templates for Python, Node, C and C++, Java and Go
- Setup, reference and extension guides
- CI that validates every JSON file
- `ACCESSIBILITY.md`: the High Contrast theme, word wrap and the one-pattern shortcuts.

### Changed

- Tidied code comments and the contributor guide.
