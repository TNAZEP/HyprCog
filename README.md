# ‼️‼️‼️ Disclaimer ‼️‼️‼️
My Personal dutfiles for hyprland on Arch
 
<div align="center">

# **HyprCog Dot Files**

![GitHub last commit](https://img.shields.io/github/last-commit/TNAZEP/dotfiles-hyprland?style=for-the-badge&color=9300ff) ![GitHub repo size](https://img.shields.io/github/repo-size/TNAZEP/dotfiles-hyprland?style=for-the-badge&color=9300ff)


<br/>

##  Showcase

![screen_1](/assets/screenshots/ImagesShowcase.png)

</div>

# Details
- **OS**: CachyOS (Also Functions on other arch distributions)
- **Compositor**: [Hyprland](https://github.com/hyprwm/Hyprland)
- **Top- and sidebar**: [eww](https://github.com/elkowar/eww)
- **Notifications**: [dunst](https://github.com/dunst-project/dunst)
- **Wallpaper Loader**: [swww](https://github.com/Horus645/swww)
- **Terminal**: [Ghostty](https://github.com/ghostty-org/ghostty)
- **Search menu**: [wofi](https://github.com/uncomfyhalomacro/wofi)
- **Browser**: Zen Browser
- **Font**: [Nerd Font](https://www.nerdfonts.com/)

# Usage
## 📦 Required dependencies:
Install these dependencies manually (Arch) 
```shell
hyprland whitesur-icon-theme ghostty zen-browser 
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

### Switching Primary Screen
Add this line to your config:
```conf
exec=~/.config/hypr/scripts/variables/set_env primary [ID_OF_PRIMAR_SCREEN] # 0, 1, 2, ...
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
- [Back777space](https://github.com/Back777space): for contributing🗿🗿🗿
- [Zenneh](https://github.com/zenneh): the Obsidian theme
- [Taylor85345](https://github.com/taylor85345): the well-organized dotfiles, and top-bar
- [flick0](https://github.com/flick0): inspiring hyprland-setup and useful scripts
- [Vaxry](https://github.com/vaxerski): hyprland


---

<br/>
<br/>
<br/>

# 🔨 TO-DO
...
