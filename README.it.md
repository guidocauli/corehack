# Core:Hack: Blackout

*Core:Hack 2.13.0 - Guido Cauli <guido.cauli@gmail.com>*

[English](README.md) · **Italiano**

![Core:Hack Blackout](img/title.jpg)

> Pianeta Terra, 2091. La Rete è di chi può permettersela.

Una simulazione di hacking cyberpunk in tempo reale. Sei un operatore indipendente con un vecchio gateway e un terminale: accetti contratti di intrusione e di difesa, costruisci una reputazione presso quattro fazioni e decidi, lavoro dopo lavoro, da che parte stare.

Gratuito, senza contenuti a pagamento. Linux, Windows e macOS, in italiano, inglese e francese.

## Download

| Sistema | Pacchetto |
|---|---|
| Windows 10/11, 64 bit | [corehack-windows-amd64.zip](../../releases/latest/download/corehack-windows-amd64.zip) |
| macOS 12+, Apple Silicon | [corehack-macos-silicon.zip](../../releases/latest/download/corehack-macos-silicon.zip) |
| Linux x86-64 | [corehack-linux-amd64.tar.gz](../../releases/latest/download/corehack-linux-amd64.tar.gz) |

[SHA256SUMS](../../releases/latest/download/SHA256SUMS) · [Tutte le versioni](../../releases)

Non si installa: estrai l'archivio e avvia il gioco dalla cartella. Server multigiocatore e manuali sono inclusi.

- **Windows:** se compare SmartScreen, "Ulteriori informazioni" → "Esegui comunque" (l'eseguibile non è firmato da un'autorità riconosciuta).
- **macOS:** tasto destro su `Sblocca-Core-Hack.command` → Apri (una volta sola), poi apri `Core-Hack.app`.
- **Linux:** avvia `./corehack` una volta: aggiunge da solo la voce nel menu delle applicazioni.

## Caratteristiche

**Hacking**
- In tempo reale, mentre il trace sale verso di te
- Terminale con comandi veri, oppure finestre, pulsanti e scorciatoie
- Reti sempre nuove: VLAN, host nascosti, backup, monitor, portali
- Red team (intrusione, furto, sabotaggio, distruzione, consegna) e blue team (difesa in diretta)
- I siti delle aziende da esplorare con WebLens: aree riservate e archivi FTP

**Scelte**
- Quattro fazioni che ricordano quello che fai
- Una coscienza su due assi, legalità ed etica, che decide il tuo cappello
- La sorveglianza di NetGuard: perquisizioni, multe, sequestri, arresti
- Una trama che emerge piano da email, contratti e frammenti

**Progressione**
- Decine di programmi a più livelli e un albero tecnologico
- Gateway e hardware da migliorare, bollette settimanali da pagare
- Il Mercato Nero e i programmi speciali: RevShell, KeyWraith, Devour, DarkHole
- Operatori rivali, indagini e fascicoli su persone e aziende

**Piattaforma**
- Tutorial integrati per ogni parte del gioco
- Cinque temi grafici: Core, Introvert, Ami, IONic, Tensor
- Multigiocatore con un server dedicato leggero

## Il mondo

Trent'anni dopo il Grande Blackout che spense la vecchia Internet, la Rete è un bene privato. Cavi, nodi e dati appartengono al **Concordato Aziendale**. **NetGuard** la sorveglia in nome dell'ordine. Il **Collettivo Lumen** la vuole libera e pubblica. La **Rete Nera** ci vive ai margini e ci fa affari. La reputazione con ciascuna fazione, da -100 a +100, decide quali contratti ti vengono offerti, quali gateway si aprono e quanto vale il tuo nome. Servirne una spesso significa tradirne un'altra.

Le grandi città sono cresciute in verticale, ad anelli: in alto, al sole del Primo Anello, il potere e i media di regime; in mezzo la manifattura, i servizi e la controinformazione di Lumen; in fondo i Bassifondi e la Fossa, dove è nata la Rete Nera.

