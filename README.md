.dotfiles
=========

Contains some basic configuration for Vim, Tmux, and Git.

Install:

1. Clone this repository to your Mac or Linux Home directory. <br>


2. If you haven't installed Vim or Tmux, you can use homebrew, apt-get, yum to install them. <br>


3. After cloning: <br>
   ln -s  ~/.dotfiles/vim ~/.vim <br>
   ln -s  ~/.dotfiles/vimrc ~/.vimrc <br>
   ln -s  ~/.dotfiles/tmux.conf ~/.tmux.conf <br><br>
   
   Optional: <br>
   ln -s  ~/.dotfiles/bash_profile ~/.bash_profile (show branch name when you are in a git directory) <br>
   ln -s  ~/.dotfiles/gitconfig ~/.gitconfig <br><br>
   

4. cd ~/.dotfiles <br>
   git submodule init <br>
   git submodule update <br>
   (The submodule will install all vim plugins) <br><br>


5. If you want to update all vim bundled plugins later: <br>
   git submodule foreach git pull origin master <br><br>

   Or update one plugin: <br>
   cd ~/.dotfiles/vim/bundle/plugin_name <br>
   git pull origin master <br>







