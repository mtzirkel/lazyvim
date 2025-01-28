# 💤 Travis' LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

## Install .10+ Neovim

```
sudo add-apt-repository ppa:neovim-ppa/unstable
sudo apt update
```

## Clone this config
```
git clone  https://github.com/mtzirkel/lazyvim.git ~/.config/nvim
```
-------------------------------------------------------------------------------------------------------------------------------
## Add NerdFonts
```
mkdir -p ~/.local/share/fonts
cd ~/.local/share/fonts && curl -fLO https://github.com/ryanoasis/nerd-fonts/raw/HEAD/patched-fonts/DroidSansMono/DroidSansMNerdFont-Regular.otf

fc-cache -fv  
```
