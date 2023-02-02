1. Install ohmyzsh

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

3. Enable these plugins in the .zshrc file

```sh
plugins=(
    docker
    docker-compose
    fzf
    gitfast
    macos
    thefuck
    zsh-autosuggestions
    zsh-syntax-highlighting
)

export EDITOR='emacs'
```

3. Install basic stuff 

```sh
brew install thefuck
brew install emacs
```

4. Run this to increase keyboard repeat rate

```sh
defaults write NSGlobalDomain KeyRepeat -int 1
defaults write NSGlobalDomain InitialKeyRepeat -int 10
```
