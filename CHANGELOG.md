# Changelog

All notable changes to this project are recorded here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
Versioning follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

## [0.0.1] - 2026-10-22

### Changed

- The integrated terminal uses `GeistMono Nerd Font` (`terminal.integrated.fontFamily`), so Nerd Font prompt symbols draw. The font is free and must be installed from the Nerd Fonts releases; `guides/reference.md` links it. The editor font is unchanged.
- Discord presence shows the file type only: the two Discord extensions no longer send the file name, the workspace name or a repository button.
- The theme is now `Zacess Deep Contrast Dark` from the Zacess Themes extension, fixed whatever the system appearance (`window.autoDetectColorScheme` is `false`), in place of the built-in high contrast pair following the system. `Zacess Deep Contrast Light` is the preferred light theme for anyone who turns following back on. All eight Zacess themes are in the picker. `zacess.zacess-themes@0.3.0` is in `extensions.txt` under a new Themes header.

## 2026-10-19

### Added

- On Windows the integrated terminal opens PowerShell 7 by default, through its launcher in `WindowsApps`, so the path keeps working when PowerShell updates. It starts with `-NoLogo`, so only the welcome banner shows.
- `bierner.markdown-mermaid` in `extensions.txt` and in the extensions guide, so Mermaid diagrams show in the markdown preview.
- Initial release: settings, keybindings for macOS and for Windows and Linux, global snippets,
  launch flags and a curated extension list
- Launch and task templates for Python, Node, C and C++, Java and Go
- Setup, reference and extension guides
- CI that validates every JSON file
- `ACCESSIBILITY.md`: the High Contrast theme, word wrap and the one-pattern shortcuts.

### Changed

- The theme follows the system's light and dark mode: `window.autoDetectColorScheme` is now on, switching between `Default High Contrast` and `Default High Contrast Light`.
- The integrated terminal uses the High Contrast palette from terminal-config, for both `Default High Contrast` and `Default High Contrast Light`. Bold text keeps its colour.
- Pull request branches are never pulled automatically (`githubPullRequests.pullBranch`), so checking out a pull request never changes the working tree on its own.
- `ACCESSIBILITY.md`: a note that the settings are preferences, a callout for the light high-contrast theme and a link to the shared accessibility statement.
- Tidied code comments and the contributor guide.
