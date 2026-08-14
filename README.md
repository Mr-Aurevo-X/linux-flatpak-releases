# linux-releases

Public installable binaries (Flatpak and archives) for Mr-Aurevo-X Linux apps.

This repository does **not** contain application source code. Source stays in private repos.

## Crypto Tracker

Flatpak: [org.mraurevox.CryptoTracker.flatpak](https://github.com/Mr-Aurevo-X/linux-releases/releases/download/crypto-tracker-v1.1.0/org.mraurevox.CryptoTracker.flatpak)

```bash
sudo apt install flatpak
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
curl -L -o org.mraurevox.CryptoTracker.flatpak \
  https://github.com/Mr-Aurevo-X/linux-releases/releases/download/crypto-tracker-v1.1.0/org.mraurevox.CryptoTracker.flatpak
flatpak install --user -y org.mraurevox.CryptoTracker.flatpak
flatpak run org.mraurevox.CryptoTracker
```

## Gest Linux Pro

Flatpak: [org.mraurevox.GestLinuxPro.flatpak](https://github.com/Mr-Aurevo-X/linux-releases/releases/download/Gest_Linux_Pro-v1.3.3/org.mraurevox.GestLinuxPro.flatpak)

```bash
sudo apt install flatpak
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
curl -L -o org.mraurevox.GestLinuxPro.flatpak \
  https://github.com/Mr-Aurevo-X/linux-releases/releases/download/Gest_Linux_Pro-v1.3.3/org.mraurevox.GestLinuxPro.flatpak
flatpak install --user -y org.mraurevox.GestLinuxPro.flatpak
flatpak run org.mraurevox.GestLinuxPro
```