## Come si gioca

1. **Scegli** un contratto in bacheca: cliente, obiettivo, compenso, rischio.
2. **Entra:** scansiona, abbatti le barriere, acceca i monitor.
3. **Colpisci:** ruba, cancella, altera, sabota o distruggi.
4. **Sparisci:** cancella i log e disconnettiti prima che il trace arrivi a te.

| Intrusione | Difesa |
|---|---|
| ![Intrusione](img/red.jpg) | ![Difesa](img/blue.jpg) |

Comincia dal contratto di addestramento: è legale, autorizzato e senza rischi. Scansiona sempre prima di agire, tieni da parte i soldi per le bollette e cancella i log: ogni traccia fa crescere l'attenzione di NetGuard.

## Multigiocatore

`corehack-server` è un unico programma senza dipendenze, che gira anche su un Raspberry Pi, in LAN o in Internet. Tiene account, messaggi e bonifici tra giocatori e gestisce le sfide: intrusioni, audit delle banche, assedi e gare. Tutto il traffico è cifrato con TLS. Vedi il manuale del server.

## Requisiti minimi

| | Linux | Windows | macOS |
|---|---|---|---|
| Sistema | 64 bit, X11 o Wayland | Windows 10 o 11, 64 bit | macOS 12 Monterey o successivo |
| Processore | x86-64 dual core | x86-64 dual core | Apple Silicon |
| Grafica | OpenGL 3.2 (altrimenti renderer software) | DirectX 11 o OpenGL 3.2 | Metal |
| Memoria | 4 GB | 4 GB | 4 GB |
| Schermo | 1280×720 | 1280×720 | 1280×720 |
| Disco | 150 MB | 150 MB | 150 MB |

Librerie di sistema su Linux:

```
# Debian / Ubuntu (da Ubuntu 24.04: libasound2t64 al posto di libasound2)
sudo apt install libgl1 libglx-mesa0 libgl1-mesa-dri libx11-6 libxcursor1 libxrandr2 libxi6 libxinerama1 libxxf86vm1 libasound2
# Fedora / RHEL / Rocky / Alma
sudo dnf install mesa-libGL mesa-dri-drivers libX11 libXcursor libXrandr libXi libXinerama libXxf86vm alsa-lib
# Arch / Manjaro
sudo pacman -S mesa libglvnd libx11 libxcursor libxrandr libxi libxinerama libxxf86vm alsa-lib
```

## Manuali

In PDF, inclusi in ogni pacchetto:

