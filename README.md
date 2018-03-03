<p align="center">
    <img src="https://i.imgur.com/z0iDrR8.png" alt="Screenshot">
</p>

# base16-faded
A faded yet colorful scheme for Vim.

## Requirements
We have to prepare .Xresources first. Save [the colorscheme file](https://github.com/aesophor/dotfiles/blob/master/.x/colorscheme/base16-faded) as `~/.x/colorscheme/base16-faded`,
then add the following two lines in .Xresources
```
! Colors (Replace aesophor with your username)
#include "/home/aesophor/.x/colorscheme/base16-faded"
```

## Installation
* Installing via [Vundle](https://github.com/VundleVim/Vundle.vim#quick-start):
add to .vimrc in the Vundle plugin section.
```
Plugin 'aesophor/base16-faded'
```

then fire up vim, and run `:PluginInstall`

* Installing via [Pathogen](https://github.com/tpope/vim-pathogen#installation):
```
cd ~/.vim/bundle
git clone https://github.com/aesophor/base16-faded
```

## Post-Installation
Enable base16-faded in your .vimrc
```
set t_Co=256
syntax on
colorscheme base16-faded
```

Also consider install the [vim-airline](https://github.com/vim-airline/vim-airline) plugin to enable an airline theme,
I'm using [minimalist](https://github.com/dikiaap/minimalist) by [dikiaap](https://github.com/dikiaap/) for example.
```
let g:airline_theme='minimalist'
let g:airline#extensions#tabline#enabled = 1
```

## License
Available under the [MIT License](https://github.com/aesophor/dotfiles/blob/master/LICENSE).
