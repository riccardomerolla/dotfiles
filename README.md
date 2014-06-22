dotfiles.git
============
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure your `zsh`, `byobu` and `emacs` development environment as follows:

```sh
cd $HOME
git clone https://github.com/riccardomerolla/dotfiles.git
ln -sb dotfiles/.zsrc .
ln -sb dotfiles/.bashrc .
mv .emacs.d .emacs.d~
ln -s dotfiles/.emacs.d .
mv .byobu.d .byobu.d~ ; ln -s dotfiles/.byobu.d .
```

