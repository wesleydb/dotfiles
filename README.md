.dotfiles
=========

Contains some basic configuration for Vim, Tmux, and Git.

Install:

1. Clone this repository to your Mac or Linux Home directory.


2. If you haven't installed Vim or Tmux, you can use homebrew, apt-get, yum to install them.


3. After cloning:
   ln -s  ~/.dotfiles/vim ~/.vim
   ln -s  ~/.dotfiles/vimrc ~/.vimrc
   ln -s  ~/.dotfiles/tmux.conf ~/.tmux.conf
   
   Optional:
   ln -s  ~/.dotfiles/bash_profile ~/.bash_profile (show branch name when you are in a git directory)
   ln -s  ~/.dotfiles/gitconfig ~/.gitconfig
   

4. cd ~/.dotfiles
   git submodule init
   git submodule update
   (The submodule will install all vim plugins)


5. If you want to update all vim bundled plugins later:
   git submodule foreach git pull origin master

   Or update one plugin:
   cd ~/.dotfiles/vim/bundle/plugin_name
   git pull origin master







