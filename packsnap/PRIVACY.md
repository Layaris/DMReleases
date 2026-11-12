# Privacy di PackSnap

[← Torna a PackSnap](README.md)

*Aggiornata al 12 novembre 2026.*

PackSnap è fatta per tenere i tuoi dati con te.

## Cosa resta sul tuo dispositivo

Oggetti, foto, valigie, liste, viaggi, documenti e impostazioni sono salvati **sul tuo telefono**
(o nel tuo browser, se usi la web app). L'account non serve: senza la Sincronizzazione online
(spenta all'inizio) niente esce dal dispositivo, se non nei casi elencati sotto.
Non ci sono pubblicità né statistiche di utilizzo.

I backup sono file che crei tu e salvi dove vuoi tu.

## Sincronizzazione online (facoltativa)

Se la accendi (Impostazioni › Funzioni extra) e crei un account, i tuoi dati vanno anche sul server
della web app (Cloudflare), per averli uguali su più dispositivi:

- tutto viene **cifrato sul tuo dispositivo con la tua password** prima di partire (AES-256): il server
  conserva solo dati illeggibili e non conosce la password;
- sul server ci sono la tua **email**, un'impronta della chiave d'accesso (non la password) e i dati cifrati;
  le foto online sono una **copia ridotta**, anche lei cifrata;
- tema, lingua, funzioni extra e la chiave di Gemini **non** si sincronizzano;
- se dimentichi la password i dati online non si possono aprire, nemmeno da chi gestisce il server
  (quelli sul tuo dispositivo restano);
- da **Impostazioni › Sincronizzazione** puoi uscire da un dispositivo o **cancellare l'account**: con
  l'account si cancellano subito tutti i dati online.

## Quando l'app usa internet

Solo in questi casi, e solo con i dati indicati:

| Quando | Dove | Cosa viene inviato |
|---|---|---|
| Riconoscimento con Gemini (facoltativo, con la tua chiave) | Google (Gemini API) | La foto dell'oggetto che scegli di riconoscere; per l'assistente, la descrizione del viaggio e nomi e categorie degli oggetti (mai le foto) |
| Import da video con Gemini (facoltativo) | Google (Gemini API) | Il video che scegli; viene cancellato dopo l'analisi |
| Meteo (funzione extra) | Open-Meteo | Il nome della destinazione e le date del viaggio |
| Avviso di nuova versione (app Android, si può spegnere) | GitHub | Una richiesta anonima alla pagina pubblica delle versioni |
| Sincronizzazione online (funzione extra, con account) | Cloudflare (server della web app) | Email e dati cifrati sul dispositivo con la tua password, foto ridotte e cifrate |
| Scontorno nella web app | Il sito della web app | Il primo uso scarica il modello di scontorno (circa 44 MB); le foto restano nel browser |
| Scontorno su Android | Google Play Services | Il modello di scontorno di ML Kit si scarica sul telefono; le foto restano sul telefono |

La chiave di Gemini resta nel portachiavi sicuro del telefono e non finisce mai nei backup.
Con il piano gratuito di Gemini, fuori dall'Unione Europea Google può usare i contenuti inviati
per migliorare i suoi servizi: non fotografare documenti o dati personali con l'AI online.

## Permessi

- **Fotocamera e galleria:** per le foto degli oggetti.
- **Notifiche:** promemoria di viaggio (funzione extra) e avviso di nuova versione.
- **Internet:** solo per i casi elencati sopra.

## Cancellare i dati

Disinstalla l'app, oppure, per la web app, cancella i dati del sito dal browser.
Per i dati online: Impostazioni › Sincronizzazione › *Cancella account e dati online*.

## Contatti

Per domande apri una segnalazione nella pagina [Issues](https://github.com/Layaris/DMReleases/issues).
