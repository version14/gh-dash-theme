# Version 14 Theme for gh-dash

A [gh-dash](https://github.com/dlvhdr/gh-dash) theme built around the **Version 14** brand palette — the same palette used across the [Zed](https://github.com/version14/zed-theme), [VS Code](https://github.com/version14/vscode-theme), [Neovim/Vim](https://github.com/version14/nvim-theme), [Ghostty](https://github.com/version14/ghostty-theme), and [Starship](https://github.com/version14/starship-theme) ports.

## Variants

| Variant | File |
|---|---|
| **Version 14** | `version14.yml` |
| **Version 14 Black** | `version14-black.yml` |
| **Version 14 Light** | `version14-light.yml` |

> The violet accent (`text.secondary`, `text.actor`, `border.primary`, `icon.owner`) is currently a **placeholder** hue, standing in for a retired lime-green accent while a permanent replacement is chosen.

## Installation

Replace the `theme:` block in `~/.config/gh-dash/config.yml` with the contents of the variant file you want. `gh-dash`'s theme schema covers `text.primary/secondary/inverted/faint/warning/success/actor`, `background.selected`, `border.primary/secondary/faint`, and `icon.newcontributor/contributor/collaborator/member/owner/unknownrole` — every file here fills in all of them.

## Color Roles

| Key | Version 14 | Version 14 Black | Version 14 Light |
|---|---|---|---|
| `text.primary` | `#F2F4F6` | `#F2F4F6` | `#0D0F11` |
| `text.secondary` | `#B7A2FF` | `#B7A2FF` | `#5F3BBB` |
| `text.inverted` | `#1A1E23` | `#0C0D0E` | `#F4F5F6` |
| `text.faint` | `#6E737A` | `#6E737A` | `#636870` |
| `text.warning` | `#FFA85E` | `#FFA85E` | `#8F4400` |
| `text.success` | `#4BDE7F` | `#4BDE7F` | `#166534` |
| `text.actor` | `#B7A2FF` | `#B7A2FF` | `#5F3BBB` |
| `background.selected` | `#1A1E23` | `#0F0F10` | `#D2D4D7` |
| `border.primary` | `#B7A2FF` | `#B7A2FF` | `#5F3BBB` |
| `border.secondary` | `#78AFFF` | `#78AFFF` | `#0054CB` |
| `border.faint` | `#1A1E23` | `#0F0F10` | `#D2D4D7` |
| `icon.newcontributor` | `#ED8EF3` | `#ED8EF3` | `#8C2293` |
| `icon.contributor` | `#FFA85E` | `#FFA85E` | `#8F4400` |
| `icon.collaborator` | `#4BDE7F` | `#4BDE7F` | `#166534` |
| `icon.member` | `#78AFFF` | `#78AFFF` | `#0054CB` |
| `icon.owner` | `#B7A2FF` | `#B7A2FF` | `#5F3BBB` |
| `icon.unknownrole` | `#6E737A` | `#6E737A` | `#636870` |

## Also available for Zed, VS Code, Neovim/Vim, Ghostty, and Starship

- [Zed extension](https://github.com/version14/zed-theme)
- [VS Code extension](https://github.com/version14/vscode-theme)
- [Neovim/Vim plugin](https://github.com/version14/nvim-theme)
- [Ghostty theme](https://github.com/version14/ghostty-theme)
- [Starship palette](https://github.com/version14/starship-theme)

## License

[MIT](./LICENSE) © [Mathieu Souflis](https://mathieusouflis.fr)
