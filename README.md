=====================================================
 Progetto Farfalle - Visualizzazione Dati con D3.js
=====================================================

Autore: Alessio Prete 533010
Corso: Visualizzazione Delle Informazioni - Laurea Magistrale Ingegneria Informatica - Università degli studi Roma Tre
 
---

## Descrizione del Progetto

Questo progetto utilizza la libreria JavaScript D3.js per creare una visualizzazione interattiva di un dataset multivariato. Il dataset è composto da 8 data-case, ognuno con 5 variabili quantitative positive.

Ogni caso è rappresentato visivamente da una farfalla, le cui proprietà (posizione X, posizione Y, grandezza di ali, testa,  addome) sono mappate dinamicamente alle 5 variabili dei dati.

Per qualsiasi dettagli tecnico si rimanda all'analisi tecnica contenuta nella cartella del progetto.

---

## Come Avviare il Progetto

Se si dovessero avere problemi ad aprire semplicemente il file html, per visualizzare correttamente il progetto, è fondamentale eseguirlo tramite un **server web locale**.

**Motivo:** Il codice JavaScript (`script.js`) deve caricare il file `data.json`. I browser moderni, per motivi di sicurezza (per es. politica CORS), bloccano queste richieste se la pagina viene aperta direttamente dal file system (con un indirizzo `file:///...`). Quindi se si apre normalmente il file "index.html" non funzionerà bene l'interfaccia.

**Metodo Consigliato (con Visual Studio Code):**
1. Installare l'estensione "Live Server".
2. Aprire la cartella del progetto in VS Code.
3. Aperta la cartella di progetto, fare click sul tasto in basso "Go Live".

In alternativa ho caricato direttamente il file di progetto su un server web, accessibile al seguente indirizzo: https://progetto-farfalle.netlify.app/
