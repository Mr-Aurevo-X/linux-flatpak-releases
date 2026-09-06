# linux-flatpak-releases

Releases **Flatpak** publiques pour **Crypto Tracker** (pas de sources).

Canal natif (zips) : https://github.com/Mr-Aurevo-X/linux-releases

**UtilKit** et **Gest Linux Pro** : releases sur leurs dépôts publics ([UtilKit](https://github.com/Mr-Aurevo-X/UtilKit), [Gest_Linux_Pro](https://github.com/Mr-Aurevo-X/Gest_Linux_Pro)).

| App | Dernier tag | Paquet |
| --- | --- | --- |
| **Crypto Tracker** | [`crypto-tracker-v1.4.1`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/tag/crypto-tracker-v1.4.1) | `org.mraurevox.CryptoTracker.flatpak` |

## Crypto Tracker 1.4.1

```bash
curl -fL -o org.mraurevox.CryptoTracker.flatpak \
  https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/crypto-tracker-v1.4.1/org.mraurevox.CryptoTracker.flatpak
flatpak install --user -y ./org.mraurevox.CryptoTracker.flatpak
mkdir -p ~/.local/share/applications
ln -sfn ~/.local/share/flatpak/exports/share/applications/org.mraurevox.CryptoTracker.desktop \
  ~/.local/share/applications/org.mraurevox.CryptoTracker.desktop
update-desktop-database ~/.local/share/applications 2>/dev/null || true
flatpak run org.mraurevox.CryptoTracker
```

Menu Démarrer : cherche « Crypto Tracker » (relance le menu si besoin).  
Prérequis : [Flatpak](https://flatpak.org/setup/) + Flathub + runtime Freedesktop 25.08.  
Graphes matplotlib inclus. Données : `~/.local/share/crypto-tracker/`

### Mentions légales Crypto Tracker (CGU / RGPD)

- **Copyright © 2026 Mr-Aurevo-X.** Logiciel propriétaire.
- **CGU :** fourni « en l’état » ; pas un conseil en investissement ; pas de copie / redistribution sans autorisation.
- **RGPD :** aucune collecte par Mr-Aurevo-X. Fichiers locaux `~/.local/share/crypto-tracker/`. Prix : CoinGecko / Binance. MAJ GitHub (désactivable).
- Texte complet : [`LEGAL-Crypto-Tracker.md`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/blob/main/LEGAL-Crypto-Tracker.md) et [`LEGAL.md`](https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/download/crypto-tracker-v1.4.1/LEGAL.md) (joint à la release). App : Paramètres → CGU / RGPD.

© 2026 Mr-Aurevo-X. Crypto Tracker : propriétaire.
