# linux-flatpak-releases

Releases **Flatpak** publiques pour **toutes** les apps Linux Mr-Aurevo-X (pas de sources).  
Apps actuelles : **Crypto Tracker** + **Gest Linux Pro** (ne pas retirer une app de ce README).

Canal natif (zips / tar.gz) : https://github.com/Mr-Aurevo-X/linux-releases

| App | Dernier tag | Paquet |
| --- | --- | --- |
| **Crypto Tracker** | [`crypto-tracker-v1.2.5`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/tag/crypto-tracker-v1.2.5) | `org.mraurevox.CryptoTracker.flatpak` |
| **Gest Linux Pro** | [`Gest_Linux_Pro-v1.4.5`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/tag/Gest_Linux_Pro-v1.4.5) | `org.mraurevox.GestLinuxPro.flatpak` |

## Crypto Tracker 1.2.5

```bash
curl -fL -o org.mraurevox.CryptoTracker.flatpak \
  https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/crypto-tracker-v1.2.5/org.mraurevox.CryptoTracker.flatpak
flatpak install --user -y ./org.mraurevox.CryptoTracker.flatpak
flatpak run org.mraurevox.CryptoTracker
```

Prérequis : [Flatpak](https://flatpak.org/setup/) + Flathub + runtime Freedesktop 25.08.  
Données : `~/.local/share/crypto-tracker/`

## Gest Linux Pro 1.4.5

**© 2026 Mr-Aurevo-X** · GPL-3.0-or-later · 100 % local (sauf vérif MAJ GitHub, désactivable)

```bash
curl -fL -o org.mraurevox.GestLinuxPro.flatpak \
  https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/Gest_Linux_Pro-v1.4.5/org.mraurevox.GestLinuxPro.flatpak
flatpak install --user -y ./org.mraurevox.GestLinuxPro.flatpak
flatpak run org.mraurevox.GestLinuxPro
```

Prérequis : Flatpak + Flathub + runtime `org.gnome.Platform//49`.

### Mentions légales (CGU / RGPD)

- **Copyright © 2026 Mr-Aurevo-X.** Code sous GPL-3.0-or-later.
- **CGU :** logiciel « en l’état » ; vous êtes responsable des actions système (pkexec, services, pare-feu, clichés, paquets). Redistribution sous GPL.
- **RGPD :** Mr-Aurevo-X ne collecte aucune donnée personnelle. Pas de compte, pas de télémétrie. Fichiers locaux uniquement (`~/.config/gest-linux-pro/`, `~/.local/share/gest-linux-pro/`). Si les MAJ sont activées, GitHub peut voir IP / User-Agent. Désactivable dans l’app.
- Texte complet : [`LEGAL-Gest-Linux-Pro.md`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/blob/main/LEGAL-Gest-Linux-Pro.md) et [`LEGAL.md`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/Gest_Linux_Pro-v1.4.5/LEGAL.md) (joint à la release). Aussi dans l’app : Préférences → Mentions légales.

© 2026 Mr-Aurevo-X. Crypto Tracker et Gest Linux Pro : licences de chaque projet.
