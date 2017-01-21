# MacBuntu-Remix
MacBuntu icon theme remix. 

## Installation
The installation procedure is pretty much the same it is for any icon theme with an `index.theme` file in its top-level directory. On any Linux distribution or Unix-like system, for that matter (so FreeBSD, NetBSD and OpenBSD are included), using GNOME, related desktops (like Cinnamon, LXDE, MATE or Xfce) or even KDE Plasma, in order to install an icon theme (any theme this one included) you merely need to move the folder containing the theme's index.theme file to `~/.local/share/icons`, if you merely want to install it for your present user account. If you want to install it and make it available for all users move this folder to `/usr/share/icons` instead (which will require root privileges so you will need to do so with either `sudo` or `su`). In the case of this theme running:

```bash
git clone https://github.com/fusion809/MacBuntu-Remix ~/.local/share/icons/MacBuntu-Remix
```

should install it for your present user, assuming git is already installed. To install it system-wide (for all users) run:

```bash
sudo git clone https://github.com/fusion809/MacBuntu-Remix /usr/share/icons/MacBuntu-Remix
```
