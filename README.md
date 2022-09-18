zsh
```bash
sudo apt install -y zsh
```

oh-my-zsh
```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

zsh-autosuggestions
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

zsh-syntax-highlighting
```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

exa
```bash
sudo apt install -y exa
```

starship
```bash
curl -sS https://starship.rs/install.sh | sh
```

yadm
```bash
sudo apt install -y yadm
yadm clone --bootstrap https://github.com/chernyshaw/dotfiles.git
yadm checkout "/home/che"
```
