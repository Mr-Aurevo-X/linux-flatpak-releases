# linux-flatpak-releases

Releases **Flatpak** publiques pour les apps Linux Mr-Aurevo-X (pas de sources).

Canal natif (zips / tar.gz) : https://github.com/Mr-Aurevo-X/linux-releases

| App | Dernier tag | Paquet |
| --- | --- | --- |
| **Crypto Tracker** | [`crypto-tracker-v1.1.8`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/tag/crypto-tracker-v1.1.8) | `org.mraurevox.CryptoTracker.flatpak` |
| **Gest Linux Pro** | [`Gest_Linux_Pro-v1.4.1`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/tag/Gest_Linux_Pro-v1.4.1) | `org.mraurevox.GestLinuxPro.flatpak` |

## Crypto Tracker 1.1.8

```bash
curl -fL -o org.mraurevox.CryptoTracker.flatpak \
  https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/crypto-tracker-v1.1.8/org.mraurevox.CryptoTracker.flatpak
flatpak install --user -y ./org.mraurevox.CryptoTracker.flatpak
flatpak run org.mraurevox.CryptoTracker
```

Prérequis : [Flatpak](https://flatpak.org/setup/) + Flathub + runtime Freedesktop 25.08.  
Données : `~/.local/share/crypto-tracker/`

## Gest Linux Pro 1.4.1

```bash
curl -fL -o org.mraurevox.GestLinuxPro.flatpak \
  https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/Gest_Linux_Pro-v1.4.1/org.mraurevox.GestLinuxPro.flatpak
flatpak install --user -y ./org.mraurevox.GestLinuxPro.flatpak
flatpak run org.mraurevox.GestLinuxPro
```

Prérequis : Flatpak + Flathub + runtime `org.gnome.Platform//49`.
