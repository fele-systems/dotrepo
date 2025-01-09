# Fele's dot files

## Clone this repo and symlink its files:

```shell
git clone https://github.com/fele-systems/dotrepo.git
ln -s ~/dotrepo/.config/shell/profile .zprofile

mkdir ~/.config/nvim & ln -s ~/dotrepo/.config/nvim/init.vim ~/.config/nvim/init.vim
```

## Install [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) (optional)

If installing oh-my-zsh, first make sure your .zprofile has been loaded as the .zprofile is usually only loaded during login.

```shell
source .zprofile
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
