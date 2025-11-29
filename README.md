
## Terminess Nerd Font
```
curl -OL https://github.com/ryanoasis/nerd-fonts/releases/latest/download/Terminus.tar.xz
```

## Powerlevel 10k
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
```

## Kitty-themes
theme: Catppuccin-Macchiato
from: https://github.com/catppuccin/kitty
```
kitty +kitten themes --reload-in=all Catppuccin-Macchiato
```

## Interception Tools
install:
```
opi interception-tools 
opi interception-caps2esc

cp udevmon.yaml /etc/interception
systemctl start udevmon.service
```