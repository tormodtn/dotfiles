# dotfiles

## Bumblebee

Clone Bumblebee repo into .config/i3/
```
git clone https://github.com/tobi-wan-kenobi/bumblebee-status.git
```

Build package
```
cd bumblebee-status
makepkg -s -i -c
```

## i3-gaps-rounded

Clone i3-gaps-rounded repo into .config/i3/
```
git clone https://aur.archlinux.org/i3-gaps-rounded-git.git
```

Build package
```
cd i3-gaps-rounded-git
makepkg -s -i -c
```

## i3-alternating-layout

Clone i3-alternating-layout repo into .config/i3/
```
git clone https://github.com/olemartinorg/i3-alternating-layout.git
```

## Fonts

Roboto Nerd Font files go in
```
$HOME/.local/share/fonts/
```

Run
```
fc-cache -f -v
```
to update fonts list
