# Contributing

Thanks for taking an interest. Contributions are welcome: setting fixes, keybinding
corrections and extension list updates.

## What belongs here

- A wrong key or value in `settings.json`
- A keybinding whose command id does not exist
- An extension id that is wrong or unpublished
- Improvements to the guides

## What does not belong here

- A setting or extension that only reflects one person's taste rather than something broadly
  useful, keep that in your own copy

## How to contribute

1. Fork the repository and create a branch named `fix/<short-description>` or
   `feat/<short-description>`.
2. Make your change. Check a keybinding's command id against the extension's own
   `package.json` `contributes.commands` first, since a wrong id fails silently.
3. Open a pull request with a clear title and a one-paragraph description of what changed and
   why. CI validates that every JSON file parses.

## Style rules

> [!IMPORTANT]
> - **Comments**: explain the why, not the what.

## Reporting bugs

Open an issue with your VS Code version and platform, what you expected versus what happened.

More about me and my work: [isaacadjei.me](https://isaacadjei.me).
