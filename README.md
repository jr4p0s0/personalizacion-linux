# Linux Customization Course (hack4u.io)

*Read this in other languages: [Español](README_es.md)*

This repository contains the configuration files for the packages used in the Linux customization course from [hack4u.io](https://hack4u.io/) taught by s4vitar.

## Repository Contents

Configuration files for the following packages:
- [ ] [**bspwm**](#bspwm)
- [ ] [**rofi**](#rofi)
- [ ] [**sxhkd**](#sxhkd)
- [ ] [**polybar**](#polybar)
- [ ] [**kitty**](#kitty)
- [ ] [**picom**](#picom)

### BSPWM
- [**bspwmrc**](./bspwm/bspwmrc): BSPWM configuration file.
- [**scripts**](./bspwm/scripts/): Directory containing utility scripts for BSPWM.

BSPWM is an event-driven window manager that is configured through scripts. This repository includes BSPWM configuration files and several utility scripts. Since this course is oriented towards creating a pentesting work environment, there are various scripts that, together with picom, allow you to visualize certain information such as current IP, HTB IP, etc.

### Rofi
- [**config.rasi**](./rofi/config.rasi): Rofi configuration file.
- [**themes**](./rofi/themes/): Directory containing Rofi themes.

Rofi is an application launcher and window switcher. This repository includes Rofi configuration files and several themes.

### SXHKD
- [**sxhkdrc**](./sxhkd/sxhkdrc): SXHKD configuration file.

SXHKD is a daemon that handles keyboard shortcuts. This repository includes the SXHKD configuration file.

### Polybar
- [**config**](./polybar/config): Polybar configuration file.
- [**scripts**](./polybar/scripts/): Directory containing utility scripts for Polybar.
- [**colors.ini**](./polybar/colors.ini): File containing colors used in Polybar.
- [**fonts**](./polybar/fonts/): Directory containing fonts used in Polybar.
- [**current.ini**](./polybar/current.ini): Current bars configuration file.
- [**launch.sh**](./polybar/launch.sh): Script to launch Polybar.
- [**workspace.ini**](./polybar/workspace.ini): Workspaces configuration file.

Polybar is a status bar that can be customized through configuration files. This repository includes Polybar configuration files and utility scripts. For this setup, only the workspaces bar, some scripts, the date and time bar, and a small bar for system shutdown have been deployed.

### Kitty
- [**kitty.conf**](./kitty/kitty.conf): Kitty configuration file.
- [**color.ini**](./kitty/color.ini): File containing colors used in Kitty.

Kitty is a terminal emulator that can be customized through configuration files. This repository includes Kitty configuration files.

### Picom
- [**picom.conf**](./picom/picom.conf): Picom configuration file.

Picom is a compositor that can be customized through configuration files. In this case, it has been configured to add shadows and rounded corners to windows.

---
