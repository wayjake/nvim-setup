# nvim-setup
This is Jake's nvim init file

## 🛠️ Installation
Make a backup of your current nvim and shared folder

```
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

## Clone the repository
```
git clone --depth 1 https://github.com/wayjake/nvim-setup ~/.config/nvim
```

## Install Vim-Plug (UNIX)
**you must have Vim-Plug installed: https://github.com/junegunn/vim-plug

```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
```
:PlugInstall
```

## The Config
[nvim][./nvim]
