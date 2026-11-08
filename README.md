# Core:Hack: Blackout

*Core:Hack 2.13.0 - Guido Cauli <guido.cauli@gmail.com>*

**English** · [Italiano](README.it.md)

![Core:Hack Blackout](img/title.jpg)

> Planet Earth, 2091. The Net belongs to whoever can afford it.

A real-time cyberpunk hacking sim. You are an independent operator with an old gateway and a terminal: you take intrusion and defence contracts, build a reputation with four factions and decide, job after job, which side you are on.

Free, with nothing behind a paywall. Linux, Windows and macOS, in Italian, English and French.

## Download

| System | Package |
|---|---|
| Windows 10/11, 64-bit | [corehack-windows-amd64.zip](../../releases/latest/download/corehack-windows-amd64.zip) |
| macOS 12+, Apple Silicon | [corehack-macos-silicon.zip](../../releases/latest/download/corehack-macos-silicon.zip) |
| Linux x86-64 | [corehack-linux-amd64.tar.gz](../../releases/latest/download/corehack-linux-amd64.tar.gz) |

[SHA256SUMS](../../releases/latest/download/SHA256SUMS) · [All releases](../../releases)

Nothing to install: extract the archive and start the game from its folder. The multiplayer server and the manuals are included.

- **Windows:** if SmartScreen appears, "More info" → "Run anyway" (the executable is not signed by a recognised authority).
- **macOS:** right-click `Sblocca-Core-Hack.command` → Open (only once), then open `Core-Hack.app`.
- **Linux:** run `./corehack` once: it adds itself to the applications menu.

## Features

**Hacking**
- Real time, while the trace climbs towards you
- A real command terminal, or windows, buttons and keyboard shortcuts
- Always-new networks: VLANs, hidden hosts, backups, monitors, portals
- Red team (intrusion, theft, sabotage, destruction, delivery) and blue team (live defence)
- Company websites to explore with WebLens: reserved areas and FTP archives

**Choices**
- Four factions that remember what you do
- A conscience on two axes, law and ethics, that decides your hat
- NetGuard surveillance: raids, fines, seizures, arrests
- A story that surfaces slowly from mail, contracts and fragments

**Progression**
- Dozens of programs in several versions, and a tech tree
- Gateways and hardware to upgrade, weekly bills to pay
- The Black Market and special programs: RevShell, KeyWraith, Devour, DarkHole
- Rival operators, investigations, and dossiers on people and companies

**Platform**
- Built-in tutorials for every part of the game
- Five visual themes: Core, Introvert, Ami, IONic, Tensor
- Multiplayer with a lightweight dedicated server

## The world

Thirty years after the Great Blackout switched off the old Internet, the Net is private property. Cables, nodes and data belong to the **Corporate Concord**. **NetGuard** polices it in the name of order. The **Lumen Collective** wants it free and public. The **Black Net** lives and trades in its margins. Your standing with each, from -100 to +100, decides which contracts you are offered, which gateways open and what your name is worth. Serving one often means betraying another.

The great cities have grown upwards, in rings: at the top, in the sun of the First Ring, power and the regime's media; in the middle, manufacturing, services and Lumen's counter-information; at the bottom the Sinks and the Pit, where the Black Net was born.

## How to play

1. **Pick** a contract on the board: client, goal, pay, risk.
2. **Get in:** scan, break the barriers, blind the monitors.
3. **Strike:** steal, delete, alter, sabotage or destroy.
4. **Vanish:** wipe the logs and disconnect before the trace reaches you.

| Intrusion | Defence |
|---|---|
| ![Intrusion](img/red.jpg) | ![Defence](img/blue.jpg) |

Start with the training contract: it is legal, authorised and risk-free. Always scan before acting, keep money aside for the bills, and wipe the logs: every trace raises NetGuard's attention.

## Multiplayer

`corehack-server` is a single program with no dependencies, which also runs on a Raspberry Pi, on a LAN or on the Internet. It keeps accounts, messages and transfers between players, and runs the competitive play: intrusions, bank audits, sieges and races. All traffic is encrypted with TLS. See the server manual.

## Minimum requirements

| | Linux | Windows | macOS |
|---|---|---|---|
| System | 64-bit, X11 or Wayland | Windows 10 or 11, 64-bit | macOS 12 Monterey or later |
| CPU | x86-64 dual core | x86-64 dual core | Apple Silicon |
| Graphics | OpenGL 3.2 (software fallback) | DirectX 11 or OpenGL 3.2 | Metal |
| RAM | 4 GB | 4 GB | 4 GB |
| Display | 1280×720 | 1280×720 | 1280×720 |
| Disk | 150 MB | 150 MB | 150 MB |

Linux system libraries:

```
# Debian / Ubuntu (Ubuntu 24.04+: libasound2t64 instead of libasound2)
sudo apt install libgl1 libglx-mesa0 libgl1-mesa-dri libx11-6 libxcursor1 libxrandr2 libxi6 libxinerama1 libxxf86vm1 libasound2
# Fedora / RHEL / Rocky / Alma
sudo dnf install mesa-libGL mesa-dri-drivers libX11 libXcursor libXrandr libXi libXinerama libXxf86vm alsa-lib
# Arch / Manjaro
sudo pacman -S mesa libglvnd libx11 libxcursor libxrandr libxi libxinerama libxxf86vm alsa-lib
```

