# Guida a Sigla

[← Torna a Sigla](README.md)

## 1. Primo avvio

Apri l'app: non serve nessun account. In basso (o a sinistra su tablet e computer) ci sono quattro
sezioni: **Documenti**, **Firme**, **Profilo** e **Impostazioni**.

Consiglio: prima crea la firma e compila il profilo, poi apri i documenti.

## 2. Firme e sigle

Nella sezione **Firme** tocca **Nuova firma** (oppure **Nuova sigla** per le iniziali) e scegli come crearla:

- **Disegna**: firma nel riquadro con il dito, lo stilo o il mouse. Scegli blu o nero e lo spessore.
  Con **Annulla** e **Ripeti** correggi l'ultimo tratto; **Cancella** ricomincia (si può annullare).
  Con Apple Pencil o uno stilo il tratto segue la pressione.
- **Importa da foto** o **da file**: firma su un foglio bianco con una penna scura e fotografa con buona luce.
  L'app toglie lo sfondo da sola. Se la firma è troppo chiara sposta **Soglia** a destra, se resta lo sfondo
  spostala a sinistra; **Automatica** torna al valore calcolato. Puoi ricolorare la firma in blu o nero.
- **Scatta una foto** (Android e iPhone): come sopra, direttamente dalla fotocamera.
- **Scrivi**: digita il nome e diventa una firma in corsivo.

Ogni firma ha un nome. Dal menu **⋮** della firma puoi **Rinominare**, **Impostare come predefinita** o
**Eliminare**. La predefinita è quella usata dalla compilazione automatica e da *Sigla tutte*.

## 3. Profilo

Nella sezione **Profilo** inserisci i dati che scrivi spesso nei moduli: nome, cognome, data e luogo di
nascita, codice fiscale, indirizzo, CAP, città, provincia, telefono, email. Con **Aggiungi un dato** puoi
salvare anche altro (per esempio il numero della patente). Si salva da solo mentre scrivi.

## 4. Aprire un documento

Nella sezione **Documenti**:

- **Apri PDF**: scegli un file dal dispositivo.
- **Scansiona documento** (Android e iPhone): fotografa le pagine, l'app raddrizza la prospettiva e crea il PDF.
- **Da immagini**: scegli una o più foto e diventano un PDF (una pagina per immagine).
- Su Android puoi anche aprire un PDF da un'altra app con **Apri con › Sigla** o **Condividi › Sigla**.

## 5. Firmare e compilare

Nell'editor la barra in basso contiene gli strumenti (su telefono scorre di lato):

| Strumento | Cosa fa |
|---|---|
| **Firma** / **Sigla** | Inserisce una firma o una sigla salvata (se ne hai più di una, la scegli) |
| **Testo** | Inserisce un testo libero |
| **Data** | Inserisce la data di oggi (gg/mm/aaaa) |
| **Spunta** / **Croce** | Inseriscono ✓ e ✗ |
| **Sigla tutte** | Mette la sigla predefinita in basso a destra su ogni pagina |
| **Campi** | Compila i campi dei PDF compilabili (compare solo se il PDF ne ha) |
| **Compila** | Trova i campi del modulo e propone i dati del profilo |
| **Dati profilo** | Inserisce un dato del profilo come testo |

- **Trascina** un elemento per spostarlo; il cerchio in basso a destra lo **ridimensiona**; la **×** rossa lo elimina.
- Con un elemento selezionato compaiono **Modifica** (testi), **Blu**/**Nero**, **Su tutte** (copia
  l'elemento su tutte le pagine) ed **Elimina**. Tocca un punto vuoto o **Fatto** per deselezionare.
- **Annulla** e **Ripeti** in alto annullano qualsiasi modifica. Con − e + cambi lo zoom.

### Compilazione automatica

Tocca **Compila**. L'app cerca etichette come *Nome*, *Cognome*, *nato/a a … il …*, *Codice fiscale*,
*Residente in*, *Via*, *CAP*, *Telefono*, *Email*, *Luogo e data*, *Firma* e lo spazio vuoto accanto
(linee ____, puntini, spazio dopo i due punti o sotto l'etichetta). Poi mostra i **Campi trovati** con
i valori proposti: correggi quello che serve, togli la spunta a quello che non vuoi e tocca **Inserisci**.
Niente viene inserito senza la tua conferma, e dopo puoi comunque spostare o eliminare ogni testo.

Con i **PDF compilabili** (moduli con caselle già pronte) tocca **Campi › Dal profilo**: si compilano i campi
vuoti che l'app riconosce dal nome.

### Riconoscimento AI (facoltativo)

Se un PDF è una scansione (solo immagini, senza testo) la ricerca sul dispositivo non trova nulla. Puoi attivare
il riconoscimento AI in **Impostazioni › Riconoscimento AI** con una tua chiave API di Anthropic. Quando tocchi
**Compila** l'app chiede se cercare **sul dispositivo** o con l'**AI avanzata**: con l'AI le pagine vengono
inviate come immagini ad Anthropic. Il modello predefinito è `claude-haiku-5-5` e si può cambiare.

## 6. Esportare

Tocca **Esporta PDF**. Firme, testi e campi diventano parte del documento e non sono più modificabili.
Poi scegli **Salva** (sul computer parte il download) oppure **Condividi**. Il nuovo file si chiama come
l'originale con `_firmato` alla fine; l'originale non viene toccato.

## 7. Backup

In **Impostazioni › Backup**:

- **Esporta backup** crea un file `.sigla` con firme, profilo e impostazioni, protetto da una password
  (almeno 8 caratteri). **Conserva la password**: senza non si può aprire.
- **Importa backup**: scegli il file, poi **Unisci** (aggiunge le firme che mancano e completa i campi
  vuoti del profilo) o **Sostituisci** (usa solo i dati del backup).

La chiave API dell'AI non va nel backup.

## 8. Sicurezza

**Impostazioni › Sicurezza › Blocca le firme** chiede impronta, Face ID o il PIN del telefono per vedere e
usare le firme. Si richiude quando esci dall'app. Nel browser non è disponibile.

## Domande frequenti

| Problema | Cosa fare |
|---|---|
| **La firma importata ha ancora lo sfondo** | Sposta la soglia a sinistra, oppure rifotografa su carta bianca con più luce. |
| **La firma importata è a pezzi** | Sposta la soglia a destra. |
| **"Nessun campo riconosciuto"** | Il PDF è probabilmente una scansione: usa il riconoscimento AI o aggiungi i testi a mano. |
| **Il PDF non si apre** | Se è protetto da password, rimuovi la protezione e riprova. |
| **"Password errata o file danneggiato"** | Controlla la password del backup (maiuscole comprese). |
| **Il testo inserito ha un simbolo "?"** | Alcuni caratteri speciali non sono disponibili nel font del PDF e vengono sostituiti. |

La firma grafica di Sigla è una **firma elettronica semplice** (eIDAS): va bene per moduli, ricevute e
documenti di tutti i giorni, non per gli atti che richiedono una firma digitale qualificata.
