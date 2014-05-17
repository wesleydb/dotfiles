.dotfiles
=========
Contains some basic configuration for Vim, Tmux, and Git.

Install:

1. Clone this repository to your Mac or Linux Home directory.<br>

2. Note: If you haven't installed Vim or Tmux or Git, use homebrew or apt-get to install them.<br>

3. After cloning:<br>
    ln -s  ~/.dotfiles/vim ~/.vim <br>
    ln -s  ~/.dotfiles/vimrc ~/.vimrc <br>
    ln -s  ~/.dotfiles/tmux.conf ~/.tmux.conf <br><br>
    ln -s  ~/.dotfiles/gitconfig ~/.gitconfig <br><br>

4. Insstall vim bundled plugins:<br>
    Launch vim and run *:PluginInstall*
    Or to install from command line: *vim +PluginInstall +qall*

5. To update all vim bundled plugins:<br>
   cd ~/.dotfiles/vim/bundle/plugin_name<br>
   git pull origin master<br>







