.dotfiles
=========
Basic configuration for Vim, Tmux, and Git.

Install:

1. Clone this repository to your Mac or Linux Home directory.


2. Note: If you haven't installed Vim or Tmux or Git, use homebrew or apt-get to install them.


3. Symlink the files:

*   **ln -s  ~/.dotfiles/vim ~/.vim**
*   **ln -s  ~/.dotfiles/vimrc ~/.vimrc**
*   **ln -s  ~/.dotfiles/tmux.conf ~/.tmux.conf**
*   **ln -s  ~/.dotfiles/gitconfig ~/.gitconfig**


4. Install vim bundled plugins:

*   Launch vim and run **:PluginInstall**
*   Or to install from command line: **vim +PluginInstall +qall**


5. To update vim bundled plugins:

*   **cd ~/.dotfiles/vim/bundle/plugin_name**
*   **git pull origin master**







