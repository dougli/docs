1. Install ohmyzsh

```
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

```
brew install thefuck
brew install emacs
```

