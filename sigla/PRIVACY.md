# Privacy di Sigla

[← Torna a Sigla](README.md)

*Aggiornata all'8 novembre 2026.*

Sigla è fatta per tenere i tuoi documenti con te.

## Cosa resta sul tuo dispositivo

PDF, firme, sigle, profilo e impostazioni restano **solo sul tuo dispositivo** (o nel tuo browser,
se usi la web app). Non ci sono account, server dell'app, pubblicità o statistiche di utilizzo.
I PDF che apri non vengono copiati da nessuna parte: l'app salva solo il file esportato, dove scegli tu.

I backup sono file `.sigla` che crei tu, cifrati con la tua password (AES-256-GCM, chiave ricavata
con PBKDF2). Senza la password non si aprono.

## Quando l'app usa internet

Solo in questi casi:

| Quando | Dove | Cosa viene inviato |
|---|---|---|
| Riconoscimento AI dei campi (facoltativo, con la tua chiave) | Anthropic (API Claude) | Le immagini delle pagine del documento che scegli di analizzare |
| Avviso di nuova versione (solo app Android, al massimo una volta al giorno, si spegne in *Impostazioni*) | GitHub (`raw.githubusercontent.com`) | Nulla di tuo: l'app scarica il file pubblico `sigla/latest.json` con il numero dell'ultima versione |

Prima di ogni invio l'app chiede quale motore usare e ricorda che le pagine vengono inviate.
Il riconoscimento predefinito funziona **sul dispositivo, senza internet**; sull'app Android anche la
lettura dei documenti scansionati (OCR di Google ML Kit) avviene sul telefono e non invia nulla.
La chiave API resta sul dispositivo e non finisce mai nei backup.
Non usare l'AI per documenti che non vuoi condividere.

I **Recenti** (ultimi PDF esportati) e i **modelli** restano sul dispositivo; i recenti non vanno
nei backup e si possono spegnere e cancellare in *Impostazioni*.

La **web app** è un sito statico ospitato da Cloudflare Pages: Cloudflare riceve la normale richiesta della
pagina (come per qualsiasi sito), ma i documenti che apri non lasciano mai il browser.

## Permessi

- **Fotocamera e galleria:** per lo scanner e per fotografare o importare la firma.
- **Impronta / Face ID:** solo se attivi il blocco delle firme.
- **Internet:** per il riconoscimento AI, se lo usi, e per l'avviso di nuova versione.

## Cancellare i dati

Disinstalla l'app, oppure, per la web app, cancella i dati del sito dal browser.

## Contatti

Per domande apri una segnalazione nella pagina [Issues](https://github.com/Layaris/DMReleases/issues).
