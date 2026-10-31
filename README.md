# mydots

Dotfiles for a Linux terminal setup: Alacritty + tmux + Neovim + Yazi.

## What's here

| Config | Path |
|--------|------|
| Alacritty | `.config/alacritty/alacritty.toml` |
| tmux | `.config/tmux/tmux.conf` + `tmux.reset.conf` |
| Neovim (LazyVim) | `.config/nvim/` |
| Yazi + plugins | `.config/yazi/` |
| lazygit | `.config/lazygit/` |
| zsh | `.zshrc` |
| vim | `.vimrc` (for simpler systems) |

## Notes

- Full setup documentation: [ChrisOrton/makeRestore](https://github.com/ChrisOrton/makeRestore)
- tmux plugins managed by TPM (`~/.tmux/plugins/tpm`) — run `prefix + I` after restore to install
- Neovim plugins managed by lazy.nvim — run `:Lazy restore` after restore to install from `lazy-lock.json`
