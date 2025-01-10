# Fele's dot files

## Clone this repo and symlink its files:

```shell
git clone https://github.com/fele-systems/dotrepo.git
ln -s ~/dotrepo/.config/shell/profile .zprofile

mkdir ~/.config/nvim && ln -s ~/dotrepo/.config/nvim/init.vim ~/.config/nvim/init.vim
```

## If using [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) (optional)
```shell
(cd dotrepo && git submodule init && git submodule update)

mkdir ~/.config/zsh
ln -s ~/dotrepo/.config/zsh/ohmyzsh ~/.config/zsh/ohmyzsh
ln -s ~/dotrepo/.config/zsh/.zshrc ~/.config/zsh/.zshrc
chsh -s $(which zsh)
```
