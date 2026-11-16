# Ledgy

## Che cosa contiene

Il file firmato deriva senza modifiche dallo script `sorgenti/ledgy/build_shortcut.py` fornito dal proprietario. Ha 17 azioni. Legge titolo, sottotitolo e corpo della notifica, chiede al modello un dizionario con importo, valuta, esercente e categoria e invia questi dati in JSON al server configurato. La conversione, la deduplicazione e le regole dipendono dal server Ledgy, che non è incluso nella raccolta.

Il flusso contiene un ramo destinato al ping giornaliero `/ping` quando non riceve notifiche e un avviso quando il server restituisce lo stato `review`. Questi rami descrivono l’intento dello script, non un risultato collaudato sul telefono.

## Installazione

1. Scarica `Ledgy.shortcut` dalla pagina della raccolta e aprilo sull’iPhone.
2. Alla domanda d’importazione inserisci l’indirizzo personale indicato in Ledgy → Altro → Cattura automatica → Collega un telefono. Il file distribuito contiene soltanto un segnaposto.
3. Configura le app delle notifiche di pagamento nel trigger di Comandi Rapidi e verifica i permessi del modello e di rete.
4. Prova una notifica nota e controlla nel server importo originale, valuta, conversione e duplicati. Verifica separatamente il ping senza input prima di usarlo con un trigger giornaliero.

## Firma e controllo

Firmato con HubSign il 15 novembre 2026 su richiesta del proprietario. Archivio AEA e catena certificati ispezionati; il payload decodificato è identico all’intero workflow generato, incluse le 17 azioni e la domanda d’importazione. Non è stata fatta una verifica crittografica completa della firma. Non eseguito su iPhone e non provato contro un server Ledgy.

La firma non corregge il codice: in questo incarico è stato firmato lo script fornito, non riscritto. Il modello selezionato e le condizioni devono essere validati sul dispositivo prima di affidargli dati reali. Il corpo originale della notifica viene inviato al proprio server insieme ai campi estratti.
