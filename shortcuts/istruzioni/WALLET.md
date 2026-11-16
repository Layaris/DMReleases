# Wallet by BudgetBakers

## Due varianti, non da attivare insieme

- **Wallet Multivaluta EUR v5**: ultima versione preparata del flusso multivaluta, con lettura dell’importo originale, normalizzazione dei separatori, cambio verso EUR e registrazione nel conto Contanti.
- **Wallet Originale Fix**: variante vicina al comando originale. Corregge il valore passato all’azione di registrazione per usare importo e valuta invece dell’intero dizionario AI.

Sono conservate perché il proprietario aveva chiesto di provare entrambe. Nessuna va presentata come completamente collaudata su iPhone. Scegli una sola automazione attiva per le stesse app, per evitare registrazioni doppie.

## Prima della prova

1. Installa Wallet e verifica che il conto Contanti esista e sia in EUR; riassocia il conto nell’azione se necessario.
2. Importa il file firmato e collega il trigger alle app delle notifiche di pagamento desiderate.
3. Verifica disponibilità del modello e permessi di Wallet/rete. Controlla che il comando riceva il corpo della notifica.
4. Prova importi riconoscibili con virgole e punti. Il caso segnalato era `97,300.00 IDR`, che deve essere interpretato come 97300 IDR, non 973003. Altro esempio: `16,200.00 IDR` deve essere 16200 IDR.
5. Confronta la spesa registrata, il cambio e il numero di record. Le prove possono creare registrazioni reali: rimuovi personalmente quelle di test.

## Limiti dello stato attuale

Le v1–v4 della variante multivaluta hanno avuto problemi segnalati dall’utente. La v5 corregge il formato dei confronti numerici e tipizza il tasso; il successo completo sul telefono non è stato confermato. Le copie precedenti sono archiviate per confronto, non proposte come soluzione corrente.

Il progetto iniziale rimane nel repository privato `Layaris/wallet-shortcut-fix`. Questa cartella pubblica raccoglie i file firmati e i sorgenti correnti; non modifica quel repository né il conto Wallet.
