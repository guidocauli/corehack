# Core:Hack: Blackout

*Core:Hack 3.0.0 - Guido Cauli <guido.cauli@gmail.com>*

**IT** · La prima beta pubblica. Simulazione di hacking cyberpunk in tempo reale. Pianeta Terra, 2091: un vecchio gateway, un terminale, quattro fazioni. Scegli i contratti, e da che parte stare.

**EN** · The first public beta. A real-time cyberpunk hacking sim. Planet Earth, 2091: an old gateway, a terminal, four factions. Pick your contracts, and pick your side.

## Download

| Sistema / System | File |
|---|---|
| Windows 10/11 (64 bit) | [corehack-windows-amd64.zip](../../releases/latest/download/corehack-windows-amd64.zip) |
| macOS 12+ (Apple Silicon) | [corehack-macos-silicon.zip](../../releases/latest/download/corehack-macos-silicon.zip) |
| Linux x86-64 | [corehack-linux-amd64.tar.gz](../../releases/latest/download/corehack-linux-amd64.tar.gz) |
| Android 7+ (64 bit) | [corehack-android.apk](../../releases/latest/download/corehack-android.apk) |

[SHA256SUMS](../../releases/latest/download/SHA256SUMS) · [Tutte le versioni / All releases](../../releases)

Nessuna installazione: estrai l'archivio e avvia il gioco dalla cartella. Server multigiocatore e manuali sono inclusi.
Nothing to install: extract the archive and start the game from its folder. Multiplayer server and manuals included.

- **Windows:** SmartScreen → "Ulteriori informazioni / More info" → "Esegui comunque / Run anyway".
- **macOS:** tasto destro / right-click `Sblocca-Core-Hack.command` → Apri / Open, poi / then `Core-Hack.app`.
- **Linux:** `./corehack` (la prima volta aggiunge la voce al menu / adds itself to the menu on first run).
- **Android:** apri l'APK sul telefono e consenti l'installazione / open the APK on your phone and allow the install.

## Novità 3.0.0 / What's new in 3.0.0

- **IT:** Next è l'interfaccia predefinita: nodi esagonali con l'anello delle azioni intorno, registro e terminale sempre aperti accanto alla mappa, contratti a schede, icone del desktop che si spostano, salvataggio veloce nella barra in alto e un widget del cielo con il meteo. Intrusioni, difesa e assedi hanno tutti la loro versione Next; la Classica c'è ancora (Opzioni, Interfaccia).
- **EN:** Next is the default interface: hexagonal nodes with a ring of actions around them, the log and the terminal always open beside the map, contracts shown as cards, desktop icons you can move, a quick save in the top bar and a sky widget with the weather. Intrusions, defence and sieges all have their Next version; Classic is still there (Options, Interface).
- **IT:** Android: Core:Hack gira su telefoni e tablet (Android 7 o successivo, 64 bit) con un'interfaccia a sfioramento tutta sua: testi e comandi più grandi, finestre a tutto schermo, niente terminale.
- **EN:** Android: Core:Hack runs on phones and tablets (Android 7 or later, 64-bit) with a touch interface of its own: bigger text and controls, full-screen windows, no terminal.
- **IT:** Coreano: tutto il gioco è tradotto, con CoreHack Mono CJK, un carattere disegnato apposta, e rune proprie per l'alfabeto delle IA.
- **EN:** Korean: the whole game is translated, with CoreHack Mono CJK, a typeface drawn for it, and runes of their own for the AIs' alphabet.
- **IT:** MultiEmu: una console retrò dentro il gioco, con dodici cartucce da trovare, record, gamepad e due giocatori sulla stessa tastiera.
- **EN:** MultiEmu: a retro console inside the game, with twelve cartridges to find, high scores, gamepad support and two players on the same keyboard.
- **IT:** Workbench (si sblocca con BreachKit v2, `wbench`): programmi custom compilati dagli snippet, dai moduli e dalle ricette che trovi nelle reti.
- **EN:** Workbench (unlocked by BreachKit v2, `wbench`): custom programs compiled from the snippets, modules and recipes you find in the networks.
- **IT:** Il diario: la voce del protagonista, una linguetta dell'Archivio, scritta nelle svolte della storia.
- **EN:** The diary: the protagonist's own voice, a tab in the Archive, written at the turning points of the story.
- **IT:** L'ultimo capitolo è cresciuto: duelli logici contro le IA, Restore per ricostruire ciò che è stato cancellato, un nuovo epilogo e un arco che resta aperto dopo la fine.
- **EN:** The last chapter has grown: logic duels against the AIs, Restore to rebuild what was erased, a new epilogue and an arc that stays open after the end.
- **IT:** Molte correzioni e ritocchi di bilanciamento. Manuali rifatti con l'interfaccia Next; i manuali ora raccontano invece di spiegare, senza spoiler.
- **EN:** Many fixes and balance changes. Manuals redone with the Next interface; the manuals now tell rather than explain, free of spoilers.

## Requisiti minimi / Minimum requirements

| | |
|---|---|
| CPU | 64 bit dual core |
| RAM | 4 GB |
| GPU | DirectX 11 · Metal · OpenGL 3.2 |
| Schermo / Display | 1280×720 |
| Disco / Disk | 150 MB |
| Android | 7.0+, arm64 |

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
