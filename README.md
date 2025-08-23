<div align="center">

# ‼️‼️‼️ Disclaimer ‼️‼️‼️
My personal hyprland config. Designed on Arch but should work fine on any distro

</div>
<div align="center">

# **HyprCog Dot Files**

![GitHub last commit](https://img.shields.io/github/last-commit/TNAZEP/HyprCog?style=for-the-badge&color=9300ff) ![GitHub repo size](https://img.shields.io/github/repo-size/TNAZEP/HyprCog?style=for-the-badge&color=9300ff)


<br/>

##  Showcase

![screen_1](/assets/screenshots/ImageShowcase.png)

</div>

# Details
- **OS**: [Arch Linux](https://archlinux.org/)
- **Compositor**: [Hyprland](https://github.com/hyprwm/Hyprland)
- **Bar**: [Waybar](https://github.com/Alexays/Waybar)
- **Terminal**: [Alacritty](https://github.com/alacritty/alacritty/releases)
- **Menu**: [Rofi](https://github.com/lbonn/rofi)
- **Notifications**: [Dunst](https://github.com/dunst-project/dunst)
- **Browser**: [Zen Browser](https://github.com/zen-browser) 
- **Font**: [Nerd Font](https://www.nerdfonts.com/)

# Usage
## 📦 Required dependencies:
Install these dependencies manually (Arch) 
```shell
hyprland alacritty dunst rofi hyprlock brightnessctl alsa-utils
```

## 🧙‍♂️ Setup Hyprland Config
Copy all files from the repo to your hyprland config folder, and rename to `hyprland.conf` .
```bash
git clone https://github.com/TNAZEP/HyprCog.git
cd HyprCog
cp -r ./* ~/.config/hypr
```

</details>

---

<br/>

# ⌨️ Keybinds 
All keybinds can be found in the `keybinds` folder
- `SUPER+SPACE`: Application Menu
- `SUPER+SHIFT+SPACE`: Power Menu
- `SUPER+1,...9,0`: Switch workspace
- `SUPERA+SHIFT+1,...9,0`: Move window to workspace
- `SUPER+RETURN`: Terminal
- `SUPER+F`: Browser
- `SUPER+E`: File Browser
- `SUPER+C`: Editor
- `SUPER+SHIFT+S`: Screenshot a part of your screen
- `SUPER+SHIFT+C`: Reset Top Bar (e.g. when connecting new screen)

# ⭐ Credits
- [Vaxry](https://github.com/vaxerski): hyprland
- [Martin Djakovic](https://github.com/martin-djakovic): Inspiration and base config

---

<br/>
<br/>
<br/>

# 🔨 TO-DO
- Add auto colour generation
...
