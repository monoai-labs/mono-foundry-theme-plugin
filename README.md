# monofoundry Theme Pack

18 popular terminal themes for [monofoundry](https://github.com/monoai-co/monofoundry), converted from [shiki](https://github.com/shikijs/textmate-grammars-themes) TextMate themes.

## Features

- 18 curated themes spanning dark and light appearances
- One-step install — all themes appear in the `/theme` picker immediately
- Converted from shiki TextMate themes with automatic fallback colours for uncovered tokens
- Themes cover syntax highlighting, diffs, markdown, status bar, spinners, and UI chrome
- Pure JavaScript — no native dependencies, works on every platform monofoundry supports

## Installation

```bash
monofoundry plugin install github:monoai-labs/mono-foundry-theme-plugin
```

Once installed and enabled, all themes appear in the `/theme` picker.

## Themes

| Name                | Appearance |
| ------------------- | ---------- |
| dark-plus           | dark       |
| light-plus          | light      |
| monokai             | dark       |
| nord                | dark       |
| one-dark-pro        | dark       |
| github-dark         | dark       |
| github-light        | light      |
| dracula             | dark       |
| material-theme      | dark       |
| solarized-dark      | dark       |
| solarized-light     | light      |
| rose-pine           | dark       |
| catppuccin-mocha    | dark       |
| tokyo-night         | dark       |
| gruvbox-dark-medium | dark       |
| kanagawa-wave       | dark       |
| synthwave-84        | dark       |
| night-owl           | dark       |

## Switching themes

```bash
/theme                   # interactive picker
/theme tokyo-night       # switch directly
/theme reset             # restore default
```

Restart any running monofoundry sessions after changing config for it to take effect.

## Configuration

This plugin has no configurable options. All themes are registered at activation time and available immediately.

## License

MIT
