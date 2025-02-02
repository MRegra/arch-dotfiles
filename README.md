# Arch Dotfiles 🖥️

Custom dotfiles for my Arch Linux setup, featuring i3, Rofi, Zsh, and more!

## Features

* i3 Window Manager – Custom i3 configuration for productivity and aesthetics.

* i3blocks – Modular status bar with useful system info.

* i3lock-color – Stylish lock screen customization.

* i3status – Lightweight system status bar.

* Rofi – MacOS Spotlight-like app launcher.

* Zsh – Configured with plugins and themes for an improved terminal experience.

---

## Installation

Clone this repository and apply the configurations:

    # Clone the repository
    git clone https://github.com/MRegra/arch-dotfiles.git ~/.dotfiles

    # Change to the dotfiles directory
    cd ~/.dotfiles

    # Symlink the configuration files to your home directory
    stow i3 rofi zsh # Add other directories as needed

If you don’t have stow, install it with:

    sudo pacman -S stow

---

## Setup Guide

### 1. i3 Window Manager

Ensure i3 is installed:

    sudo pacman -S i3-wm

Restart your session to apply changes.

### 2. Rofi Application Launcher

    sudo pacman -S rofi

To launch Rofi:

    rofi -show drun

### 3. Zsh Shell Configuration

Install Zsh and Oh-My-Zsh:

    sudo pacman -S zsh
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

## Screenshots

---

## Todo

---

## Contributing

Feel free to fork and submit pull requests!

## License

MIT License © [MRegra]
