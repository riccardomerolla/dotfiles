dotfiles.git
============
Clone and run this on a new EC2 instance running Ubuntu 14.04 LTS to
configure your `bash` and `emacs` development environment as follows:

```sh
cd $HOME
git clone https://github.com/startup-class/dotfiles.git
ln -sb dotfiles/.screenrc .
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
mv .emacs.d .emacs.d~
ln -s dotfiles/.emacs.d .
```

See also http://github.com/riccardomerolla/setup to install prerequisite
programs.