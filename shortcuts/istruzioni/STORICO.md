# Storico del lavoro

Aggiornamento: 15 novembre 2026. Riassunto tecnico della lavorazione, senza credenziali o dati di notifiche personali.

## Wallet

Il progetto iniziale è stato recuperato e verificato nel repository privato `Layaris/wallet-shortcut-fix`. La firma su runner GitHub macOS richiedeva una sessione iCloud: la generazione da sola non produceva un file installabile firmato. Successivamente i file sono stati firmati con HubSign su autorizzazione del proprietario.

L’originale funzionava ma in alcuni casi alterava l’importo con separatori decimali/migliaia. Sono state preparate una variante vicina all’originale e una multivaluta EUR. Le revisioni hanno corretto serializzazione dei campi di testo, confronto della valuta, riferimenti circolari che perdevano il corpo della notifica e confronti numerici privi di valore visibile. La v5 usa valori letterali corretti e converte il tasso in Numero prima del confronto/calcolo. Il collaudo finale iPhone resta non confermato.

## Driver Grab/Gojek

I due comandi iCloud forniti erano identici e non si richiamavano. Alzavano Media tre volte e non ripristinavano il silenzioso. Il proprietario ha confermato iPhone 15 Pro Max, iOS 27 e Actions già installata.

| Versione | Lavoro svolto | Evidenza e limiti |
|---|---|---|
| v1 | Unico flusso, filtro per arrivo del passaggio/consegna, segnale audio, salvataggio e ripristino di silenzioso/Full immersion, Media e Suoneria al 100%. | Controlli locali; il proprietario ha riferito alcuni test riusciti e messaggi reali non riconosciuti. |
| v2 | Riconoscimento diretto di “Your food’s here!” e “Your food arrived on time”; solo frase vocale personalizzata, senza lettura della notifica. | 47 scenari locali; archivio firmato confrontato col sorgente. |
| v3 | Aggiunte le varianti “Your food arrived early/late”. | 57 scenari locali; archivio firmato confrontato col sorgente. |
| v4 | Aggiunta “Yay, your order came early! 😊”, anche con riga dell’orario. | 99 scenari locali complessivi; archivio firmato confrontato col sorgente. Test definitivo sul dispositivo non confermato. |

La suoneria torna al 50% fisso: non viene letto il livello precedente separato. Il ripristino di Media dipende dal valore fornito da iOS. La Full immersion viene riattivata per identità, non con la scadenza originaria. Un errore/interruzione può impedire il ripristino. Le schermate inviate sembravano Live Activities: un aggiornamento della scheda non dimostra che il trigger Notifica abbia ricevuto un evento. Le correzioni del testo non risolvono un eventuale mancato trigger.

## Ledgy — 15 novembre 2026

Ricevuto `build_shortcut.py` dal proprietario. Letto il codice, generato il workflow di 17 azioni e firmato con HubSign senza modificare il sorgente. Il workflow estratto dall’archivio restituito è identico a quello generato, domanda d’importazione compresa. Il risultato è `Ledgy.shortcut`; iPhone e server non sono stati collaudati.

## Pubblicazione — 15 novembre 2026

La cartella di lavoro locale non era un repository Git. Il proprietario ha chiesto una raccolta documentata con download e ha scelto il repository pubblico **Layaris/DMReleases**, dopo una prima preferenza per il repository privato. Sono stati separati pagina/download, istruzioni, sorgenti e verifiche. Il consenso alla pubblicazione include i file con frase personalizzata Driver e riferimento al conto Contanti; non vengono pubblicati indirizzi Ledgy personali.

La firma via HubSign è stata autorizzata dal proprietario; non rende il comando automaticamente funzionante, collaudato o sempre eseguibile in background.

## Selezione del 16 novembre 2026
Su richiesta del proprietario, nei download sono presenti soltanto le ultime versioni Ledgy e Driver Grab/Gojek v4. I file precedenti restano locali; le note Wallet sono conservate come storico, non come download corrente.
