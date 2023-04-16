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

## Install Packer (UNIX)
Packer repo: https://github.com/wbthomason/packer.nvim
```
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

```
-- You must run this or `PackerSync` whenever you make changes to your plugin configuration
-- Regenerate compiled loader file
:PackerCompile

-- Clean, then install missing plugins
:PackerInstall
```

## Install Vim-Plug (UNIX)
Vim-Plug repo: https://github.com/junegunn/vim-plug

```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
```
:PlugInstall
```

## The Config
[nvim][./nvim]
