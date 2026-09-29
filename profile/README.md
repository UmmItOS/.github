# UmmItOS

<p align="center">
  <a href="https://github.com/UmmItOS/UmmItOS/releases">
    <img alt="GitHub Release" src="https://img.shields.io/github/v/release/UmmItOS/UmmItOS?style=flat-square&logo=linux&logoColor=white&label=Version&color=7c3aed">
  </a>
  <a href="https://github.com/UmmItOS/UmmItOS/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/badge/License-GPL--3.0-7c3aed?style=flat-square">
  </a>
  <a href="https://www.archlinux.org/">
    <img alt="Arch Linux" src="https://img.shields.io/badge/Arch_Linux-1793d1?style=flat-square&logo=arch-linux&logoColor=white&label=Base">
  </a>
  <a href="https://hyprland.org/">
    <img alt="Hyprland" src="https://img.shields.io/badge/Hyprland-58e1ff?style=flat-square&logo=hyprland&logoColor=black&label=WM">
  </a>
</p>

**A streamlined Arch Linux distribution built around the Hyprland dynamic window manager.**

UmmItOS provides a fully automated setup script that transforms a fresh Arch Linux (or Arch-based, e.g. EndeavourOS) installation into a polished Hyprland environment with a curated software stack, hardware auto-detection, and sensible defaults.

## Highlights

- **Quickshell desktop shell**: a single QML shell provides the bar, notifications, launcher, clipboard, wallpaper picker, dashboard, lock screen, Alt+Tab overview, screenshots, screen recording, QR scanner, settings panel and weather widget.
- **Lua Hyprland config**: `hyprland.lua`.
- **Matching login screen**: greetd with a QML greeter.

> **Requirements:** Arch Linux or an Arch-based distro, an AMD GPU (NVIDIA is not supported), and a normal user account (don't run as root).

## Quick Start

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/UmmItOS/UmmItOS/main/setup.sh)
```

Or clone it and run the menu yourself:

```bash
git clone --recursive https://github.com/UmmItOS/UmmItOS && cd UmmItOS && ./install-menu.sh
```

## Repositories

| Repository | Description |
|---|---|
| [UmmItOS/UmmItOS](https://github.com/UmmItOS/UmmItOS) | Installer, dotfiles, and the Quickshell desktop shell |
| [UmmItOS/wallpaper](https://github.com/UmmItOS/wallpaper) | Wallpapers bundled with UmmItOS |
| [UmmItOS/www](https://github.com/UmmItOS/www) | Official documentation website |
| [UmmItOS/.github](https://github.com/UmmItOS/.github) | Organization profile and community health files |

## Documentation

Full installation guides and configuration references are available at the [official documentation site](https://docs.ummit.dev/).

## License

[GPL-3.0](https://github.com/UmmItOS/UmmItOS/blob/main/LICENSE)
