# Dotfiles

Alright... still under construction (pray for me).
This was unofficially forked from [Rafael Conde's](https://github.com/rafaelconde/dotfiles)

## Installation

```shell
$ cd ~/
$ git clone git@github.com:rys1024/dotfiles.git
$ cd ~/dotfiles
$ ./bootstrap.sh
```

The boostrap script will symlink config files from `~/.dotfiles` into `~/` and install the following packages:

- https://github.com/robbyrussell/oh-my-zsh
- https://github.com/zsh-users/zsh-syntax-highlighting
- https://github.com/gmarik/vundle
- https://github.com/creationix/nvm

## Updating

```shell
$ cd ~/.dotfiles
$ git pull
$ ./bootstrap.sh
```
