# developers-system-setup

### Initial Setup

- [Windows 10 setup](#windows-setup)

# Windows Setup
### What are going to do

- [Install Ubuntu into our system](#installing-ubuntu-on-windows-10)
- [Install ZSH shell](#install-zsh-shell)
- Install OhMyZSH plugin
- Install Node via NVM
- Install Ruby via RBENV
- Install Postgres

### Installing Ubuntu On Windows 10

### Install ZSH Shell

Update and install ZSH shell

    $ sudo apt-get update && sudo apt-get -y install zsh

Check the version to see if it's running on your machine.

    $ zsh --version

Make ZSH shell your default shell

    $ chsh -s /bin/zsh
