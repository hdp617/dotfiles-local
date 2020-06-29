# dotfiles-local

## install [Homebrew](https://brew.sh/)
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

## install packages from `Brewfile`
```
brew bundle
```

## change shell to `zsh`
```
command -v zsh | sudo tee -a /etc/shells
sudo chsh -s "$(command -v zsh)" "${USER}"
```
