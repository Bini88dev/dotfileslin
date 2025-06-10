# Dotfiles for linux distros...
My easy backup & restore of main config files...

## Install yadm, before any furhter TODOs
```
sudo apt install yadm
```
Use the proprietary package manager for your distro.

### Clone the dotfiles
```
yadm clone https://github.com/Bini88dev/dotfileslin.git
```

### Confirm changes...
```
yadm checkout "home/$USER"
```

### Clear & regenerate font cache after clone
```
fc-cache -f -v
```
Set all over Nerd Font... windows terminal, linux terminal, terminator, etc...

