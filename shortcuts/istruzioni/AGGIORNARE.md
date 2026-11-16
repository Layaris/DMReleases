# Aggiornare questa raccolta

## Destinazione e organizzazione

Repository di pubblicazione: **Layaris/DMReleases**, pubblico. Pagina: `docs/shortcuts/index.html` → `https://layaris.github.io/DMReleases/shortcuts/`.

- `docs/shortcuts/downloads/`: file firmati correnti.
- `docs/shortcuts/downloads/archivio/`: versioni superate, chiaramente etichettate.
- `shortcuts/istruzioni/`: spiegazioni e storico; tenere qui i nuovi documenti.
- `shortcuts/sorgenti/`: workflow non firmati e generatori.
- `shortcuts/verifiche/`: manifest e rapporti; aggiornare gli SHA-256 dopo ogni nuova firma.

## Procedura per una nuova versione

1. Leggere la richiesta corrente, lo storico e il sorgente esatto della versione in uso. Conservare i file originali e le versioni pubblicate.
2. Modificare soltanto il comportamento richiesto. Verificare riferimenti delle variabili, blocchi condizionali, parametri obbligatori e assenza di richieste manuali indesiderate. Per i messaggi, usare il testo esatto fornito e includere prove negative per ritiro al ristorante e arrivo futuro.
3. Generare il file non firmato. Per Ledgy: `python shortcuts/sorgenti/ledgy/build_shortcut.py build/ledgy`. Lo script produce un `.shortcut` non firmato e un plist XML, non un file già installabile.
4. Per la firma, utilizzare il metodo autorizzato dal proprietario. HubSign riceve il contenuto del workflow: controllare che non contenga token, password, URL privati o notifiche reali. Non effettuare upload automatici come effetto collaterale di una modifica alla documentazione.
5. Verificare il file ricevuto: formato AEA, payload estraibile, confronto delle azioni/parametri con il sorgente, domanda d’importazione se presente e SHA-256. Documentare gli eventuali metadati eliminati dal servizio, soprattutto i trigger. Questo controllo non sostituisce la validazione crittografica completa o una prova su iPhone.
6. Pubblicare il nuovo file con nome/versione distinti. Spostare il precedente in archivio e aggiornare pagina, indice, guida, storico, sorgente e manifest. Non cambiare gli altri progetti di DMReleases, in particolare Multifolio.
7. Verificare i link locali e poi quelli pubblici. Scaricare nuovamente il file dal sito e confrontare SHA-256. Verificare che il commit abbia toccato solo i percorsi previsti e che GitHub Pages abbia pubblicato la nuova pagina.
8. Chiedere il risultato del test sul telefono e riportarlo come prova dell’utente, distinguendolo dai controlli locali. Se il test fallisce, conservare il testo esatto e l’azione che mostra l’errore, evitando notifiche o dati privati nel repository pubblico.

La raccolta non si sincronizza da sola con il PC: ogni nuova versione richiede un commit e l’aggiornamento di questa documentazione. Non scrivere “testato su iPhone” senza un risultato verificato/riferito e circoscritto.
