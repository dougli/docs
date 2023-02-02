1. Install ohmyzsh. This will also trigger Xcode to install developer tools, which will get git.

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

2. Enable these plugins in the .zshrc file

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

3. Install [homebrew](https://brew.sh/)

4. Run this blob in the terminal

```sh
# Install basic stuff
brew install thefuck
brew install emacs
brew install fzf

# Increase keyboard repeat rate to 🚀 speed
defaults write NSGlobalDomain KeyRepeat -int 1
defaults write NSGlobalDomain InitialKeyRepeat -int 10

# Configure git
git config --global user.name "Douglas Li"
git config --global user.email "lidouglas@gmail.com"
```

6. Install [Visual Studio Code](https://code.visualstudio.com/download).
