# Driver Grab Gojek v4

Correzione del 14 novembre 2026 per il messaggio Grab:

```
Yay, your order came early! 😊
On time · Arrived at 16:13
```

La prima riga, anche senza emoji o punto esclamativo, ora attiva direttamente l'avviso senza interrogare il modello. La seconda riga non ostacola il riconoscimento. Restano le regole dirette precedenti per "Your food’s here!" e "Your food arrived on time/early/late". Per altri testi resta il filtro AI precedente.

Vengono riprodotti il segnale iniziale e SOLO il messaggio personalizzato originale dell'utente. Il testo della notifica serve al filtro, ma non viene pronunciato. La gestione dei volumi, del silenzioso e della Full immersion è identica alla v3. La suoneria torna al 50% fisso, non al volume precedente misurato. Il ripristino richiede che l'esecuzione termini normalmente.

## Installazione e prova

1. Importa `Driver_Grab_Gojek_v4.shortcut` e disattiva le automazioni delle versioni precedenti, conservandole.
2. Aggiungi al nuovo comando il trigger "Quando ricevo una notifica da…" con Grab, Gojek e ntfy per le prove. Il servizio di firma rimuove i trigger incorporati.
3. Invia da ntfy il messaggio sopra. Provalo anche con la sola prima riga. Attendi il termine di ogni esecuzione.
4. Verifica il volume della frase e il ritorno allo stato precedente di silenzioso/Full immersion.

## Verifica

99 scenari locali di riconoscimento passati: 57 di regressione e 42 aggiunti per la nuova dicitura. Le risposte del modello e le azioni dispositivo sono simulate; le regex sono provate in Python, non su iOS. Il confronto con v3 conferma che cambiano soltanto il pattern e il nome della versione. Il rapporto `Driver_Grab_Gojek_v4_verifica.json` documenta il controllo del contenuto restituito da HubSign.

Non è un collaudo su iPhone. La modifica riconosce il testo SE viene consegnato al comando dal trigger: non trasforma gli aggiornamenti di una Live Activity in notifiche. Se il test ntfy passa ma la scheda reale non attiva l'avviso, occorre verificare separatamente il trigger dell'app e il testo effettivamente ricevuto.