- [Player's Manual](CoreHack-Manual.pdf) (inglese)
- [Advanced Manual](CoreHack-Advanced-Manual.pdf) (inglese)
- [Manuale del giocatore](CoreHack-Manuale.pdf)
- [Manuel du joueur](CoreHack-Manuel.pdf) (francese)
- [Manuale avanzato](CoreHack-Manuale-Avanzato.pdf)
- [Manuel avancé](CoreHack-Manuel-Avance.pdf) (francese)
- [Manuale del server](CoreHack-Manuale-Server.pdf)

## Novità 2.13.0

- WebLens, un browser da usare fuori missione (menu Applicazioni, `browse`): dato l'IP di un host pubblico di un'azienda ne mostra il sito (home, chi siamo, contatti: i referenti ufficiali vanno in Rubrica) o il terminale informativo con il personale in servizio. Ogni sito ha il suo aspetto. Trovate le credenziali su un host interno si apre l'area riservata: avvisi interni, rubrica interna e indirizzo dell'archivio FTP. Nuovi contratti sui siti: buttarlo giù, sfregiarlo, screditarlo, ripristinarlo.
- I file di credenziali e configurazione si leggono sul posto (pulsante + arancione), non occupano spazio e nel rapporto risultano come credenziali.
- Città ad anelli: le grandi città sono cresciute in verticale, ad anelli sovrapposti, dal Primo Anello al sole fino alle discariche della Fossa (da 4 a 7 anelli per città). Ogni azienda sta nel suo anello (scheda in Rubrica, whois, sito) e le notizie raccontano la vita negli anelli: persone che non sono mai del tutto la loro fazione, e che cosa hanno fatto i tuoi contratti alla gente di quell'anello.
- Contratti speculari: da metà gioco capita che due fazioni vogliano qualcosa dalla stessa azienda. Contesa: il file lo ha uno solo, e chi resta a mani vuote può chiederti una copia (il doppio gioco paga, finché non ti scoprono). Scontro: una fazione paga per colpire, un'altra per difendere; scegli da che parte stare, o leggi com'è finita nelle notizie.
- Nuovi contratti per Lumen (redazioni, ransomware, fondi neri, audit), NetGuard (botnet, congelamenti, lavori civici) e per i quartieri della Rete Nera (usura, ambulatori, liste nere, caporali). Le piste facoltative di Lumen sono anche fonti: ognuna lascia un'informazione vera. Ogni tanto le notizie raccontano la Rete Nera che aiuta i suoi.
- La trama: il Broker e la Rete Nera hanno più profondità (nuove lettere a cui rispondere, la sua parte di colpa, il retro dell'ordine, il consiglio della Rete Nera); l'origine dell'Id è stata riscritta (una chiave sola, l'apertura nella stazione morta, le prove di com'è andata davvero); i Guardiani si presentano dicendo come li conoscevi; i file di trama (parti di Cerbero, Frammenti, chiave, Matrice) stanno nel blocco File chiave dello Storage, non occupano spazio e non si cancellano; le lettere che aspettano una risposta restano non lette; nuove chiusure per G.C.; molte correzioni di coerenza nei testi della trama.
- Gli operatori rivali hanno nomi reali internazionali e crescono più piano. Se possiedi la versione Primaria e quella Nera di un programma scegli quale usare, e nelle reti degli operatori si possono rubare programmi Neri e varianti α/β.
- Assedi: i programmi di difesa oltre la v1 chiedono processore e Cloak all'altezza; una mail avvisa quando qualcuno comincia a sondare il gateway. Le perquisizioni di NetGuard arrivano a un'ora qualsiasi, annunciate da un allarme di traffico anomalo.
- Widget del desktop: il sole e la luna seguono l'ora, e un radar mostra chi tiene d'occhio il tuo gateway e quanto è vicino.
- Reti: i bersagli possono stare in più VLAN sovrapposte; `unlock` libera un host dal tuo stesso cryptolocker.
- Icone al neon per i programmi sperimentali e gli oggetti unici; nuovi tutorial su exploit e falle e su WebLens.
- Musica: tre nuovi brani per la radio, Paper Lanterns (koto e shakuhachi), Causeway Mist (arpa celtica e low whistle) e Tidewater (piano elettrico e violoncello); la radio parte da un brano davvero a caso; uno strato leggero di pianoforte in Guardian Protocol; un brusio appena udibile quando un testo si decifra.
- Interfaccia: l'Archivio è una finestra a sé nella barra in alto, a destra della Rubrica; il rapporto di missione mostra le righe una alla volta; i contatti che portano a un gateway segreto stanno in cima alla Rubrica e si cercano per indirizzo, per parole o per nome; gli avvisi sulle reti molto sopra il tuo livello parlano al condizionale; le restrizioni di protocollo compaiono sul contratto.
- L'accesso libero a un'azienda non fa più passare un giorno.
- Documentazione: nuovo manuale avanzato in francese; i manuali parlano di città ad anelli, contratti speculari, WebLens e file chiave.

### Novità 2.12.0

- Falle e BreachKit: una falla è una debolezza di un tipo di protezione (Firewall, Proxy, Password, Curva) in tutta un'azienda e resta aperta qualche giorno. Si scopre scansionando, leggendo i ticket interni e seguendo le notizie; BreachKit (v1-v5) la sfrutta per far cadere la protezione di colpo e con poco rumore (pulsante EXPLOIT, `exploit <host>`, tasto x).
- Gli operatori più esperti ritoccano i log che lasciano: con un LogParser troppo vecchio si legge una catena falsa, con uno all'altezza il ritocco si riconosce.
- Rubrica a grafo: nuova categoria Individui. Sugli host di lavoro delle aziende ci sono le rubriche dei contatti (`contatti_*.vcf`): leggerle porta in Rubrica il proprietario e le persone che conosce. Dalla scheda si naviga tra le conoscenze (Conosce:) e si contatta una persona a pagamento per un altro nome o un'informazione (`people`, `contact`).
- Volti: i personaggi unici hanno il ritratto del sito, tutti gli altri un avatar generato; compaiono nella scheda in Rubrica e nella posta (una sagoma per chi non ha volto).
- ExploitForge: le scansioni danno campioni delle protezioni e con tre campioni la forgia costruisce una falla che dura più a lungo. Tutto passa dalla nuova finestra Exploit nella scheda dell'azienda in Rubrica (`forge`).
- Exploit su commissione: un esperto per fazione, ognuno a modo suo (il Fabbro della Rete Nera, Vantage Labs del Concordato, Halloran di NetGuard, il collettivo Prisma di Lumen), raggiungibili con la reputazione o trovandoli nella rubrica delle figure di spicco; i dipendenti del reparto IT vendono la falla della loro azienda; nelle reti della Rete Nera ci sono kit già pronti (`order`).
- Informazioni false, introdotte gradualmente: password civetta, credenziali preparate per chi ascolta, file esca (ticket inventati, debiti e segreti che non esistono), voci nelle notizie e soffiate da verificare. Ci si difende con Inspect, con il riscontro di una seconda fonte e con la Verifica di ExploitForge; le trappole costano traccia, allerta e sorveglianza, mai il contratto.
- Sistema > Programmi: i programmi posseduti sono divisi in linguette per categoria, come nel Mercato; installando un programma si apre la sua linguetta.
- Contratti: il testo di un contratto di cancellazione con i backup ora nomina sempre il file da far sparire; se la rete reale sposta il bersaglio su un altro host, il testo segue anche il nodo. Un nuovo controllo automatico confronta il testo di migliaia di contratti con le reti reali.

### Novità 2.11.5

- Rubrica: la ricerca per indirizzo IP trova l'azienda anche dagli indirizzi registrati con ping e mette in evidenza l'host corrispondente; nella scheda gli host scoperti sono un elenco scorrevole che non copre più i pulsanti in fondo.
- Gateway segreti più facili da trovare: ogni indizio dice in quale azienda è nascosto il prossimo che manca (l'Archivio lo ricorda), ogni indizio ha almeno due copie per fazione e le notizie che ne regalano uno arrivano più spesso e danno il primo che manca.
- Traceroute ha 5 versioni (v1-v3 nel gateway base, v4-v5 nei gateway di fazione): sulle catene di relay degli operatori si parte dal 50% e ogni versione aumenta la probabilità di scoprire il salto successivo.
- Mercato: i programmi in vendita sono divisi in linguette per categoria (Red, Blue, Utilità, Exploit).

### Novità 2.11.4

- Rubrica: nella casella di ricerca un pulsante a discesa mostra le reti visitate di recente; sceglierne una la seleziona sulla mappa.
- Banca: nella lista dei movimenti i bonifici e le righe troppo lunghe si aprono con un clic, per leggere tutto il testo e il numero di conto della controparte.
- Le tracce bancarie seguono il destinatario: un movimento porta a te solo se la controparte sei tu (nick o numero di conto). Se nel movimento che porta a te metti un nickname, un nome o un cognome inesistenti, o di qualcun altro, la pista si perde: la banca segnala l'anomalia, ma senza conseguenze per te.
- Gli operatori arrestati rientrano con un nuovo nick e 2-3 livelli sotto quelli che avevano (mai sotto 1), invece di ripartire da zero.
- KeyWraith scrive solo quando ha qualcosa di nuovo; il mittente delle sue mail indica il nodo e la rete in cui è impiantato.
- Nel Fascicolo la riga dell'infiltrato va a capo e non finisce più sotto il pulsante.

### Novità 2.11.3

- Ripristino esatto della partita: il gioco tiene una cronologia degli ultimi 7 giorni di gioco (un punto a ogni ora nuova e dopo ogni missione, in un file accanto ai salvataggi). In chsavedit, riportando indietro il giorno si può tornare esattamente a quel giorno e a quell'ora: soldi, reputazione, programmi, trama, debiti, sequestri, blocchi del conto e condanne successivi spariscono. Da terminale: `chsavedit hist N` e `chsavedit restore N giorno [ora]`.
- Un accesso libero rimasto aperto alla fine della partita non blocca più il pulsante «Accesso all'host» della Rubrica; i salvataggi colpiti si sistemano da soli al caricamento, e se il pulsante è spento un suggerimento spiega perché.
- chsavedit, riportando indietro i giorni nei salvataggi senza cronologia, riapre la partita chiusa e toglie i blocchi del conto scattati dopo il nuovo giorno.

### Novità 2.11.2

- Icone neon nuove per tutti i programmi e per le protezioni degli host, nei colori delle famiglie: rosso i Red, azzurro i Blue, grigio chiaro le utilità, viola chiaro gli exploit; i Primari bianchi e i Neri viola scuro. Compaiono nel Mercato, nei programmi del gateway e sulla mappa della rete.
- Le icone delle azioni in missione sono state rifatte nello stesso stile; sui pulsanti con una scorciatoia da tastiera compare la lettera in un quadratino.
- Il gioco va in pausa da solo quando la sua finestra perde il focus.
- La barra viola dell'accecamento ora si vede anche sul nodo selezionato e sotto il 20% pulsa in modo evidente.
- Le notifiche restano 10 secondi; un clic le chiude in dissolvenza.
- Devour non lascia più log: l'host distrutto se li porta via.
- I file cancellati compaiono nell'elenco solo con Inspect e un FileUndeleter capace di recuperarli.
- Nell'Archivio le informazioni raccolte sulle fazioni si chiamano «Informazioni su…».

### Novità 2.11.1

- Fuori dalle missioni, i log gialli e rossi compaiono come notifiche in alto a destra quando la finestra Eventi è chiusa: entrano in dissolvenza e svaniscono dopo 6 secondi.

### Novità 2.11.0

- Cerbero, i Frammenti e ION ora fanno parte di una sola storia: al capitolo 4 di ogni arco tieni l'originale della parte di Cerbero e consegni una copia.
- Dopo il blocco delle alleanze arrivano il Recupero, l'Attacco e una nuova missione segreta sulle orme di Orfeo; le IA delle fazioni si fanno vive più avanti, una alla volta.
- Una copia venduta nell'Ombra può finire nelle difese della fazione rivale.
- Una barra viola sotto il nodo mostra quanto resta dell'accecamento dell'IDS.
- In bacheca due icone sostituiscono le diciture RED e BLUE.

**2.10.2:** icone dei contratti; manuali in inglese; il titolare derubato se ne accorge entro 24 ore; bollette e scadenze fra le 2 e le 6 del mattino.

**2.10.1:** tutorial nuovi *Operatori e indagini* e *Fascicoli e persone*; Devour e DarkHole corrodono l'host in glitch fino a farlo sparire; gli operatori arrestati tornano con un nome nuovo.

**2.10.0:** contratti a host ignoto e di consegna; Devour e DarkHole distruggono un host per sempre; nuovi contratti di distruzione.

## Sostieni il progetto

Core:Hack è il lavoro di una persona sola, nel tempo libero. Se ti piace: [Ko-fi](https://ko-fi.com/guidocauli) · [PayPal](https://paypal.me/guidocauli).

---

Core:Hack: Blackout - Guido Cauli <guido.cauli@gmail.com>
