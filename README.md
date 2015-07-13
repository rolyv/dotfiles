dotfiles.git
============

```sh
cd $HOME
git clone https://github.com/rolyv/dotfiles.git
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
ln -sb dotfiles/.racketrc .
mv .emacs.d .emacs.d~
ln -s dotfiles/.emacs.d .
```
