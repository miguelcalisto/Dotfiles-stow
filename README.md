usar GNU stow para instalar
```bash
sudo apt install stow
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
