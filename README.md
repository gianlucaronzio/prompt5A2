# Prompt per la maturità 2027

App web interattiva con 29 prompt per il docente di lettere di quinta liceo: prima prova, programma e lezioni, verifiche, colloquio orale, inclusione, ripasso, scrittura e lessico, organizzazione, motivazione.

Funziona con filtri per categoria, ricerca e pulsante "Copia". È un unico file HTML, senza dipendenze esterne né build.

## Pubblicazione su GitHub Pages

1. Crea un nuovo repository su GitHub (per esempio `prompt-maturita-2027`).
2. Carica `index.html` e `README.md` nella radice del repository.
3. Vai su **Settings → Pages**.
4. In **Build and deployment** scegli **Deploy from a branch**, branch `main`, cartella `/ (root)`, poi **Save**.
5. Dopo uno o due minuti il sito sarà online all'indirizzo `https://TUO-UTENTE.github.io/prompt-maturita-2027/`.

## Personalizzazione

I prompt sono nell'array `P` dentro `index.html`, nel formato `["Categoria","Titolo","Testo del prompt"]`. Le categorie sono nell'array `CATS`.
