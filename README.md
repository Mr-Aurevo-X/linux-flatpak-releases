# linux-releases

Public installable binaries (Flatpak and archives) for Mr-Aurevo-X Linux apps.

This repository does **not** contain application source code.

## Gest Linux Pro

Flatpak: [org.mraurevox.GestLinuxPro.flatpak](https://github.com/Mr-Aurevo-X/linux-releases/releases/download/Gest_Linux_Pro-v1.3.0/org.mraurevox.GestLinuxPro.flatpak)

Install on Linux Mint / Ubuntu:

```bash
sudo apt install flatpak
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak install --user ./org.mraurevox.GestLinuxPro.flatpak
flatpak run org.mraurevox.GestLinuxPro
```
