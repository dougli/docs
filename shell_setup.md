1. Install ohmyzsh. This will also trigger Xcode to install developer tools, which will get git.

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

2. Install some zsh plugins:

```sh
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

3. Enable these plugins in the .zshrc file

```sh
ZSH_THEME="powerlevel10k/powerlevel10k"

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

4. Install [homebrew](https://brew.sh/)
5. Run this blob in the terminal:

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

6. Get the [Powerlevel10k](https://github.com/romkatv/powerlevel10k) theme for zsh.
7. Install [Visual Studio Code](https://code.visualstudio.com/download).
8. Run `shell command` in VSCode to install the `code` command in the terminal.
