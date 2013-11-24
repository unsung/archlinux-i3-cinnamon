archlinux-awesome-cinnamon
=======================

PKGBUILDs for Cinnamon 2.0 Integration with Awesome for ArchLinux

Instructions: Place
- awesome-cinnamon.desktop in /usr/share/xsessions/
- awesome.desktop in /usr/share/applications/
- awesome.session in /usr/share/cinnamon-session/sessions/

Known Issues:
- Provides awesome.desktop, which is also provided by the awesome-gnome package from https://github.com/nekolover/archlinux-awesome-gnome
- Requires the package notification-daemon, where the awesome-gnome package does not require it (this is for the awesome.session file).
