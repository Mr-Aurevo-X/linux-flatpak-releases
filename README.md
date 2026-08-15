# linux-flatpak-releases

Releases **Flatpak** publiques pour **toutes** les apps Linux Mr-Aurevo-X (pas de sources).  
Apps actuelles : **Crypto Tracker** + **Gest Linux Pro** + **MrAurevoX Kit** (ne pas retirer une app de ce README).

Canal natif (zips / tar.gz) : https://github.com/Mr-Aurevo-X/linux-releases

| App | Dernier tag | Paquet |
| --- | --- | --- |
| **Crypto Tracker** | [`crypto-tracker-v1.2.12`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/tag/crypto-tracker-v1.2.12) | `org.mraurevox.CryptoTracker.flatpak` |
| **Gest Linux Pro** | [`Gest_Linux_Pro-v1.4.9`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/tag/Gest_Linux_Pro-v1.4.9) | `org.mraurevox.GestLinuxPro.flatpak` |
| **MrAurevoX Kit** | [`MrAurevoX-Kit-v0.2.6`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/tag/MrAurevoX-Kit-v0.2.6) | `org.mraurevox.MrAurevoXKit.flatpak` |

## Crypto Tracker 1.2.12

```bash
curl -fL -o org.mraurevox.CryptoTracker.flatpak \
  https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/crypto-tracker-v1.2.12/org.mraurevox.CryptoTracker.flatpak
flatpak install --user -y ./org.mraurevox.CryptoTracker.flatpak
flatpak run org.mraurevox.CryptoTracker
```

Prérequis : [Flatpak](https://flatpak.org/setup/) + Flathub + runtime Freedesktop 25.08.  
Graphes matplotlib inclus. Données : `~/.local/share/crypto-tracker/`

### Mentions légales Crypto Tracker (CGU / RGPD)

- **Copyright © 2026 Mr-Aurevo-X.** Logiciel propriétaire.
- **CGU :** fourni « en l’état » ; pas un conseil en investissement ; pas de copie / redistribution sans autorisation.
- **RGPD :** aucune collecte par Mr-Aurevo-X. Fichiers locaux `~/.local/share/crypto-tracker/`. Prix : CoinGecko / Binance. MAJ GitHub (désactivable).
- Texte complet : [`LEGAL-Crypto-Tracker.md`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/blob/main/LEGAL-Crypto-Tracker.md) et [`LEGAL.md`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/crypto-tracker-v1.2.12/LEGAL.md) (joint à la release). App : Paramètres → CGU / RGPD.

## Gest Linux Pro 1.4.9

**© 2026 Mr-Aurevo-X** · GPL-3.0-or-later · 100 % local (sauf vérif MAJ GitHub, désactivable)

```bash
curl -fL -o org.mraurevox.GestLinuxPro.flatpak \
  https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/Gest_Linux_Pro-v1.4.9/org.mraurevox.GestLinuxPro.flatpak
flatpak install --user -y ./org.mraurevox.GestLinuxPro.flatpak
flatpak run org.mraurevox.GestLinuxPro
```

Prérequis : Flatpak + Flathub + runtime `org.gnome.Platform//49`.

### Mentions légales Gest Linux Pro (CGU / RGPD)

- **Copyright © 2026 Mr-Aurevo-X.** Code sous GPL-3.0-or-later.
- **CGU :** logiciel « en l’état » ; vous êtes responsable des actions système (pkexec, services, pare-feu, clichés, paquets). Redistribution sous GPL.
- **RGPD :** aucune collecte par Mr-Aurevo-X. Fichiers locaux `~/.config/gest-linux-pro/`, `~/.local/share/gest-linux-pro/`. MAJ GitHub désactivable.
- Texte complet : [`LEGAL-Gest-Linux-Pro.md`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/blob/main/LEGAL-Gest-Linux-Pro.md).

## MrAurevoX Kit 0.2.6

**© 2026 Mr-Aurevo-X** · GPL-3.0-or-later · 100 % local (sauf vérif MAJ GitHub, désactivable)

```bash
curl -fL -o org.mraurevox.MrAurevoXKit.flatpak \
  https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/MrAurevoX-Kit-v0.2.6/org.mraurevox.MrAurevoXKit.flatpak
flatpak install --user -y ./org.mraurevox.MrAurevoXKit.flatpak
flatpak run org.mraurevox.MrAurevoXKit
```

Prérequis : Flatpak + Flathub + runtime `org.gnome.Platform//49`.  
Recherche, pipette, hash, images/EXIF, PDF, atelier.  
Données : `~/.config/mraurevox-kit/`, `~/.local/share/mraurevox-kit/`.

### Mentions légales MrAurevoX Kit (CGU / RGPD)

- **Copyright © 2026 Mr-Aurevo-X.** Code sous GPL-3.0-or-later.
- **CGU :** logiciel « en l’état » ; vous êtes responsable des fichiers que vous renommez, redimensionnez ou ouvrez. Redistribution sous GPL.
- **RGPD :** aucune collecte par Mr-Aurevo-X. Pas de télémétrie. MAJ GitHub désactivable.
- Texte complet : [`LEGAL-MrAurevoX-Kit.md`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/blob/main/LEGAL-MrAurevoX-Kit.md).

© 2026 Mr-Aurevo-X. Crypto Tracker : propriétaire. Gest Linux Pro et MrAurevoX Kit : GPL-3.0-or-later.
