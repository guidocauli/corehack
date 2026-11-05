# Core:Hack: Blackout

*Core:Hack 2.10.2 - Guido Cauli <guido.cauli@gmail.com>*

**IT** · Simulazione di hacking cyberpunk in tempo reale. Pianeta Terra, 2091: un vecchio gateway, un terminale, quattro fazioni. Scegli i contratti, e da che parte stare.

**EN** · A real-time cyberpunk hacking sim. Planet Earth, 2091: an old gateway, a terminal, four factions. Pick your contracts, and pick your side.

## Download

| Sistema / System | File |
|---|---|
| Windows 10/11 (64 bit) | [corehack-windows-amd64.zip](../../releases/latest/download/corehack-windows-amd64.zip) |
| macOS 12+ (Apple Silicon) | [corehack-macos-silicon.zip](../../releases/latest/download/corehack-macos-silicon.zip) |
| Linux x86-64 | [corehack-linux-amd64.tar.gz](../../releases/latest/download/corehack-linux-amd64.tar.gz) |

[SHA256SUMS](../../releases/latest/download/SHA256SUMS) · [Tutte le versioni / All releases](../../releases)

Nessuna installazione: estrai l'archivio e avvia il gioco dalla cartella. Server multigiocatore e manuali sono inclusi.
Nothing to install: extract the archive and start the game from its folder. Multiplayer server and manuals included.

- **Windows:** SmartScreen → "Ulteriori informazioni / More info" → "Esegui comunque / Run anyway".
- **macOS:** tasto destro / right-click `Sblocca-Core-Hack.command` → Apri / Open, poi / then `Core-Hack.app`.
- **Linux:** `./corehack` (la prima volta aggiunge la voce al menu / adds itself to the menu on first run).

## Novità 2.10.2 / What's new in 2.10.2

- **IT:** la sorveglianza NetGuard presa con un contratto non si perde più nei giorni del lavoro; il resoconto mostra l'aumento reale.
- **EN:** NetGuard surveillance earned on a contract is no longer lost over the days it takes; the report shows the actual increase.
- **IT:** ogni contratto ha un'icona per il tipo di lavoro, in bacheca, nei dettagli e nel rapporto; manuale del giocatore e manuale avanzato anche in inglese.
- **EN:** every contract has an icon for the kind of job, on the board, in the details and in the report; player's and advanced manuals now in English too.

Dalla 2.10.1 / Since 2.10.1: tutorial *Operatori e indagini* e *Fascicoli e persone* / new *Operators and investigations* and *Dossiers and people* tutorials; corrosione animata di Devour e DarkHole / animated Devour and DarkHole corrosion; operatori arrestati con un nome nuovo / arrested operators return under a new name.

## Requisiti minimi / Minimum requirements

| | |
|---|---|
| CPU | 64 bit dual core |
| RAM | 4 GB |
| GPU | DirectX 11 · Metal · OpenGL 3.2 |
| Schermo / Display | 1280×720 |
| Disco / Disk | 150 MB |

Linux, librerie di sistema / system libraries:

```
# Debian / Ubuntu (Ubuntu 24.04+: libasound2t64)
sudo apt install libgl1 libglx-mesa0 libgl1-mesa-dri libx11-6 libxcursor1 libxrandr2 libxi6 libxinerama1 libxxf86vm1 libasound2
# Fedora / RHEL
sudo dnf install mesa-libGL mesa-dri-drivers libX11 libXcursor libXrandr libXi libXinerama libXxf86vm alsa-lib
# Arch
sudo pacman -S mesa libglvnd libx11 libxcursor libxrandr libxi libxinerama libxxf86vm alsa-lib
```

## Sostieni / Support

[Ko-fi](https://ko-fi.com/guidocauli) · [PayPal](https://paypal.me/guidocauli)
