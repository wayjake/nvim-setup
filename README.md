# nvim-setup
This is my nvim init file

These are normally located at, ~/.config/nvim/init.vim (normally meaning from the one time I've installed nvim so far on MacOs)

## 🛠️ Installation
Make a backup of your current nvim and shared folder

```
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

## Clone the repository
```git clone --depth 1 https://github.com/AstroNvim/AstroNvim ~/.config/nvim```

**you must have Vim-Plug installed: https://github.com/junegunn/vim-plug


```
" turn relative line numbers on
:set relativenumber
" Highlight cursor line underneath the cursor horizontally.
set cursorline

" Turn syntax highlighting on.
syntax on
" Enable type file detection. Vim will be able to try to detect the type of file in use.
filetype on
" Enable plugins and load plugin for the detected file type.
filetype plugin on
" Load an indent file for the detected file type.
filetype indent on

call plug#begin()
Plug 'ncm2/ncm2'
Plug 'SirVer/ultisnips'
Plug 'honza/vim-snippets'
Plug 'ThePrimeagen/vim-be-good'
call plug#end()
```
