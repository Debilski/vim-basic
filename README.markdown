# vim-basic

Some sensible vim defaults.

## Installation

    cd $HOME
    git clone https://github.com/Debilski/vim-basic.git .vim
    ln -s .vim/vimrc .vimrc
    vim +PlugInstall +qall

## Upgrading

    cd $HOME/.vim
    git pull
    vim +PlugUpgrade +PlugUpdate +qall
