# Novità di Multifolio
<!-- changelog:next -->

## 0.8.0 (build 22) – 11/11/2026

- Versione 0.8.0
- Notizie di exploit: una notifica per notizia, non una per ogni pool
- Notifica dei guadagni dai pool: niente più "guadagno del giorno" come "Ultima ora"; file delle build per 7 giorni
- Data di oggi nei movimenti, prezzo in $, wallet intero copiabile, "Aggiungi conto" completo, reti raggruppate, icone, Be
- Posti per wallet/rete/protocollo (v10), guadagni Aave/Lido/Ether.fi, Gnosis, CSV, «Scarta» definitivo
- Audit completo (23 difetti corretti), scanner pool Beta, conti espandibili, note leggibili, APY a 365 giorni
- Sync: i record di un portafoglio cancellato non restano bloccati; STATO di fine sessione

[Scarica l'APK](https://github.com/Layaris/DMReleases/releases/download/multifolio-v0.8.0-build22/multifolio-0.8.0-build22.apk)

## 0.7.1 (build 21) – 08/11/2026

- Aave USDCn con prezzo, APY su Optimism, ordine per APY e rete dei token negli asset
- Saldi Solana anche dal sito, USDCn con prezzo e APY, Pool DeFi nel menu, notizie su iPhone, collegamenti rinominabili
- 0.7.1: correzioni dal collaudo (ripristino dei backup vecchi, notifiche, avvisi ricorrenti sul sito, ricerca)

[Scarica l'APK](https://github.com/Layaris/DMReleases/releases/download/multifolio-v0.7.1-build21/multifolio-0.7.1-build21.apk)

## 0.7.0 (build 19) – 08/11/2026

- App più semplice (audit applicato), notifiche segnabili come lette, versione 0.7.0
- Campanella con lo storico delle notifiche, report PDF dei guadagni dai pool, audit delle funzioni
- Avvisi di prezzo: una volta o ricorrenti (ogni 2 ore finché non li spegni)
- Guadagni dai pool: portafogli a scelta, indirizzi a confronto, scheda nella home
- Test indipendenti dai tempi della macchina e STATO del quarto giro
- Pool: un solo giro per avvisi APY e monitoraggio, niente corse sull'elenco
- Test delle migrazioni da ogni versione del database
- STATO dopo il terzo giro e sottotitolo di Avanzate

[Scarica l'APK](https://github.com/Layaris/DMReleases/releases/download/multifolio-v0.7.0-build19/multifolio-0.7.0-build19.apk)

## 0.6.0 (build 18) – 07/11/2026

- Prima pubblicazione

[Scarica l'APK](https://github.com/Layaris/DMReleases/releases/download/multifolio-v0.6.0-build18/multifolio-0.6.0-build18.apk)

## 0.6 — novembre 2026

Prima versione pubblicata su DM Releases. Riassume tutto quello che è arrivato fino a
oggi, in parole semplici.

### Novità

- **Tablet e computer**: layout dedicati, con cruscotto a due colonne, barra laterale,
  tabella degli asset e grafici più grandi; layout anche in **orizzontale** su telefono
  e tablet.
- **Impostazioni in 8 categorie** (Aspetto, Valute e prezzi, Portafogli ed elenchi,
  Funzioni, Notifiche, Privacy e sicurezza, Backup e sincronizzazione, Avanzate), con
  ricerca e "Ripristina predefiniti" per ogni pagina.
- **Profili**: patrimoni separati (personale, famiglia, azienda) nella stessa app.
- **Multi-valuta**: valuta principale a scelta, seconda valuta sotto il totale e scelta
  di come scrivere gli importi (simbolo o sigla, prima o dopo il numero).
- **Nuove analisi**: rendimento per periodo, confronto con Bitcoin, S&P 500 o
  inflazione, mappa di calore, mini grafici nei portafogli, ribilanciamento.
- **Nuovi strumenti**: storico di tutti i movimenti con filtri, immagine della
  ripartizione da condividere senza importi, riepilogo di fine anno in PDF o CSV.
- **Notizie di attacchi hacker**: pannello con gli attacchi recenti a exchange, wallet e
  protocolli crypto e notifica che apre la notizia. È **spenta di default**: si accende in
  Impostazioni › Funzioni.
- **Monitoraggio pool DeFi**: pagina con i pool scelti, grafici di APY e liquidità,
  segnali di rischio (TVL in calo, APY anomalo, contratti in pausa, possibili exploit),
  avviso quando la liquidità torna disponibile e widget.
- **Avvisi pool APY** dal link del pool (Beefy, Kamino, Jupiter, Aave, Spark e altri),
  con pool consigliati e ordine per APY o liquidità.
- **Posizioni DeFi** con APY medio: Aave, Spark Savings, Beefy, Ether.fi, Kamino,
  Jupiter; saldi Bybit Earn e Nexo Pro.
- **Indice Fear & Greed** nella home.
- **Temi**: Classico, Carta, Ardesia, Blu notte, Sakura Pop e il nuovo **Ghiaccio**;
  effetti speciali e icone degli asset.
- **Coriandoli** e **musica di sottofondo** (rilassante o per la concentrazione),
  attivabili in Impostazioni › Funzioni.
- **Promemoria backup** e **copie mensili** automatiche su Google Drive e nel telefono.

### Miglioramenti

- Scorrimento e swipe tra le pagine **più fluidi**, soprattutto nella web app su iPhone;
  il dito ferma subito la lista e la segue senza salti.
- Web app su iPhone a schermo intero, motore grafico WebAssembly e **modalità leggera**
  per i dispositivi meno potenti.
- Sakura Pop più leggibile; la web app si aggiorna anche con rete lenta.
- Pool Aave: un solo pool per il mercato del link, con il nome del mercato nell'elenco;
  link di Kamino e Jupiter riconosciuti.
- Uscita più semplice da Monitoraggio pool e Avvisi pool APY; regolazione del volume
  della musica.
- Componenti interni aggiornati per stabilità e sicurezza.

### Correzioni

- Sito che restava bloccato durante la sincronizzazione e possibili doppioni dopo
  l'accesso all'account.
- Striscia vuota in fondo allo schermo nella web app su iPhone (iOS 26).
- Avviso di liquidità dei pool di nuovo disponibile e tasti funzionanti per tutti i pool.

### Sicurezza

- **Backup più robusti**: cifratura con 600 000 iterazioni e password nuove di almeno
  10 caratteri (i backup vecchi si aprono come sempre; quelli nuovi richiedono l'app
  aggiornata).
- **Account**: cancellazione e reset dell'account solo con la password, sessioni che
  scadono dopo 90 giorni, limiti ai tentativi di accesso, protezioni aggiuntive del sito.
- **Android**: i dati non finiscono più nel backup automatico del sistema. Per cambiare
  telefono usa il backup di Multifolio o l'account (l'app lo ricorda nella schermata
  Backup).
- Il **widget** nasconde gli importi quando l'app è protetta dal blocco.
- Notizie di attacchi hacker: al server delle notifiche vanno solo nomi di exchange,
  wallet, crypto e protocolli, e solo se scegli "i miei". Mai saldi né quantità.
