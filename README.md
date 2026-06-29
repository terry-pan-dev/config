# config

Dotfiles/config snippets for a few apps.

## Neovim

To use the Neovim config on a new machine:

```sh
git clone https://github.com/terry-pan-dev/config.git ~/config
mkdir -p ~/.config
ln -sfn ~/config/nvim ~/.config/nvim
```

Then start Neovim:

```sh
nvim
```

`nvim/lazy-lock.json` is tracked, so plugin versions stay reproducible across machines.
