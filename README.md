# iTerm2-VSCode-Color-Configuration
Personal Modified iTerm colour themes, zsh configurations and configurations for VSCode

### Install Oh-my-zsh
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Set `ZSH_THEME="agnoster"` to `~/.zshrc`

### Install powerline fonts [Powerline](https://github.com/powerline/fonts)
```bash
# clone
git clone https://github.com/powerline/fonts.git --depth=1
# install
cd fonts
./install.sh
# clean-up a bit
cd ..
rm -rf fonts
```

### install [PowerLevel10k](https://github.com/romkatv/powerlevel10k#Homebrew) and put that into .zshrc
```bash
brew install romkatv/powerlevel10k/powerlevel10k
echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
```

