# Guida d'uso di Multifolio

Questa guida spiega come usare Multifolio passo per passo, sul telefono, sul tablet,
sul computer e nella web app. Le voci dei menu sono scritte come le trovi nell'app
(per esempio **Impostazioni › Funzioni**).

[← Torna a Multifolio](README.md) · [Novità](CHANGELOG.md)

## Indice

1. [Primo avvio](#1-primo-avvio)
2. [Portafogli, conti e profili](#2-portafogli-conti-e-profili)
3. [Aggiungere asset e movimenti](#3-aggiungere-asset-e-movimenti)
4. [Prezzi e valute](#4-prezzi-e-valute)
5. [Collegamenti: exchange e indirizzi](#5-collegamenti-exchange-e-indirizzi)
6. [La home e lo swipe tra le pagine](#6-la-home-e-lo-swipe-tra-le-pagine)
7. [Andamento, analisi e grafici](#7-andamento-analisi-e-grafici)
8. [Obiettivi](#8-obiettivi)
9. [Movimenti ricorrenti](#9-movimenti-ricorrenti)
10. [Ribilanciamento](#10-ribilanciamento)
11. [Report PDF e riepilogo di fine anno](#11-report-pdf-e-riepilogo-di-fine-anno)
12. [Pool DeFi e monitoraggio](#12-pool-defi-e-monitoraggio)
13. [Notifiche e avvisi](#13-notifiche-e-avvisi)
14. [Impostazioni › Funzioni](#14-impostazioni--funzioni)
15. [Temi ed effetti](#15-temi-ed-effetti)
16. [Backup e ripristino](#16-backup-e-ripristino)
17. [Account Multifolio e codice di recupero](#17-account-multifolio-e-codice-di-recupero)
18. [Cambiare telefono](#18-cambiare-telefono)
19. [Tablet, orizzontale e computer](#19-tablet-orizzontale-e-computer)
20. [Web app o app installata?](#20-web-app-o-app-installata)
21. [Privacy e sicurezza](#21-privacy-e-sicurezza)
22. [Domande frequenti](#22-domande-frequenti)
23. [Problemi comuni](#23-problemi-comuni)

---

## 1. Primo avvio

Alla prima apertura alcune schermate presentano l'app; poi Multifolio chiede
**da dove partire**:

- **Crea il primo portafoglio** – per iniziare da zero.
- **Importa da Delta o da un backup** – se arrivi dall'app Delta (file CSV) o hai già
  un backup di Multifolio.
- **Ho già un account Multifolio** – entra con email e password e ritrovi i tuoi dati.

Puoi fare tutto anche dopo, dalle impostazioni. Consiglio: appena hai inserito i primi
dati, imposta subito una **password dei backup** (vedi [Backup](#16-backup-e-ripristino)).

## 2. Portafogli, conti e profili

Multifolio organizza il patrimonio su tre livelli:

| Livello | Cos'è | Esempi |
|---|---|---|
| **Portafoglio** | Un gruppo di asset, con un colore | "Crypto", "Conti bancari", "Oro" |
| **Asset** | Cosa possiedi | Bitcoin, Euro, ETF VWCE, oro in grammi |
| **Conto** | Dove lo tieni | la tua banca, un exchange, un wallet, il broker, la cassaforte |

Lo stesso asset può stare in più conti (per esempio Bitcoin su un exchange e su un
wallet hardware): l'app somma tutto e ti mostra **dove lo tieni** e in che percentuale.

**Creare un portafoglio:** dalla home tocca **Crea portafoglio** (o **+ Aggiungi**),
poi **Scegli un modello** (Contanti, Conti bancari, Carte e app di pagamento, Risparmio,
Le mie Crypto, Azioni ed ETF, Obbligazioni e titoli di Stato, Metalli preziosi,
Previdenza, Crediti e debiti, Beni) oppure **Scegli tu nome e colore**.

**Gestire un portafoglio:** aprilo e tocca **⋯** per rinominarlo, escluderlo dal totale,
ordinare e filtrare gli asset o eliminarlo (vengono eliminati anche asset e movimenti).
L'ordine dei portafogli si cambia dalla home con **Riordina**.

**Conti:** l'icona della banca in alto nella home apre l'elenco dei conti. L'elenco di
banche, exchange e wallet proposti si gestisce in **Impostazioni › Portafogli ed elenchi ›
Banche, exchange e wallet**.

**Cosa ti interessa:** in **Impostazioni › Portafogli ed elenchi** puoi spegnere le
categorie che non usi (per esempio obbligazioni): spariscono dai modelli e dai tipi di asset.

**Profili** (funzione facoltativa): per tenere separati patrimoni diversi (personale,
famiglia, azienda) nella stessa app. Ogni profilo ha il suo totale, il suo andamento e i
suoi report. Si gestiscono in **Impostazioni › Portafogli ed elenchi › Profili**; il
selettore del profilo compare nella home. Eliminando un profilo i suoi portafogli non si
cancellano: tornano in *Personale*.

## 3. Aggiungere asset e movimenti

### Aggiungere un asset

1. Apri un portafoglio e tocca **Aggiungi asset** (o il tasto **+**).
2. Cerca l'asset: per le crypto scrivi simbolo o nome (es. *USDT*, *Bitcoin*), per azioni
   ed ETF **Cerca il titolo** (es. *VWCE*, *Apple*) per avere il prezzo automatico, per i
   metalli **Scegli il metallo**. Per beni o asset senza quotazione scrivi un nome
   (es. *Auto*) e un **valore unitario**.
3. **Scegli il conto dove lo tieni** e scrivi la **quantità**.

### Numeri all'italiana

Gli importi si scrivono **come in Italia**: punto per le migliaia e virgola per i decimali,
per esempio `1.000,50`. Funziona anche il formato inglese (`1000.50`): l'app lo riconosce.
Le crypto accettano fino a 8 decimali (es. `0,00125`).

### Movimenti

Tocca un asset per vedere **dove lo tieni** e i **movimenti**. Con **Aggiungi movimento**
puoi registrare:

- **Deposito** e **Prelievo** – soldi o asset che entrano o escono;
- **Acquisto** e **Vendita** – con il **prezzo** di 1 unità (lascialo vuoto per usare
  il prezzo automatico del giorno);
- **Correzione** – per allineare il saldo a quello reale;
- **Trasferisci** – sposta una quantità verso un altro conto (es. da exchange a wallet).

Ogni movimento può avere una **nota** e, se la funzione *Foto sui movimenti* è accesa,
una **foto** (ricevuta, screenshot). Con **Ripeti** il movimento diventa
[ricorrente](#9-movimenti-ricorrenti).

**Prezzo medio e guadagno:** se scrivi il prezzo d'acquisto nei movimenti, nel dettaglio
dell'asset compaiono **prezzo medio di carico**, **investito** e **guadagno**. Se hai
sbagliato, tocca il movimento per correggerlo o eliminarlo; molte azioni si possono
**annullare** dal messaggio che compare in basso.

**Cerca:** la lente nella home cerca tra asset, portafogli, conti, movimenti e note.

## 4. Prezzi e valute

- I prezzi si aggiornano **da soli**: ogni pochi secondi con l'app aperta e
  periodicamente in background. Tira giù la home o tocca **Aggiorna i prezzi** per
  forzare l'aggiornamento. Sotto il totale vedi l'ora dell'ultimo aggiornamento.
- **Fonte prezzi crypto** (**Impostazioni › Valute e prezzi**): Binance (rapido, coin
  principali), Coinbase (cambio EUR diretto) o CoinGecko (migliaia di token, più lento).
  Se un token non c'è sulla fonte scelta, il prezzo arriva da CoinGecko.
- Azioni ed ETF arrivano da Yahoo Finance; i cambi delle valute dalla BCE (le valute del
  Golfo, come il dirham, sono agganciate al dollaro).
- **Aggiornamento prezzi:** scegli la frequenza; più spesso = più dati e batteria.
- **Valuta principale:** tutti i totali vengono mostrati in questa valuta (euro, dollaro,
  dirham, franco svizzero e molte altre).
- **Seconda valuta sotto il totale:** utile se vivi o investi in due valute.
- **Come scrivere gli importi:** simbolo o sigla (`€` o `EUR`), prima o dopo il numero
  (`€ 1.250` o `1.250 €`), `US$` al posto di `$` per non confonderlo con USDT e USDC,
  `Fr.` al posto di `CHF`.
- **Icone delle valute** (in **Aspetto**): bandiera o moneta.

## 5. Collegamenti: exchange e indirizzi

Con i collegamenti i saldi si aggiornano da soli. Accendi prima **Saldi da indirizzi**
e/o **Sincronizzazione exchange** in **Impostazioni › Funzioni**, poi apri
**Impostazioni › Funzioni › Collegamenti automatici › Nuovo collegamento**.

### Indirizzi pubblici

Incolla l'**indirizzo pubblico** di un wallet: Bitcoin, Ethereum e reti EVM, Solana, Tron,
Litecoin, Dogecoin o XRP. Serve solo l'indirizzo pubblico: **non inserire mai la frase
di recupero (seed) né chiavi private**, Multifolio non le chiede.

### Exchange

Exchange supportati: **Binance, Bybit, OKX, KuCoin, Gate, MEXC, Kraken, Bitget, Nexo Pro**.

1. Sul sito dell'exchange crea una **chiave API in sola lettura** (*Read only*).
   **Non attivare mai** trading, prelievi o trasferimenti: a Multifolio servono solo i saldi.
2. In Multifolio scegli l'exchange e incolla chiave e segreto (per OKX, KuCoin e Bitget
   anche la *passphrase*).
3. Scegli il **portafoglio per i nuovi asset** e tocca **Collega e leggi i saldi**.

I saldi si aggiornano all'apertura dell'app e circa ogni ora in background; con
**Sincronizza ora** o **Sincronizza tutto** li aggiorni subito. Ogni differenza diventa un
movimento *Sincronizzazione*, così lo storico resta.

> Le chiavi API restano **solo su questo dispositivo**, cifrate, e **non finiscono nei
> backup** né sul server. Su un telefono nuovo vanno inserite di nuovo.

### Posizioni DeFi

Con la funzione **Posizioni DeFi e APY** l'app legge depositi, prestiti e vault di Aave,
Spark, Beefy, Ether.fi, Kamino e Jupiter dagli indirizzi collegati, con APY e guadagno
stimato.

## 6. La home e lo swipe tra le pagine

La home è fatta di pagine che scorrono **orizzontalmente** (i puntini in basso dicono
dove sei):

1. **Totale** – il patrimonio complessivo, la variazione di oggi, il grafico
   *Andamento e ripartizione* e l'elenco dei portafogli con l'interruttore
   **Includi nel totale**.
2. **Un portafoglio per pagina** – scorri a destra per aprirli uno dopo l'altro.
3. **Monitoraggio pool** – l'ultima pagina, se la funzione è accesa.

In alto trovi: l'**occhio** per nascondere gli importi (utile in pubblico), la **lente**
per cercare, l'icona della **banca** per i conti e quella delle **impostazioni**.
Il tasto **+ Aggiungi** aggiunge un asset o un movimento al volo.

Altri elementi che possono comparire nella home: indice **Fear & Greed**, campanello
delle **notizie** (se accese), guadagno sul totale, rendimento per periodo.
Quando il patrimonio tocca un nuovo massimo l'app festeggia il **record**.

## 7. Andamento, analisi e grafici

Tocca **Andamento e ripartizione** nella home per aprire l'analisi:

- **Grafico del patrimonio** con periodi 7G, 1M, 3M, 1A, Tutto; trascina il dito sul
  grafico per leggere il valore di un giorno.
- **Ripartizione** per categoria, per portafoglio e asset principali.
- **Rendimento per periodo**: 1 settimana, 1 mese, da inizio anno, 1 anno, anche per
  portafoglio.
- **Confronto con un riferimento**: il tuo patrimonio contro Bitcoin, S&P 500 o
  l'inflazione sullo stesso grafico.
- **Mappa di calore**: riquadri grandi quanto il peso di ogni asset, verdi o rossi per la
  variazione del giorno.
- **Immagine da condividere**: la ripartizione in percentuale, **senza importi**.

Lo storico si costruisce giorno per giorno. Se hai inserito movimenti con date passate,
in **Impostazioni › Backup e sincronizzazione** puoi usare **Ricostruisci storico**.

## 8. Obiettivi

Apri **Obiettivi** (dalla home, dall'analisi o da **Impostazioni › Funzioni**) e tocca
**Nuovo obiettivo**: dai un nome (es. *Casa*), l'importo e, se vuoi, una scadenza.
Multifolio mostra il progresso sul totale dei portafogli inclusi e **stima quando ci
arrivi** al ritmo attuale (servono almeno 7 giorni di storico). Quando raggiungi un
obiettivo partono fuochi d'artificio o coriandoli, se gli effetti sono accesi.

## 9. Movimenti ricorrenti

Per stipendio, affitto o piani di accumulo: quando aggiungi un movimento scegli **Ripeti**
ogni settimana, mese o anno. I movimenti vengono registrati **da soli** alla data
prevista, anche se apri l'app qualche giorno dopo. L'elenco è in
**Impostazioni › Funzioni › Movimenti ricorrenti**.

## 10. Ribilanciamento

In **Impostazioni › Funzioni › Ribilanciamento** scegli quanto vuoi in ogni categoria
(il totale deve fare 100%, oppure tocca **Usa quella attuale**) e una tolleranza:
l'app ti dice **quanto spostare** per tornare in equilibrio. È solo un calcolo: non
esegue operazioni.

## 11. Report PDF e riepilogo di fine anno

- **Report mensile PDF** (**Impostazioni › Funzioni**): un PDF con totale, variazione del
  mese, grafico, ripartizione per categoria e portafoglio, asset principali e obiettivi.
  Scegli il mese e salvalo o condividilo.
- **Riepilogo di fine anno**: i valori al 31 dicembre per conto e per paese, in PDF o CSV.
  Utile come promemoria per la dichiarazione dei redditi (non sostituisce il
  commercialista).

## 12. Pool DeFi e monitoraggio

### Avvisi pool APY

1. Accendi **Avvisi pool APY** in **Impostazioni › Funzioni**.
2. Apri **Impostazioni › Notifiche › Avvisi pool APY**.
3. Incolla il **link del pool** copiato dal sito del protocollo (Beefy, Kamino, Jupiter,
   Aave, Spark, Compound, Benqi, DefiLlama…) oppure **Scegli dai pool consigliati**.
4. Imposta le soglie **sopra** e/o **sotto** e ogni quanto controllare.

### Monitoraggio pool

Con **Monitoraggio pool DeFi** acceso, l'ultima pagina della home mostra i pool scelti
con APY, liquidità (TVL) e utilizzo. Tocca un pool per aprirne i **grafici** e gli
**avvisi di rischio**: TVL in calo, APY anomalo, contratti in pausa, possibili exploit,
poca liquidità o **liquidità di nuovo disponibile**. Puoi ordinare i pool per APY o
liquidità. Le soglie si regolano in **Impostazioni › Notifiche › Soglie del monitoraggio
pool**. Sull'app iPhone è disponibile anche un widget con i pool monitorati.

## 13. Notifiche e avvisi

Tutto in **Impostazioni › Notifiche**:

- **Avvisi di prezzo** – apri un asset, tocca **⋯** e scegli **Avviso di prezzo**:
  notifica quando il prezzo supera o scende sotto una soglia.
- **Avvisi in percentuale** – quando un asset che hai sale o scende di molto in 24 ore
  (scegli la variazione minima).
- **Allarme stablecoin** – se USDT, USDC, DAI o simili si staccano da 1 dollaro.
- **Avvisi pool APY** e **Soglie del monitoraggio pool** – vedi sopra.
- **Notizie di attacchi hacker** – **spenta di default**. Accendila in
  **Impostazioni › Funzioni**: un pannello raccoglie gli attacchi recenti a exchange,
  wallet e protocolli crypto (Google News e DefiLlama, ogni 15 minuti) e una notifica
  apre la notizia. Puoi scegliere tutti gli attacchi o solo quelli che riguardano
  *i tuoi* exchange, wallet, crypto e protocolli. Gli avvisi di possibili exploit dei
  pool monitorati arrivano comunque, anche con le notizie spente.
- **Promemoria backup** – ti avvisa se non salvi un backup da troppo tempo.
- **Ore di silenzio** – di notte le notifiche arrivano senza suono né vibrazione.
- **Prova una notifica** – per controllare che i permessi siano a posto.

Con l'app aperta i prezzi si controllano ogni 20 secondi; sul telefono un controllo in
background circa ogni 15 minuti tiene vivi avvisi e widget.
**Web app:** per ricevere gli avvisi a sito chiuso accendi **Notifiche ad app chiusa**
in **Impostazioni › Funzioni** (su iPhone prima aggiungi il sito alla schermata Home).

## 14. Impostazioni › Funzioni

Ogni funzione non essenziale si **accende o spegne** qui; spenta, sparisce dall'app.
Le funzioni sono divise in gruppi:

- **Analisi** – Andamento e grafici, Guadagno sul totale, Guadagno nei portafogli,
  Rendimento negli asset, Rendimento per periodo, Confronto con un riferimento,
  Mappa di calore, Mini grafici nei portafogli, Ribilanciamento.
- **Crypto e DeFi** – Saldi da indirizzi, Sincronizzazione exchange, Posizioni DeFi e
  APY, Avvisi pool APY, Monitoraggio pool DeFi, Notizie di attacchi hacker (spenta di
  default), Indice Fear & Greed.
- **Strumenti e automazioni** – Obiettivi, Report PDF, Avvisi di prezzo, Movimenti
  ricorrenti, Foto sui movimenti, Widget nella Home, Storico dei movimenti, Immagine da
  condividere, Riepilogo di fine anno, Profili.
- **Effetti speciali** – vedi [Temi ed effetti](#15-temi-ed-effetti).
- **Musica di sottofondo** – rilassante o per la concentrazione (brano e volume in
  **Impostazioni › Avanzate**).

Da qui si aprono anche gli strumenti accesi (Collegamenti, Storico, Ribilanciamento,
Obiettivi, Report, Riepilogo di fine anno, Monitoraggio pool, Notizie, Ricorrenti).
Ogni pagina delle impostazioni ha **Ripristina predefiniti**; la casella **Cerca nelle
impostazioni** trova subito qualsiasi voce.

## 15. Temi ed effetti

In **Impostazioni › Aspetto**:

- **Tema:** Classico (chiaro, scuro o come il sistema), Carta (chiaro, testo più grande),
  Ardesia (scuro riposante), Blu notte (scuro elegante), Sakura Pop (pastelli, vignette
  e petali), Ghiaccio (grigio chiarissimo e azzurro).
- **Dimensione del testo** (si somma a quella del telefono).
- **Effetti speciali**, uno per uno: cifre a contachilometri, fuochi d'artificio,
  coriandoli, riflesso sul totale, grafico animato, profondità tra i portafogli, pioggia
  di monete, cambio tema a cerchio, petali e stelline (Sakura Pop).

Se sul telefono è attivo *riduci animazioni*, gli effetti restano spenti. Nella web app,
in **Impostazioni › Avanzate**, c'è la **Modalità leggera** (niente sfondi animati ed
effetti, per scorrere più fluido) e la scelta del motore grafico.

## 16. Backup e ripristino

Tutto in **Impostazioni › Backup e sincronizzazione › Backup, Google Drive e CSV**.

1. **Imposta password dei backup** (almeno 10 caratteri). **Conservala bene**: se la perdi,
   i backup non si possono recuperare.
2. Scegli dove salvare:
   - **Salva backup cifrato** – un file da salvare o condividere (File, e-mail, un'app
     cloud come Proton Drive o Icedrive tramite *Condividi*);
   - **Cartella del telefono** – il backup viene salvato lì, anche in una cartella
     sincronizzata con il cloud;
   - **Google Drive** (app Android e sito) – backup cifrato automatico quando chiudi l'app,
     se hai cambiato qualcosa, più una **copia mensile visibile** nella cartella
     *Multifolio* del Drive.
3. **Promemoria backup** ti avvisa se è passato troppo tempo dall'ultimo.

Il backup contiene **tutti i dati e tutte le impostazioni**, tranne quelle che valgono
solo per il dispositivo: blocco con impronta, cartelle scelte e **chiavi API degli
exchange** (che restano solo sul telefono).

**Ripristinare:** **Ripristina da file** o **Ripristina da Drive**, scrivi la password e
conferma. Attenzione: i dati attuali sul dispositivo **vengono sostituiti** da quelli del
backup.

**CSV e Delta:** **Importa da Delta** (in Delta: menu ☰ › Impostazioni › Dispositivi e dati ›
Esporta dati), **Esporta CSV completo** (si apre con Excel) ed **Esporta CSV per Delta**.

## 17. Account Multifolio e codice di recupero

L'account (facoltativo) tiene **gli stessi dati sul telefono, sull'iPhone e sul sito**:
ogni modifica arriva sugli altri dispositivi in pochi secondi.

1. **Impostazioni › Backup e sincronizzazione › Account Multifolio**.
2. Crea l'account con email e password (almeno 10 caratteri), oppure entra.
3. Se sia il dispositivo sia l'account hanno già dei dati, scegli se **unirli** o
   **usare i dati dell'account**. Se trovi portafogli doppi, usa **Togli i doppioni**.
4. **Crea subito il codice di recupero** (24 caratteri, es. `XXXX-XXXX-…`) e conservalo in
   un posto sicuro, per esempio un gestore di password.

Perché il codice è importante: i dati partono **già cifrati con la tua password** e il
server non può leggerli. Per questo la password **non si reimposta via email**. Se la
dimentichi: **Password dimenticata?** › email + codice di recupero + nuova password.
Senza codice, puoi ancora cambiarla da un dispositivo dove sei collegato; senza codice
e senza dispositivi collegati l'account non si può recuperare (i dati sul dispositivo
restano comunque).

Altre azioni: **cambia password** (gli altri dispositivi dovranno entrare di nuovo),
**esci** (i dati restano sul dispositivo ma non si sincronizzano più), **elimina
account** (cancella i dati dal server, non dai dispositivi; chiede la password).
Le chiavi API degli exchange e le foto non vengono sincronizzate.

## 18. Cambiare telefono

> **Il trasferimento automatico di Android (o il ripristino da backup di Google) non copia
> i dati di Multifolio.** È voluto: i dati sono protetti e restano fuori dai backup del
> sistema.

Per portare i dati sul telefono nuovo, scegli **uno** di questi modi:

- **Account Multifolio:** installa l'app sul telefono nuovo e scegli *Ho già un account
  Multifolio*.
- **Google Drive:** sul telefono vecchio **Fai il backup ora**; sul nuovo accedi con lo
  stesso Google e scegli **Ripristina da Drive**.
- **File:** sul vecchio **Salva backup cifrato** e trasferisci il file; sul nuovo
  **Ripristina da file** con la password dei backup.

Poi ricollega gli **exchange** inserendo di nuovo le chiavi API (non vengono copiate).

## 19. Tablet, orizzontale e computer

- Su **tablet** e **computer** l'app usa un layout più largo: barra laterale con le
  sezioni, cruscotto a due colonne, tabella degli asset e grafici più grandi.
- In **orizzontale** (telefono e tablet) la barra a icone va di lato, i grafici crescono
  e fogli e dialoghi scorrono quando apri la tastiera.
- Sul computer puoi usare la [web app](https://multifolio.pages.dev) e installarla dal
  browser (Chrome o Edge › icona *Installa*).

## 20. Web app o app installata?

| | Web app | App Android | App iPhone (IPA) |
|---|---|---|---|
| Installazione | nessuna (o *Aggiungi a Home*) | APK | SideStore/AltStore, rinnovo ogni 7 giorni |
| Dati | nel browser di quel dispositivo | nel telefono | nel telefono |
| Notifiche ad app chiusa | sì, con *Notifiche ad app chiusa* | sì | sì |
| Backup su Google Drive | sì | sì | no (usa file o account) |
| Widget nella Home | no | sì (totale) | pool monitorati, se incluso nella versione |
| Foto sui movimenti | no | sì | sì |

**Attenzione:** i dati della web app stanno nel browser. Se cancelli i dati di
navigazione del sito li perdi: fai un backup o usa l'account Multifolio.
Per avere gli stessi dati su web e telefono usa l'**account Multifolio**.

## 21. Privacy e sicurezza

- **Blocca con impronta o volto** e **Blocco automatico** (dopo quanto tempo in
  background chiede di nuovo lo sblocco) in **Impostazioni › Privacy e sicurezza**.
- **Nascondi importi**: l'occhio nella home o l'impostazione fissa. Con il blocco attivo,
  anche il widget nasconde gli importi.
- I dati restano sul dispositivo; backup e account sono cifrati con la tua password.
  Dettagli nella sezione [Privacy](README.md#privacy).

## 22. Domande frequenti

**Multifolio è gratis? Ci sono pubblicità?**
È un'app personale condivisa così com'è: niente pubblicità e niente tracciamento.

**Multifolio può fare operazioni sui miei conti?**
No. Legge solo saldi e prezzi. Per gli exchange usa chiavi **in sola lettura**.

**Devo inserire la seed phrase del wallet?**
**Mai.** Basta l'indirizzo pubblico. Nessuna app seria te la chiede.

**Perché il valore è diverso da quello dell'exchange?**
Fonti di prezzo diverse e orari di aggiornamento diversi. Puoi cambiare la fonte in
**Impostazioni › Valute e prezzi**.

**Posso usare l'app in un'altra valuta?**
Sì: valuta principale e seconda valuta in **Impostazioni › Valute e prezzi**.

**Come registro debiti o soldi prestati?**
Usa il modello di portafoglio **Crediti e debiti** (i debiti sono valori negativi).

**Posso tenere separati i soldi di famiglia e quelli personali?**
Sì, con i **Profili**.

**Gli aggiornamenti cancellano i dati?**
No: l'APK nuovo si installa sopra quello vecchio e i dati restano. Non disinstallare
l'app per aggiornarla.

**L'app iPhone non si apre più.**
Probabilmente la firma di 7 giorni è scaduta: apri SideStore o AltStore e rinnovala.
I dati non si perdono.

## 23. Problemi comuni

| Problema | Cosa fare |
|---|---|
| **Prezzi non aggiornati** | Controlla la connessione e tocca *Aggiorna i prezzi*. Se un token non ha prezzo, prova un'altra fonte in *Valute e prezzi*. |
| **Alcuni prezzi mancanti** in un portafoglio | L'asset non è stato riconosciuto: aprilo e collegalo al titolo giusto o scrivi un valore unitario manuale. |
| **L'exchange non si sincronizza** | Verifica che la chiave API sia attiva, in sola lettura, con i permessi di lettura dei saldi e (per OKX, KuCoin, Bitget) con la passphrase giusta. Gli errori sono in *Impostazioni › Avanzate › Diagnostica*. |
| **Non arrivano le notifiche** | *Impostazioni › Notifiche › Prova una notifica*. Se il permesso è negato, abilitalo nelle impostazioni del telefono. Controlla le ore di silenzio e il risparmio energetico. Sul web: *Notifiche ad app chiusa* e, su iPhone, il sito aggiunto alla schermata Home. |
| **La web app scatta su iPhone** | Prova la *Modalità leggera* in *Impostazioni › Avanzate* o spegni qualche effetto. |
| **"Password errata" aprendo un backup** | Serve la password dei backup usata quando il backup è stato creato. |
| **Backup nuovo lento da aprire con un'app vecchia** | I backup recenti usano una cifratura più robusta: aggiorna l'app. |
| **Doppioni dopo l'accesso all'account** | *Account Multifolio › Togli i doppioni*. |
| **Ho perso la password dell'account** | *Password dimenticata?* con il codice di recupero, oppure cambiala da un dispositivo ancora collegato. |
| **Lo storico ha buchi** | *Impostazioni › Backup e sincronizzazione › Ricostruisci storico*. |
| **Android blocca l'installazione dell'APK** | Consenti l'installazione da questa origine (vedi la [guida all'installazione](../README.md#installare-unapp-su-android-file-apk)). |

Per segnalare un problema: [Issues › Segnala un problema](https://github.com/Layaris/DMReleases/issues/new/choose).
Non inserire mai importi, indirizzi, chiavi o altri dati personali nelle segnalazioni.
