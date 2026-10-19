# Accessibility

The settings put readability first and every custom shortcut follows one pattern.

> [!NOTE]
> Some of these settings are preferences rather than requirements. Change them freely in your own copy. If a change would help other people too, open an issue or a pull request so I can consider it for everyone.

## Vision

- The colour theme is VS Code's built-in `Default High Contrast`.
- The integrated terminal uses the High Contrast palette from [terminal-config](https://github.com/zaccesss/terminal-config): vivid colours on black, with a light version where every colour reaches 7:1 or more on white. Bold text keeps its colour.
- Word wrap is on, so long lines never need horizontal scrolling. `Cmd+Alt+W` (`Ctrl+Alt+W` on Windows and Linux) switches it off for one file.
- The editor font is 14 points. Raise `editor.fontSize` in `settings.json` as needed.

> [!TIP]
> To switch to `Default High Contrast Light` whenever the system is in light mode, set `window.autoDetectColorScheme` to `true` in `settings.json`. Its terminal colours are already set.

## Keyboard

- Every custom shortcut starts with `Cmd+Alt` on macOS or `Ctrl+Alt` on Windows and Linux, some with Shift added, so there is one pattern to remember.
- [jetbrains-config](https://github.com/zaccesss/jetbrains-config) uses the same pair. `Cmd+Alt+Q` runs a database query in both editors.
- Shortcuts cover focusing the terminal, running tests, toggling inline diagnostics and opening a markdown preview beside the editor. The full list is in [guides/reference.md](guides/reference.md).

## Memory

- Files save automatically when focus leaves VS Code, so switching apps never loses work.

## Feedback wanted

If something here gets in the way, open an [issue](https://github.com/zaccesss/vscode-config/issues/new/choose) describing what happened and what would work better.

## The shared statement

> [!NOTE]
> I keep one shared accessibility statement for all my projects: [zaccesss/accessibility](https://github.com/zaccesss/accessibility) or on [my site](https://isaacadjei.me/accessibility). This file takes precedence where the two differ.
