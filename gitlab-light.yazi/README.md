# gitlab-yazi-theme

GitLab-inspired Yazi flavors — dark and light — ported from [gitlab-nvim-theme](https://github.com/snesjhon/gitlab-nvim-theme).

## Flavors

| Flavor | Preview |
|--------|---------|
| `gitlab-dark` | Dark background (`#28262B`), vivid ANSI palette |
| `gitlab-light` | Light background (`#FAFAFF`), muted accessible palette |

## Install

```sh
ya pkg add snesjhon/gitlab-yazi-theme:gitlab-dark
ya pkg add snesjhon/gitlab-yazi-theme:gitlab-light
```

Then set in `~/.config/yazi/theme.toml`:

```toml
[flavor]
dark  = "gitlab-dark"
light = "gitlab-light"
```

## License

MIT
