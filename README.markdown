Readme
========
Source the following files in this directory your main bash_profile/bashrc file.

```sh
source ~/bashrc/bashrc
source ~/.bash_box_aliases
# create the .bash_box_aliases file if it does not exist
```

Usual Settings
==================

Set git name and email to
```sh
git config --global user.name "Name"
git config --global user.emai email@example.com
git config --global color.ui true
```

OSX
=========

```sh
# install homebrew
ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
brew tap phinze/cask
brew install brew-cask
brew cask install google-chrome
brew install \
  the_silver_searcher \
  vim \
  git \
  exuberant-ctags \
  cloc \
  ncdu 
``` 

Use brew to install the common packages listed below.

Ubuntu
===================

    sudo apt-get install \
      silversearcher-ag \
      vim \
      git \
      exuberant-ctags \
      ncdu

