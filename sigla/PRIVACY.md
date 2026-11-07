# Privacy di Sigla

[← Torna a Sigla](README.md)

*Aggiornata al 7 novembre 2026.*

Sigla è fatta per tenere i tuoi documenti con te.

## Cosa resta sul tuo dispositivo

PDF, firme, sigle, profilo e impostazioni restano **solo sul tuo dispositivo** (o nel tuo browser,
se usi la web app). Non ci sono account, server dell'app, pubblicità o statistiche di utilizzo.
I PDF che apri non vengono copiati da nessuna parte: l'app salva solo il file esportato, dove scegli tu.

I backup sono file `.sigla` che crei tu, cifrati con la tua password (AES-256-GCM, chiave ricavata
con PBKDF2). Senza la password non si aprono.

## Quando l'app usa internet

Solo in questo caso, e solo se lo attivi:

| Quando | Dove | Cosa viene inviato |
|---|---|---|
| Riconoscimento AI dei campi (facoltativo, con la tua chiave) | Anthropic (API Claude) | Le immagini delle pagine del documento che scegli di analizzare |

Prima di ogni invio l'app chiede quale motore usare e ricorda che le pagine vengono inviate.
Il riconoscimento predefinito funziona **sul dispositivo, senza internet**; sull'app Android anche la
lettura dei documenti scansionati (OCR di Google ML Kit) avviene sul telefono e non invia nulla.
La chiave API resta sul dispositivo e non finisce mai nei backup.
Non usare l'AI per documenti che non vuoi condividere.

## Permessi

- **Fotocamera e galleria:** per lo scanner e per fotografare o importare la firma.
- **Impronta / Face ID:** solo se attivi il blocco delle firme.
- **Internet:** solo per il riconoscimento AI, se lo usi.

## Cancellare i dati

Disinstalla l'app, oppure, per la web app, cancella i dati del sito dal browser.

## Contatti

Per domande apri una segnalazione nella pagina [Issues](https://github.com/Layaris/DMReleases/issues).
