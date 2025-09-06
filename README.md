**Required packages:**

- **Terminal:** ghostty
- **Shell:** zsh (optional: fzf, bat)
- **Editor:** neovim
- **Bar:** waybar
- **File manager**: yazi
- **App launcher**: wofi
- **Notification daemon:** mako
- **Bluetooth manager:** blueman
- **Video player:** celluloid
- **Resource monitor:** btop
- **Screenshot tools:** grim (paired with slurp)
- **Image viewer:** imv
- **Manager for GTK:** nwg-look
- **Screenshot tools:** slurp (paired with grim)
- **Wallpaper:** swww
- **Required fonts** ttf-jetbrains-mono ttf-nerd-fonts-symbols woff2-font-awesome
- **Clipboard manager**: wl-clipboard
- **Blue light filter:** wlsunset

```bash
sudo pacman -Sy bat blueman btop celluloid fzf ghostty grim imv mako neovim slurp swww ttf-jetbrains-mono ttf-nerd-fonts-symbols waybar wl-clipboard wlsunset woff2-font-awesome wofi yazi zsh
```
*Also update cache fonts*
```fc-cache -fv```

___
**Download**

```bash
git clone https://github.com/plp11p/dotfiles && cd ~/dotfiles && mv -f .zshrc .p10k.zsh .zcompdump ~/ && mv -f config/* ~/.config/
```
___
**Make GTK Theme**
```bash
paru -S catppuccin-gtk-theme-mocha nwg-look

#or

yay -S catppuccin-gtk-theme-mocha nwg-look
```
