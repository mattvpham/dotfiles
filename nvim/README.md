# nvim

## Windows

On Windows, Neovim runs ~/AppData/Local/nvim/init.vim at startup.

Create the file if it does not exist, then paste this in the file:

'''
set runtimepath+=~/vimfiles,~/vimfiles/after
set packpath+=~/vimfiles
source ~/_vimrc
'''

Next, copy this folder's vimrc file to `~/_vimrc`.

## Linux / OS X

On Linux / OSX, the config file is `~/.config/nvim/init.vim`.

Create the file if it does not exist, then paste this in the file:

'''
set runtimepath+=~/vimfiles,~/vimfiles/after
set packpath+=~/vimfiles
source ~/_vimrc
'''

Next, copy this folder's vimrc file to `~/_vimrc`.

