# linux-flatpak-releases

Releases **Flatpak** publiques pour les apps Linux Mr-Aurevo-X (pas de sources).

## Gest Linux Pro

```bash
curl -fL -o org.mraurevox.GestLinuxPro.flatpak \
  https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/Gest_Linux_Pro-v1.3.4/org.mraurevox.GestLinuxPro.flatpak
flatpak install --user -y ./org.mraurevox.GestLinuxPro.flatpak
flatpak run org.mraurevox.GestLinuxPro
```

Prérequis : Flatpak + Flathub + runtime `org.gnome.Platform//49`.

Canal natif (`tar.gz` / `.deb`) : https://github.com/Mr-Aurevo-X/linux-releases
