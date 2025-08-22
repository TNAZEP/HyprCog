# ‼️‼️‼️ Disclaimer ‼️‼️‼️
My Personal dotfiles for hyprland on Arch
 
<div align="center">

# **HyprCog Dot Files**

![GitHub last commit](https://img.shields.io/github/last-commit/TNAZEP/HyprCog?style=for-the-badge&color=9300ff) ![GitHub repo size](https://img.shields.io/github/repo-size/TNAZEP/HyprCog?style=for-the-badge&color=9300ff)


<br/>

##  Showcase

![screen_1](/assets/screenshots/ImagesShowcase.png)

</div>

# Details
- **OS**: [Arch Linux](https://archlinux.org/)
- **Compositor**: [Hyprland](https://github.com/hyprwm/Hyprland)
- **Bar**: [Waybar](https://github.com/Alexays/Waybar)
- **Terminal**: [Ghostty](https://github.com/ghostty-org/ghostty)
- **Menu**: [Rofi](https://github.com/lbonn/rofi)
- **Notifications**: [Dunst](https://github.com/dunst-project/dunst)
- **Browser**: [Zen Browser](https://github.com/zen-browser) 
- **Font**: [Nerd Font](https://www.nerdfonts.com/)

# Usage
## 📦 Required dependencies:
Install these dependencies manually (Arch) 
```shell
hyprland whitesur-icon-theme ghostty zen-browser dunst rofi
```
Background utility:
`swww`
Follow the [Quick Start Instructions from Hyprland](https://wiki.hyprland.org/Getting-Started/Quick-start/)

## 🧙‍♂️ Setup Hyprland Config
Copy all files from the repo to your hyprland config folder, and rename `_hyprland.conf` to `hyprland.conf` .
```bash
git clone https://github.com/TNAZEP/HyprCog.git
cd dotfiles-hyprland
cp -r ./* ~/.config/hypr
# Rename config file
mv ~/.config/hypr/_hyprland.conf ~/.config/hypr/hyprland.conf 
```

## ✨ Theming Other Applications

<details>
<summary>
instructions 
</summary>

### Default Applications
The themes of other applications are saved in the `dots` folder.
`wofi`, `rofi`, `kitty` and `dunst` can be themed by copying the folders into `~/.config`
```bash
cp -r ./dots/dunst ~/.config
cp -r ./dots/wofi ~/.config
cp -r ./dots/rofi ~/.config
cp -r ./dots/kitty ~/.config
```

### Obsidian
The Obsidian theme can be found in the community theme store, just look up `Apatheia`. Install the theme which is developed by @AmadeusWM, @Zenneh. 

### GTK Theme
For GTK: [Orchis-Theme](https://github.com/vinceliuice/Orchis-theme)
Edit the following files:
- `~/.config/gtk-3.0/settings.ini`
- `~/.config/gtk-4.0/settings.ini`
to:
```conf
[Settings]
gtk-application-prefer-dark-theme=1
gtk-theme-name = Orchis-Dark
```
and you might have to run: 
```bash
gsettings set org.gnome.desktop.interface color-scheme prefer-dark
```
### Eww Bar
Credits to https://github.com/taylor85345
Dependency: `eww-wayland`

</details>

---

<br/>

# ⌨️ Keybinds 
All keybinds can be found in the `keybinds` folder
- `SUPER+SPACE`: Application Launcher (wofi)
- `SUPER+Z`: Prev workspace
- `SUPER+X`: Next workspace
- `SUPER+CTRL+M`: Quit Hyprland
- `SUPER+1,...9,0`: Switch workspace
- `SUPERA+SHIFT+1,...9,0`: Move window to workspace
- `SUPER+ALT+1,...9,0`: Move window to workspace (silent)
- `SUPER+B`: Switch Wallpaper
- `SUPER+V`: Open clipboard history
- `SUPER+RETURN` or `SUPER+T`: Kitty
- `SUPER+F`: Firefox
- `SUPER+O`: Obsidian
- `SUPER+E`: Nautilus
- `SUPER+C`: Zed Editor
- `PRINT`: Screenshot a part of your screen
- `SUPER+PRINT`: Record a part of your screen
- `SUPER+SHIFT+B`: Reset Top Bar (e.g. when connecting new screen)

# ⭐ Credits
- [Vaxry](https://github.com/vaxerski): hyprland
- [Martin Djakovic]([https://github.com/vaxerski](https://github.com/martin-djakovic)): Inspiration and some configs


---

<br/>
<br/>
<br/>

# 🔨 TO-DO
...
