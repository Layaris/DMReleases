# DM Releases

Qui trovi le **pubblicazioni ufficiali delle app DM**: i file da installare
(APK per Android, IPA per iPhone), le note di rilascio, le guide d'uso e la grafica.

Questo repository contiene **solo pubblicazioni e documentazione**: niente codice
sorgente delle app, niente dati personali.

**Sito:** [layaris.github.io/DMReleases](https://layaris.github.io/DMReleases/)

---

## Le app

<!-- app:multifolio -->
### <img src="multifolio/grafica/icona-192.png" alt="" width="28" height="28" align="top"> Multifolio

Tutto il tuo patrimonio in un posto solo: conti, contanti, crypto, azioni ed ETF,
obbligazioni, oro e pool DeFi, con prezzi automatici, grafici, obiettivi, report PDF
e backup cifrati. Funziona su Android, iPhone, tablet e computer.

- **Usala subito nel browser:** [multifolio.pages.dev](https://multifolio.pages.dev)
- **Download, descrizione e guida:** cartella [`multifolio/`](multifolio/README.md)
  · [Guida d'uso](multifolio/GUIDA.md) · [Novità](multifolio/CHANGELOG.md)

<!-- multifolio:latest -->
- **Android: 0.6.0 (build 18)** del 07/11/2026 · [Scarica l'APK](https://github.com/Layaris/DMReleases/releases/download/multifolio-v0.6.0-build18/multifolio-0.6.0-build18.apk) · [Novità](multifolio/CHANGELOG.md)
<!-- /multifolio:latest -->
<!-- /app:multifolio -->

<!-- app:packsnap -->
### <img src="packsnap/grafica/icona-192.png" alt="" width="28" height="28" align="top"> PackSnap

Fotografa i tuoi oggetti, scontornali e prepara la valigia con le checklist di viaggio:
valigie, viaggi, liste modello, etichetta con QR e backup. Senza account, i dati restano
sul dispositivo. App Android; su iPhone e computer si usa la web app.

- **Usala subito nel browser:** [dmpacksnap.pages.dev](https://dmpacksnap.pages.dev)
- **Download, descrizione e guida:** cartella [`packsnap/`](packsnap/README.md)
  · [Guida d'uso](packsnap/GUIDA.md) · [Novità](packsnap/CHANGELOG.md) · [Privacy](packsnap/PRIVACY.md)

<!-- packsnap:latest -->
_Prima pubblicazione in preparazione._
<!-- /packsnap:latest -->
<!-- /app:packsnap -->

<!-- app:sigla -->
### <img src="sigla/grafica/icona-192.png" alt="" width="28" height="28" align="top"> Sigla

Compila e firma PDF dal telefono o dal computer: firme disegnate, da foto o scritte, sigla su tutte
le pagine, compilazione automatica dei moduli dai tuoi profili, modelli per i moduli ricorrenti,
penna ed evidenziatore, backup cifrati. Senza account: documenti e firme restano sul dispositivo.
Android, iPhone e [web app](https://layaris.github.io/SIGLAPDF/).

- **Download, descrizione e guida:** cartella [`sigla/`](sigla/README.md)
  · [Guida d'uso](sigla/GUIDA.md) · [Novità](sigla/CHANGELOG.md) · [Privacy](sigla/PRIVACY.md)

<!-- sigla:latest -->
_Prima pubblicazione in preparazione._
<!-- /sigla:latest -->
<!-- /app:sigla -->

---

## Installare un'app su Android (file APK)

1. Apri dal telefono la pagina dell'app (per esempio [Multifolio](multifolio/README.md))
   e tocca il file `.apk` dell'ultima versione per scaricarlo.
2. A download finito tocca la notifica, oppure apri l'app **File** › **Download** e
   tocca il file.
3. La prima volta Android blocca l'installazione: tocca **Impostazioni** e attiva
   **Consenti da questa origine** per l'app con cui hai aperto il file (Chrome o File).
   Su alcuni telefoni la voce si chiama *Installa app sconosciute* o *Origini sconosciute*.
4. Torna indietro e tocca **Installa**. Se compare Play Protect, scegli
   **Installa comunque** (l'app non viene dal Play Store, per questo lo chiede).

**Aggiornare:** scarica il nuovo APK e installalo **sopra** la versione che hai già.
Non serve disinstallare: tutte le versioni sono firmate con la **stessa chiave**, quindi
Android le riconosce come la stessa app e **i dati restano**.

> Non disinstallare l'app per aggiornarla: disinstallando, Android cancella i dati.
> Prima di cambi importanti fai comunque un backup dall'app.

## Installare un'app su iPhone (file IPA)

Apple non permette di installare app fuori dall'App Store con un semplice download.
Si usa un programma di *sideload* che firma l'app con il **tuo Apple ID**. Con un
Apple ID gratuito la firma dura **7 giorni**: poi va rinnovata (i dati restano).

### Con SideStore (consigliato, si rinnova dal telefono)

1. Installa **SideStore** seguendo la guida ufficiale su [sidestore.io](https://sidestore.io)
   (la prima volta serve un computer, una volta sola).
2. Sull'iPhone scarica il file `.ipa` dell'app da questa pagina (Safari › tocca il file ›
   *Scarica*).
3. Apri **SideStore** › **My Apps** › **+** e scegli il file `.ipa` da *File › Download*.
4. Se richiesto, inserisci il tuo Apple ID (serve solo per firmare l'app).
5. La prima volta: **Impostazioni › Generali › VPN e gestione dispositivi** › tocca il
   tuo Apple ID › **Autorizza**. Su iOS 16 e successivi attiva anche
   **Impostazioni › Privacy e sicurezza › Modalità sviluppatore** e riavvia.
6. **Ogni 7 giorni** apri SideStore e tocca **Refresh All** (o il numero dei giorni
   accanto all'app) per rinnovarla.

### Con AltStore

1. Installa **AltServer** sul computer e **AltStore** sull'iPhone seguendo
   [altstore.io](https://altstore.io).
2. Scarica il file `.ipa` sull'iPhone.
3. Apri **AltStore** › **My Apps** › **+** e scegli il file.
4. Autorizza il profilo come al punto 5 di SideStore.
5. Rinnovo ogni 7 giorni: con l'iPhone sulla stessa rete Wi-Fi del computer acceso
   (con AltServer aperto), AltStore rinnova da solo; altrimenti apri AltStore ›
   **Refresh All**.

### Con Sideloadly (dal computer)

1. Installa **Sideloadly** su Windows o Mac da [sideloadly.io](https://sideloadly.io).
2. Collega l'iPhone con il cavo, trascina il file `.ipa` nella finestra, inserisci
   il tuo Apple ID e premi **Start**.
3. Autorizza il profilo come al punto 5 di SideStore.
4. Per rinnovare dopo 7 giorni ripeti l'installazione con lo stesso file o con la
   versione nuova: i dati restano.

**Aggiornare:** installa il nuovo `.ipa` con lo stesso programma e lo stesso Apple ID:
sostituisce l'app senza cancellare i dati.

> Se dimentichi il rinnovo l'app non si apre più, ma **i dati non si perdono**:
> rinnovala e torna come prima.

## Segnalare un problema

Apri una segnalazione nella scheda **Issues** di questo repository con il modulo
*Segnala un problema* (app, versione, dispositivo e passi per ripetere il problema).
Non inserire mai importi, saldi, indirizzi, chiavi o altri dati personali.

## Avvertenze

- Sono **app personali**, sviluppate per uso privato e condivise così come sono,
  **senza alcuna garanzia** di funzionamento, disponibilità o assenza di errori.
- I valori, i prezzi e le analisi mostrati dalle app sono **solo informativi**:
  **non sono consulenza finanziaria**, fiscale o di investimento.
- I prezzi arrivano da servizi esterni e possono essere in ritardo o sbagliati:
  verifica sempre con le fonti ufficiali prima di decidere.
- Installi i file a tuo rischio: scaricali **solo da questo repository** o dal sito
  collegato qui sopra.

© DM Releases. **Tutti i diritti riservati.** Nessuna licenza d'uso del codice o della
grafica è concessa, salvo diversa indicazione futura.
