.vim
====
Original from [jessfraz/.vim](https://github.com/jessfraz/.vim)

My vim dot files. the `.vimrc` file is saved to [vimrc](https://github.com/bugbuilder/.vim/blob/master/vimrc).

Just run the following commands via terminal to get perfectly set up:

```console
$ cd ~/
$ git clone --recursive https://github.com/bugbuilder/.vim.git .vim
$ ln -sf $HOME/.vim/vimrc $HOME/.vimrc
$ cd $HOME/.vim
$ git submodule update --init
```

## Pathogen
The vim dot files make use of the excellent [Pathogen](https://github.com/tpope/vim-pathogen) runtime path manager to install plugins and runtime files into their own private directiories.

Currently using version 2.4 of Pathogen

## Updating and Installing

You can use the [`Makefile`](Makefile) to run a series of commands.

```console
$ make help
install                        Sets up symlink for user and root .vimrc for vim and neovim.
README.md                      Generates and updates plugin info in README.md.
remove-submodule               Removes a git submodule (ex MODULE=bundle/nginx.vim).
update-pathogen                Updates pathogen.
update-plugins                 Updates all plugins.
update                         Updates pathogen and all plugins.
```

## Plugins Used

* [github.com/Raimondi/delimitMate](https://github.com/Raimondi/delimitMate.git)
* [github.com/zchee/deoplete-go](https://github.com/zchee/deoplete-go.git)
* [github.com/Shougo/deoplete.nvim](https://github.com/Shougo/deoplete.nvim.git)
* [github.com/scrooloose/nerdtree](https://github.com/scrooloose/nerdtree.git)
* [github.com/Xuyuanp/nerdtree-plugin.git](https://github.com/Xuyuanp/nerdtree-git-plugin.git)
* [github.com/chr4/nginx.vim](https://github.com/chr4/nginx.vim.git)
* [github.com/joshdick/onedark.vim](https://github.com/joshdick/onedark.vim.git)
* [github.com/godlygeek/tabular](https://github.com/godlygeek/tabular.git)
* [github.com/SirVer/ultisnips](https://github.com/SirVer/ultisnips.git)
* [github.com/vim-airline/vim-airline](https://github.com/vim-airline/vim-airline.git)
* [github.com/ntpeters/vim-better-whitespace](https://github.com/ntpeters/vim-better-whitespace.git)
* [github.com/ap/vim-buftabline](https://github.com/ap/vim-buftabline.git)
* [github.com/tpope/vim-five.git](https://github.com/tpope/vim-fugitive.git)
* [github.com/fatih/vim-go](https://github.com/fatih/vim-go.git)
* [github.com/fatih/vim-hclfmt](https://github.com/fatih/vim-hclfmt.git)
* [github.com/terryma/vim-multiple-cursors](https://github.com/terryma/vim-multiple-cursors.git)
* [github.com/uarun/vim-protobuf](https://github.com/uarun/vim-protobuf.git)
* [github.com/tpope/vim-sensible](https://github.com/tpope/vim-sensible.git)
* [github.com/wgwoods/vim-systemd-syntax](https://github.com/wgwoods/vim-systemd-syntax.git)
* [github.com/Raimondi/delimitMate](https://github.com/Raimondi/delimitMate.git)
* [github.com/zchee/deoplete-go](https://github.com/zchee/deoplete-go.git)
* [github.com/Shougo/deoplete.nvim](https://github.com/Shougo/deoplete.nvim.git)
* [github.com/scrooloose/nerdtree](https://github.com/scrooloose/nerdtree.git)
* [github.com/Xuyuanp/nerdtree-plugin.git](https://github.com/Xuyuanp/nerdtree-git-plugin.git)
* [github.com/chr4/nginx.vim](https://github.com/chr4/nginx.vim.git)
* [github.com/joshdick/onedark.vim](https://github.com/joshdick/onedark.vim.git)
* [github.com/godlygeek/tabular](https://github.com/godlygeek/tabular.git)
* [github.com/SirVer/ultisnips](https://github.com/SirVer/ultisnips.git)
* [github.com/vim-airline/vim-airline](https://github.com/vim-airline/vim-airline.git)
* [github.com/ntpeters/vim-better-whitespace](https://github.com/ntpeters/vim-better-whitespace.git)
* [github.com/ap/vim-buftabline](https://github.com/ap/vim-buftabline.git)
* [github.com/tpope/vim-five.git](https://github.com/tpope/vim-fugitive.git)
* [github.com/fatih/vim-go](https://github.com/fatih/vim-go.git)
* [github.com/fatih/vim-hclfmt](https://github.com/fatih/vim-hclfmt.git)
* [github.com/terryma/vim-multiple-cursors](https://github.com/terryma/vim-multiple-cursors.git)
* [github.com/uarun/vim-protobuf](https://github.com/uarun/vim-protobuf.git)
* [github.com/tpope/vim-sensible](https://github.com/tpope/vim-sensible.git)
* [github.com/wgwoods/vim-systemd-syntax](https://github.com/wgwoods/vim-systemd-syntax.git)
