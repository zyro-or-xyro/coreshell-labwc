# coreshell-labwc
An simple and lightweight dotfile for labwc Arch-based GNU/Linux distributions

DEPS:
```txt
swww
labwc
eza
fastfetch
waybar
nwg-bar
waypaper
wofi
wofi-emoji
swaync
ttf-jetbrains-mono-nerd
```
Recommended install [EXPERIMENTAL](backup first, this overwrites your existing dotfiles)
```bash
git clone https://github.com/zyro-or-xyro/coreshell
cd .config
rm -rf btop kitty labwc waybar wofi fastfetch matugen nwg-bar waypaper
cd ~/coreshell-labwc/dotfiles
mv -r * ~/.config
cd ..
mv .zshrc ~/
```
