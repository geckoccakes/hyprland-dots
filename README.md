- **Window Manager** • [Hyprland](https://github.com/hyprwm/Hyprland)🎨 Tiles Everywhere!
- **Shell** • [Zsh](https://www.zsh.org) 🐚 &
  [starship](https://github.com/starship/starship) Cross Shell Platform!
- **Terminal** • [WezTerm](https://github.com/wez/wezterm) 💻 A powerful term with gpu support!
- **Panel** • [Waybar](https://aur.archlinux.org/packages/waybar-hyprland-git)🍧 Patched waybar following hyprland faq!
- **Notify Daemon** • [Dunst](https://github.com/dunst-project/dunst) 🍃 Minimalist and functional!
- **Launcher** • [Rofi](https://github.com/davatorium/rofi) 🚀 Rofi!
- **File Manager** • [Ranger](https://github.com/ranger/ranger)🔖 Customizable file manager!
- **GUI Basic-IDE** • [NvChad](https://github.com/NvChad/NvChad) the IDE!

## 🌸 Setup

<img align="center" src="/assets/r-unixporn.webp">

<summary><b>Quick Setup</b></summary>

<div align="left">

<details>
<summary><h3>Hyprland Stuff</h3></summary>

```sh
## Hyprland Stuff
paru -S hyprland-git hyprpicker-git waybar-git dunst nwg-look wf-recorder wlogout wlsunset
```

</details>

<details>
<summary><h3>Dependencies</h3></summary>

- Install it.
  
```sh
paru -S colord ffmpegthumbnailer gnome-keyring grimblast-git gtk-engine-murrine  \
imagemagick kvantum pamixer playerctl polkit-kde-agent qt5-quickcontrols         \
qt5-quickcontrols2 qt5-wayland qt6-wayland swww ttf-font-awesome tumbler         \
ttf-jetbrains-mono ttf-icomoon-feather cliphist qt5-imageformats qt5ct           \
```

```sh
## Not sure.
xwaylandvideobridge-cursor-mode-2-git xdg-desktop-portal-hyprland-git xdotool
```

</details>

<details>
<summary><h3>Apps and Quick Setup</h3></summary>

- Quick Setup

```sh
paru -S btop cava neofetch rofi-lbonn-wayland-git rofi-emoji  \
starship zsh viewnior ocs-url brave-bin file-roller  \
thunar thunar-archive-plugin pipewire  \
pipewire-alsa pipewire-audio pipewire-pulse  \
pipewire-jack wireplumber gst-plugin-pipewire pavucontrol
```

- Fonts:

```sh
noto-fonts-emoji noto-fonts noto-fonts-cjk
```

</details>

</div>

<div align="left">

<details>
<summary><h3>DOTFILES</h3></summary>

```sh
git clone https://github.com/geckoccakes/hyprland-dots $HOME/Downloads/hyprland-dots/
cd $HOME/Downloads/hyprland-dots/
rsync -avxHAXP --exclude '.git*' .* ~/
```

</details>
</div>

## Credits

**Original Dotfiles by: [L I N U X M O B I L E](https://github.com/linuxmobile/).**

_Beauty community: [r/unixporn](https://www.reddit.com/r/unixporn)._

**©** _Artist who make Wallpapers, graphics and more_

**©** _All of mantainers of this amazing and opensource tools :3_

---

© [Owl4ce](https://github.com/owl4ce) © [Ilham25](https://github.com/ilham25) ©
[Siduck](https://github.com/siduck) © [NvChad](https://github.com/NvChad) ©
[Rxyhn](https://github.com/rxyhn) © [AmitGold](https://github.com/AmitGolden)
