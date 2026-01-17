# Lucyna Rice – Hyprland Setup

A polished **Linux rice** running **Hyprland**, designed for a clean, aesthetic, and efficient desktop experience.

> Check out the showcase on [r/LinuxPorn](https://www.reddit.com/r/LinuxPorn/comments/1m2su9k/hyprland_lucyna_rice/)

---

## Screenshots

<a href="https://github.com/user-attachments/assets/8209a5d1-779d-4684-b108-6b18426b5144">
  <img src="https://github.com/user-attachments/assets/8209a5d1-779d-4684-b108-6b18426b5144" width="600" />
</a>
<a href="https://preview.redd.it/hyprland-lucyna-rice-v0-520k6tj84kdf1.png?width=1080&crop=smart&auto=webp&s=1e6522de4b3ebb55229f235f7652769ca94bf2a2">
  <img src="https://preview.redd.it/hyprland-lucyna-rice-v0-520k6tj84kdf1.png?width=1080&crop=smart&auto=webp&s=1e6522de4b3ebb55229f235f7652769ca94bf2a2" width="600" />
</a>
<a href="https://preview.redd.it/hyprland-lucyna-rice-v0-qke1asjk4kdf1.png?width=1080&crop=smart&auto=webp&s=48ce346eef913e370737e0ff4ce7c7fe1aa6f5e4">
  <img src="https://preview.redd.it/hyprland-lucyna-rice-v0-qke1asjk4kdf1.png?width=1080&crop=smart&auto=webp&s=48ce346eef913e370737e0ff4ce7c7fe1aa6f5e4" width="600" />
</a>
<a href="https://preview.redd.it/hyprland-lucyna-rice-v0-oeqfnedy4kdf1.png?width=1080&crop=smart&auto=webp&s=143178fb12bd6a0a786390113a4795cc4345cc9b">
  <img src="https://preview.redd.it/hyprland-lucyna-rice-v0-oeqfnedy4kdf1.png?width=1080&crop=smart&auto=webp&s=143178fb12bd6a0a786390113a4795cc4345cc9b" width="600" />
</a>
<a href="https://preview.redd.it/hyprland-lucyna-rice-v0-05ytno395kdf1.png?width=1080&crop=smart&auto=webp&s=b06a9224f2a64b12e8a424811bc153ec520a9df3">
  <img src="https://preview.redd.it/hyprland-lucyna-rice-v0-05ytno395kdf1.png?width=1080&crop=smart&auto=webp&s=b06a9224f2a64b12e8a424811bc153ec520a9df3" width="600" />
</a>
<a href="https://preview.redd.it/hyprland-lucyna-rice-v0-m9t3qf2o5kdf1.png?width=1080&crop=smart&auto=webp&s=e3c4c54502f51dfc0286c8651dc630cf32e9e9b7">
  <img src="https://preview.redd.it/hyprland-lucyna-rice-v0-m9t3qf2o5kdf1.png?width=1080&crop=smart&auto=webp&s=e3c4c54502f51dfc0286c8651dc630cf32e9e9b7" width="600" />
</a>

---

## Overview

Lucyna rice is a fully themed Wayland setup using **Hyprland** as the compositor. The rice focuses on:

- Cohesive aesthetics across GTK, Qt, and terminal apps  
- Smooth animations and transparency  
- Easy-to-use keybindings and workflow enhancements  

This rice is ideal for users who want a visually appealing Wayland desktop without sacrificing usability.

---

## Features

- Custom wallpapers and color schemes  
- Themed terminal with Fira Code font  
- Unified GTK and icon theme  
- Polished bar and launcher setup  
- Optimized keybindings for Hyprland  
- Lightweight scripts to enhance usability  
- Wayland-native screenshot workflow  

---

## Software & Tools Used

| Category          | App/Tool |
|------------------|----------|
| Compositor/WM     | Hyprland |
| Bar/Panel         | Waybar |
| Launcher           | Rofi / Wofi |
| Terminal           | Kitty / Alacritty |
| GTK Theme          | Graphite-Dark |
| Icon Theme         | Papirus-Dark |
| Fonts              | Fira Code, Ubuntu |
| Utilities          | wl-clipboard, grim, slurp, python-pywal |

> Replace or add entries depending on your exact setup.

---

## Installation

### Prerequisites

Install the following (example for Arch Linux):

```bash
sudo pacman -S hyprland waybar rofi kitty \
    papirus-icon-theme gtk-theme-graphite \
    xdg-desktop-portal-hyprland \
    wl-clipboard grim slurp python-pywal
