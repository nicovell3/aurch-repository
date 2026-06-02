# aurch-repository
Arch repository for AUR packages

This repository is meant to avoid creating packages from AUR everytime I want to upgrade. Packages are pre-built and ready to be installed in any ArchLinux x86_64 machine.

To use this repository, just add this to your `/etc/pacman.conf`:

```
[aurch]
SigLevel = Optional TrustAll
Server = https://github.com/nicovell3/aurch-repository/releases/download/repository
```

Current list of included packages:

- google-chrome
- visual-studio-code-bin
- yay-bin
- python312
- megasync-bin
- opera
- synology-drive
- unityhub
- flutter-bin
- unionfs-fuse

If you want a different set of packages, just setup your own repository. It's free.

You can check the packages you have installed from AUR with `pacman -Qm`.
