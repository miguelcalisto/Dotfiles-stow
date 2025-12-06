usar GNU stow para instalar
```bash
sudo apt install stow
```


 ```bash
sudo apt update -y
sudo apt install -y \
    rofi neofetch vim neovim zsh fish tmux chafa i3blocks git diodon i3lock \
    i3-wm pcmanfm tilix fonts-firacode lxappearance lsd dunst wlogout \
    gnome-screenshot picom htop btop kitty cava systemd fonts-powerline \
    curl wget python3-pip ripgrep python3-venv psensor alacritty polybar
```

```bash
cd ~
git clone https://github.com/miguelcalisto/Dotfiles-stow.git
cd Dotfiles-stow
```

```bash
stow bash zsh tmux vim config scripts
```
```bash
ls -la ~ | grep '\.zshrc\|\.bashrc\|\.tmux.conf'
```
```bash
chmod +x ~/.local/bin/*
chmod +x ~/scripts/*
chmod +x ~/SCRIPTS/*
```


```bash
cp ~/.bashrc ~/.bashrc.bak
```
