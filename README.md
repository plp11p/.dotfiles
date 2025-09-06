**Required packages:**

- **Terminal:** ghostty  
- **Shell:** zsh *(optional: fzf, bat)*  
- **Editor:** neovim  
- **Notification daemon:** mako  
- **Bar:** waybar  
- **App launcher:** wofi  
- **File manager:** yazi  
- **Bluetooth manager:** blueman  
- **Screenshot tools:** slurp + grim  
- **Resource monitor:** btop  
- **Blue light filter:** wlsunset  
- **Image viewer:** imv  
- **Video player:** celluloid  
- **Required fonts** woff2-font-awesome, ttf-nerd-fonts-symbols, ttf-jetbrains-mono
- **Clibord manager** wl-clipboard
- **Manager for GTK** nwg-look
- **Wallpaper** swww

```bash
sudo pacman -S fzf blueman ghostty zsh neovim wlsunset bat imv swww celluloid mako slurp grim waybar wofi btop yazi wl-clipboard  woff2-font-awesome ttf-nerd-fonts-symbols ttf-jetbrains-mono
```
*Also update cache fonts*
```fc-cache -fv```

___
**Download**

```bash
git clone https://github.com/plp11p/dotfiles ~/dotfiles && cd ~/dotfiles && mv -f .zshrc .p10k.zsh .zcompdump ~/ && mv -f config/* ~/.config/
```
___
**Make GTK Theme**
```bash
paru -S catppuccin-gtk-theme-mocha nwg-look

#or

yay -S catppuccin-gtk-theme-mocha nwg-look
```