## Manuals

PDF manuals, included in every package:

- [Player's Manual](CoreHack-Manual.pdf) (English)
- [Advanced Manual](CoreHack-Advanced-Manual.pdf) (English)
- [Manuale del giocatore](CoreHack-Manuale.pdf) (Italian)
- [Manuel du joueur](CoreHack-Manuel.pdf) (French)
- [Manuale avanzato](CoreHack-Manuale-Avanzato.pdf) (Italian)
- [Manuale del server](CoreHack-Manuale-Server.pdf) (Italian)

## What's new in 2.13.0

- WebLens, a browser for outside missions (Applications menu, `browse`): type the IP of a company's public host to see its website (home, about, contacts: the official contacts go into your Directory) or its public kiosk with the staff on duty. Every site has its own look. Find the credentials on an internal host and the reserved area opens: internal notices, the internal directory and the address of the FTP archive. New contracts on websites: take a site down, deface it, smear it, restore it.
- Credential and configuration files are read on the spot (orange + button), take no storage space and show up in the report as credentials.
- Ring cities: the great cities have grown upwards in stacked rings, from the sunlit First Ring down to the dumps of the Pit (4 to 7 rings per city). Every company lives in its ring (Directory card, whois, website), and the news now tell the life in the rings: people who are never quite their faction, and what your contracts did to the people of that ring.
- Mirror contracts: from mid-game, two factions sometimes want something from the same company. Contest: only one of them gets the file, and the one left empty-handed may ask you for a copy (the double game pays, until it is discovered). Clash: one faction pays to strike, another to defend; take a side, or read the outcome in the news.
- New contracts for Lumen (newsrooms, ransomware, slush funds, audits), NetGuard (botnets, freezes, civic jobs) and the Black Net's neighbourhood jobs (usury, clinics, blacklists, gangmasters). Lumen's optional leads are also sources: each one leaves a piece of true information. Now and then the news tell of the Black Net helping its own.
- The story: the Broker and the Black Net have more depth (new letters you can answer, his share of guilt, the back of the order, the Black Net council); the origin of the Id has been rewritten (a single key, the opening in the dead station, the proof of what really happened); the Guardians introduce themselves by the name you knew them by; story files (Cerberus parts, Fragments, the key, the Matrix) sit in a Key files block of the Storage that takes no space and cannot be deleted; letters waiting for an answer stay unread; new closings for G.C.; many consistency fixes in the story texts.
- Rival operators have real international names and grow more slowly. If you own both the Primary and the Black version of a program you choose which one to use, and operators' networks may hold Black programs and α/β variants to steal.
- Sieges: defence programs above v1 need a processor and a Cloak to match; a warning mail arrives when someone starts probing your gateway. NetGuard raids come at a random hour, announced by an anomalous-traffic alarm.
- Desktop widget: the sun and the moon move with the hour, and a radar shows who is watching your gateway and how close they are.
- Networks: targets can sit several stacked VLANs deep; `unlock` frees a host from your own cryptolocker.
- Neon icons for experimental programs and unique items; new tutorials for exploits and flaws and for WebLens.
- Music: three new radio tracks, Paper Lanterns (koto and shakuhachi), Causeway Mist (Celtic harp and low whistle) and Tidewater (electric piano and cello); the radio starts from a truly random track; a soft piano layer in Guardian Protocol; a faint murmur when text decodes.
- Interface: the Archive is its own window in the top bar, right of the Directory; the mission report reveals its lines one at a time; the contacts that lead to a secret gateway sit at the top of the Directory and can be searched by address, by words or by name; warnings about networks well above your level speak in the conditional; protocol restrictions are shown on the contract.
- Free access to a company no longer makes a day go by.

### What's new in 2.12.0

- Flaws and BreachKit: a flaw is a weakness in one type of protection (Firewall, Proxy, Password, Curve) across a whole company and stays open for a few days. You find them by scanning, reading internal tickets and following the news; BreachKit (v1-v5) exploits them to bring the protection down at once and quietly (EXPLOIT button, `exploit <host>`, x key).
- Skilled operators doctor the logs they leave: with an outdated LogParser you read a false chain, with one that's up to it the forgery shows.
- A web of acquaintances in the Directory: new Individuals category. Companies' work hosts hold contact lists (`contatti_*.vcf`): reading one brings its owner and the people they know into the Directory. From the card you move through acquaintances (Knows:) and can pay someone for another name or some information (`people`, `contact`).
- Faces: unique characters have the portrait from the website, everyone else a generated avatar; they show on the Directory card and in your mail (a silhouette for those without a face).
- ExploitForge: scans give samples of the protections, and with three samples the forge builds a flaw that lasts longer. Everything goes through the new Exploit window on the company's Directory card (`forge`).
- Exploits to order: one expert per faction, each with their own ways (the Black Net's Smith, the Concord's Vantage Labs, NetGuard's Halloran, Lumen's Prisma collective), reached through reputation or found in the contacts of notable figures; IT employees sell their own company's flaw; Black Net networks hold ready-made kits (`order`).
- False information, introduced gradually: decoy passwords, credentials prepared for whoever is listening, bait files (made-up tickets, debts and secrets that don't exist), rumours in the news and tips to verify. You defend yourself with Inspect, with a second source and with ExploitForge's Verify; traps cost trace, alert and surveillance, never the contract.
- System > Programs: owned programs are split into tabs by category, as in the Market; installing a program opens its tab.
- Contracts: the text of a delete-with-backups contract now always names the file to erase; if the real network moves the target to another host, the text follows the node too. A new automatic check compares the text of thousands of contracts with the real networks.

### What's new in 2.11.5

- Directory: searching by IP address also finds the company from addresses recorded with ping and highlights the matching host; on the card, discovered hosts are a scrolling list that no longer covers the buttons at the bottom.
- Secret gateways are easier to find: every clue names the company hiding the next one you are missing (the Archive keeps it), every clue has at least two copies per faction, and the news items that give one away come more often and give the first one missing.
- Traceroute has 5 versions (v1-v3 at the base gateway, v4-v5 at faction gateways): on operators' relay chains it starts at 50% and every version raises the chance of uncovering the next hop.
- Market: programs for sale are split into tabs by category (Red, Blue, Utility, Exploit).

### What's new in 2.11.4

- Directory: a drop-down button in the search box lists recently visited networks; picking one selects it on the map.
- Bank: in the movements list, transfers and rows that are too long open with a click, to read the whole text and the counterparty's account number.
- Bank traces follow the recipient: a movement leads to you only if the counterparty is you (nick or account number). If you put a nonexistent nickname, first name or surname, or someone else's, in the movement that leads to you, the trail is lost: the bank flags the anomaly, with no consequences for you.
- Arrested operators come back with a new nick and 2-3 levels below what they had (never below 1), instead of starting from scratch.
- KeyWraith writes only when it has something new; the sender of its mails shows the node and the network it is planted in.
- In the Dossier the insider line wraps and no longer ends up under the button.

### What's new in 2.11.3

- Exact game restore: the game keeps a history of the last 7 in-game days (a point at every new hour and after every mission, in a file next to the saves). In chsavedit, moving the day back can return the game exactly to that day and hour: money, reputation, programs, story, debts, seizures, account freezes and convictions that came later disappear. From the terminal: `chsavedit hist N` and `chsavedit restore N day [hour]`.
- A free access left open when the game ended no longer disables the Directory's «Host access» button; affected saves fix themselves on load, and when the button is off a tooltip explains why.
- chsavedit, when moving days back in saves without history, reopens a closed game and removes account freezes triggered after the new day.

### What's new in 2.11.2

- New neon icons for every program and for host protections, in family colours: red for Red, light blue for Blue, light grey for utilities, light violet for exploits; Primaries white and Blacks dark violet. They appear in the Market, in the gateway's programs and on the network map.
- The in-mission action icons were redrawn in the same style; buttons with a keyboard shortcut show the key in a small square.
- The game pauses by itself when its window loses focus.
- The violet blinding bar is now visible on the selected node too, and below 20% it pulses clearly.
- Notifications stay 10 seconds; a click closes them with a fade-out.
- Devour no longer leaves logs: the destroyed host takes them with it.
- Deleted files appear in the list only with Inspect and a FileUndeleter able to recover them.
- In the Archive, the intel gathered on the factions is called «Information on…».

### What's new in 2.11.1

- Outside missions, yellow and red log lines appear as notifications at the top right when the Events window is closed: they fade in and vanish after 6 seconds.

### What's new in 2.11.0

- Cerberus, the Shards and ION are now one story: in chapter 4 of every arc you keep the original part of Cerberus and hand over a copy.
- After the alliances lock come the Recovery, the Attack and a new secret mission in Orfeo's footsteps; the faction AIs show up later, one at a time.
- A copy sold in the Shadow can end up in the rival faction's defences.
- A violet bar under the node shows how much IDS blinding is left.
- On the board two icons replace the RED and BLUE labels.

**2.10.2:** contract icons; English manuals; a robbed holder notices within 24 hours; bills and deadlines between 2 and 6 in the morning.

**2.10.1:** new *Operators and investigations* and *Dossiers and people* tutorials; Devour and DarkHole corrode the host in glitches until it vanishes; arrested operators come back under a new name.

**2.10.0:** unknown-host and delivery contracts; Devour and DarkHole destroy a host for good; new destruction contracts.

## Support the project

Core:Hack is one person's work, in their spare time. If you enjoy it: [Ko-fi](https://ko-fi.com/guidocauli) · [PayPal](https://paypal.me/guidocauli).

---

Core:Hack: Blackout - Guido Cauli <guido.cauli@gmail.com>
