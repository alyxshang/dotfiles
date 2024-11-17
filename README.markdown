# DOTFILES :dragon: :ribbon: :black_heart:

***My dotfiles for my custom Linux setup. :dragon: :ribbon: :black_heart:

## ABOUT :books:

This repository contains my dotfiles for my customized Linux desktop. This setup uses BSPWM as the window manager and SXHKD as the key-combination daemon.

## THE SOFTWARE :package:

These packages can be installed with `pacman`, Arch's package manager. If specified, some of these packages can be installed from the AUR with `paru` or `yay`.

### GENERAL PACKAGES

If you are just installing Arch Linux, these are the packages you will need as a bare minimum.

- Sound Tools: `alsa-utils`
- Arch Linux Base Packages: `base`
- Arch Linux Basic Build Tools: `base-devel`
- Boot Manager for UEFI Systems: `efibootmgr`
- Web Browser: `google-chrome` (AUR)
- Git: `git`
- The GRUB Bootloader: `grub`
- File System Extensions: `gvfs`
- A Light Display Manager: `lightdm`
- A Greeter for Light DM: `lightdm-gtk-greeter`
- The "Zen" variant of the Linux Kernel: `linux-zen`
- Linux Kernel Firmware: `linux-firmware`
- Text Editor: `neovim`
- Daemon for managing networking: `networkmanager`
- An AUR Helper: `paru`
- The Sound Server: `pulseaudio`
- Sudo Tool: `sudo`
- File Manager: `thunar`
- Display Server: `xorg`
- Emoji support: `noto-fonts-emoji`
- The Rust installer: `rustup`
- Compositor: `picom`
- App Launcher: `rofi`
- Terminal: `alacritty`
- Screenshot Tool: `flameshot`
- Window Manager: `bspwm`
- Hotkey Daemon: `sxhkd`
- Wallpaper Tool: `nitrogen`
- System Panel: `polybar`
- Fetch Script: `uwufetch`

## KEY COMBINATIONS :keyboard:

- Mod + Space: Open Rofi.
- Mod + P: Open Rofi in shell mode for system reboot or shutdown.
- Mod + O: Take a screenshot.
- Mod + Shift + W: Quit an application.
- Mod + Enter: Open Alacritty.
- Mod + L: Logout.
- Mod + H: Hibernate.
- Mod + 1-9: Switch workspace.

## INSTALLATION :inbox_tray:

To install this setup on your Linux installation, install the packages from the list provided above.

- 1.) Clone this repository using Git.
- 2.) Move the `config` folder to your `$HOME` folder.
- 3.) Rename the `config` folder to `.config`.
- 4.) Move the `wallpapers` folder to your `$HOME` folder.
- 5.) Make sure all files in the `.config ` folder ending in `.sh` are executable. (This is most important!)
- 6.) Move the file `.xprofile` from the `.config` folder to your `$HOME` directory.
- 7.) Start Nitrogen and add the `$HOME/wallpapers` directory as a source and set the wallpaper (`$HOME/wallpapers/01.jpg`).
- 8.) Make sure to set the image-rendering mode to "Centered" in Nitrogen when setting the wallpaper.
- 9.) Move the font file, `FiraCode-Regular.ttf`, from `fonts` directory to `/usr/local/share/fonts`. Create the `fonts` directory inside `/usr/local/share` if it does not exist.
- 10.) Move the font file `MC.ttf` from the `fonts` directory to `/usr/local/share/fonts`. Create the `fonts` directory inside `/usr/local/share` if it does not exist.
- 11.) This rice also includes my Neovim configuration.
- 13.) Start your display manager or the X11 server.
- 13.) To use my Starship prompt and neofetch in your Bash shell, add these lines to your `.bashrc` file:
```bash
neofetch
eval "$(starship init bash)"
```

## NOTE :scroll:

- *Dotfiles :dragon: :ribbon: :black_heart:*
- Licensed under the GNU GPL v3.
