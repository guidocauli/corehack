# Core:Hack: Blackout

*Core:Hack 2.13.0 - Guido Cauli <guido.cauli@gmail.com>*

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

## Novità 2.13.0 / What's new in 2.13.0

- **IT:** WebLens, un browser da usare fuori missione (menu Applicazioni, `browse`): dato l'IP di un host pubblico di un'azienda ne mostra il sito (home, chi siamo, contatti: i referenti ufficiali vanno in Rubrica) o il terminale informativo con il personale in servizio. Ogni sito ha il suo aspetto. Trovate le credenziali su un host interno si apre l'area riservata: avvisi interni, rubrica interna e indirizzo dell'archivio FTP. Nuovi contratti sui siti: buttarlo giù, sfregiarlo, screditarlo, ripristinarlo.
- **EN:** WebLens, a browser for outside missions (Applications menu, `browse`): type the IP of a company's public host to see its website (home, about, contacts: the official contacts go into your Directory) or its public kiosk with the staff on duty. Every site has its own look. Find the credentials on an internal host and the reserved area opens: internal notices, the internal directory and the address of the FTP archive. New contracts on websites: take a site down, deface it, smear it, restore it.
- **IT:** I file di credenziali e configurazione si leggono sul posto (pulsante + arancione), non occupano spazio e nel rapporto risultano come credenziali.
- **EN:** Credential and configuration files are read on the spot (orange + button), take no storage space and show up in the report as credentials.
- **IT:** Città ad anelli: le grandi città sono cresciute in verticale, ad anelli sovrapposti, dal Primo Anello al sole fino alle discariche della Fossa (da 4 a 7 anelli per città). Ogni azienda sta nel suo anello (scheda in Rubrica, whois, sito) e le notizie raccontano la vita negli anelli: persone che non sono mai del tutto la loro fazione, e che cosa hanno fatto i tuoi contratti alla gente di quell'anello.
- **EN:** Ring cities: the great cities have grown upwards in stacked rings, from the sunlit First Ring down to the dumps of the Pit (4 to 7 rings per city). Every company lives in its ring (Directory card, whois, website), and the news now tell the life in the rings: people who are never quite their faction, and what your contracts did to the people of that ring.
- **IT:** Contratti speculari: da metà gioco capita che due fazioni vogliano qualcosa dalla stessa azienda. Contesa: il file lo ha uno solo, e chi resta a mani vuote può chiederti una copia (il doppio gioco paga, finché non ti scoprono). Scontro: una fazione paga per colpire, un'altra per difendere; scegli da che parte stare, o leggi com'è finita nelle notizie.
- **EN:** Mirror contracts: from mid-game, two factions sometimes want something from the same company. Contest: only one of them gets the file, and the one left empty-handed may ask you for a copy (the double game pays, until it is discovered). Clash: one faction pays to strike, another to defend; take a side, or read the outcome in the news.
- **IT:** Nuovi contratti per Lumen (redazioni, ransomware, fondi neri, audit), NetGuard (botnet, congelamenti, lavori civici) e per i quartieri della Rete Nera (usura, ambulatori, liste nere, caporali). Le piste facoltative di Lumen sono anche fonti: ognuna lascia un'informazione vera. Ogni tanto le notizie raccontano la Rete Nera che aiuta i suoi.
- **EN:** New contracts for Lumen (newsrooms, ransomware, slush funds, audits), NetGuard (botnets, freezes, civic jobs) and the Black Net's neighbourhood jobs (usury, clinics, blacklists, gangmasters). Lumen's optional leads are also sources: each one leaves a piece of true information. Now and then the news tell of the Black Net helping its own.
- **IT:** La trama: il Broker e la Rete Nera hanno più profondità (nuove lettere a cui rispondere, la sua parte di colpa, il retro dell'ordine, il consiglio della Rete Nera); l'origine dell'Id è stata riscritta (una chiave sola, l'apertura nella stazione morta, le prove di com'è andata davvero); i Guardiani si presentano dicendo come li conoscevi; i file di trama (parti di Cerbero, Frammenti, chiave, Matrice) stanno nel blocco File chiave dello Storage, non occupano spazio e non si cancellano; le lettere che aspettano una risposta restano non lette; nuove chiusure per G.C.; molte correzioni di coerenza nei testi della trama.
- **EN:** The story: the Broker and the Black Net have more depth (new letters you can answer, his share of guilt, the back of the order, the Black Net council); the origin of the Id has been rewritten (a single key, the opening in the dead station, the proof of what really happened); the Guardians introduce themselves by the name you knew them by; story files (Cerberus parts, Fragments, the key, the Matrix) sit in a Key files block of the Storage that takes no space and cannot be deleted; letters waiting for an answer stay unread; new closings for G.C.; many consistency fixes in the story texts.
- **IT:** Gli operatori rivali hanno nomi reali internazionali e crescono più piano. Se possiedi la versione Primaria e quella Nera di un programma scegli quale usare, e nelle reti degli operatori si possono rubare programmi Neri e varianti α/β.
- **EN:** Rival operators have real international names and grow more slowly. If you own both the Primary and the Black version of a program you choose which one to use, and operators' networks may hold Black programs and α/β variants to steal.
- **IT:** Assedi: i programmi di difesa oltre la v1 chiedono processore e Cloak all'altezza; una mail avvisa quando qualcuno comincia a sondare il gateway. Le perquisizioni di NetGuard arrivano a un'ora qualsiasi, annunciate da un allarme di traffico anomalo.
- **EN:** Sieges: defence programs above v1 need a processor and a Cloak to match; a warning mail arrives when someone starts probing your gateway. NetGuard raids come at a random hour, announced by an anomalous-traffic alarm.
- **IT:** Widget del desktop: il sole e la luna seguono l'ora, e un radar mostra chi tiene d'occhio il tuo gateway e quanto è vicino.
- **EN:** Desktop widget: the sun and the moon move with the hour, and a radar shows who is watching your gateway and how close they are.
- **IT:** Reti: i bersagli possono stare in più VLAN sovrapposte; `unlock` libera un host dal tuo stesso cryptolocker.
- **EN:** Networks: targets can sit several stacked VLANs deep; `unlock` frees a host from your own cryptolocker.
- **IT:** Icone al neon per i programmi sperimentali e gli oggetti unici; nuovi tutorial su exploit e falle e su WebLens.
- **EN:** Neon icons for experimental programs and unique items; new tutorials for exploits and flaws and for WebLens.
- **IT:** Musica: tre nuovi brani per la radio, Paper Lanterns (koto e shakuhachi), Causeway Mist (arpa celtica e low whistle) e Tidewater (piano elettrico e violoncello); la radio parte da un brano davvero a caso; uno strato leggero di pianoforte in Guardian Protocol; un brusio appena udibile quando un testo si decifra.
- **EN:** Music: three new radio tracks, Paper Lanterns (koto and shakuhachi), Causeway Mist (Celtic harp and low whistle) and Tidewater (electric piano and cello); the radio starts from a truly random track; a soft piano layer in Guardian Protocol; a faint murmur when text decodes.
- **IT:** Interfaccia: l'Archivio è una finestra a sé nella barra in alto, a destra della Rubrica; il rapporto di missione mostra le righe una alla volta; i contatti che portano a un gateway segreto stanno in cima alla Rubrica e si cercano per indirizzo, per parole o per nome; gli avvisi sulle reti molto sopra il tuo livello parlano al condizionale; le restrizioni di protocollo compaiono sul contratto.
- **EN:** Interface: the Archive is its own window in the top bar, right of the Directory; the mission report reveals its lines one at a time; the contacts that lead to a secret gateway sit at the top of the Directory and can be searched by address, by words or by name; warnings about networks well above your level speak in the conditional; protocol restrictions are shown on the contract.
- **IT:** L'accesso libero a un'azienda non fa più passare un giorno.
- **EN:** Free access to a company no longer makes a day go by.
- **IT:** Documentazione: nuovo manuale avanzato in francese; i manuali parlano di città ad anelli, contratti speculari, WebLens e file chiave.
- **EN:** Documentation: new French advanced manual; the manuals cover the ring cities, mirror contracts, WebLens and key files.

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
