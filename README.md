.dotfiles
=========
Basic configuration for Vim, Tmux, Git and Ack. (Note: If you haven't installed Vim or Tmux or Git or Ack, use homebrew or apt-get to install them.)

Install:

Clone this repository to your Mac or Linux Home directory.


Install oh-my-zsh:
**curl -L http://install.ohmyz.sh | sh**      Or      **wget --no-check-certificate http://install.ohmyz.sh -O - | sh**


Symlink the files:
*   **ln -s  ~/.dotfiles/vim ~/.vim**
*   **ln -s  ~/.dotfiles/vimrc ~/.vimrc**
*   **ln -s  ~/.dotfiles/tmux.conf ~/.tmux.conf**
*   **ln -s  ~/.dotfiles/gitconfig ~/.gitconfig**
*   **ln -s  ~/.dotfiles/gitignore_global ~/.gitignore_global**
*   **ln -s  ~/.dotfiles/alias ~/.alias**
*   **ln -s  ~/.dotfiles/ackrc ~/.ackrc**

Install vim bundled plugins:
*   Launch vim and run **:PluginInstall**     
*   Or to install from command line: **vim +PluginInstall +qall**
*   "You Complete Me" Plugin need compiling: **cd ~/.vim/bundle/YouCompleteMe** -----> **./install.sh**


Add alias to zshrc:
*   add **source ~/.zshrc** to zshrc file 


To update vim bundled plugins:
*   **cd ~/.dotfiles/vim/bundle/plugin_name**
*   **git pull origin master**







