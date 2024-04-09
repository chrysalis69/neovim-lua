# Neovim Lua
Here is some of my basic configs for neovim, mostly copied from `ThePrimeagen\init.lua`.

Based upon Lazy package manager, with extra tools like:
* `fugitive` for git
* `rose-pine` theme
* `treesitter` for syntax
* `harpoon` for jumping between files

## Installing
Install Jetbrains Mono font and configure your terminal to use it so that icons work properly.
[Jetbrains Mono](https://www.jetbrains.com/lp/mono/#how-to-install)

Clone into neovim config dir.
```shell
git clone git@github.com:chrysalis69/neovim-lua.git ~/.config/nvim
```

If you have an existing neovim config, you might have to clear that first
```shell
rm -rf ~/.config/nvim
rm -rf ~/.local/share/nvim
```
