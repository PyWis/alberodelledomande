# L'albero delle domande

Quiz a scelta multipla per **qualsiasi materia**: ogni risposta giusta aggiunge un addobbo all'albero 3D e l'ultima mette la stella in cima. È una sola pagina (`index.html`), non serve installare niente: si apre nel browser o si pubblica con GitHub Pages.

## Per l'insegnante

Apri **Pannello insegnante**:

- **Raccolte** – crea più raccolte di domande (una per materia o per classe), importale da CSV, duplicale, scegli con quale giocare. Tutto resta salvato nel browser.
- **Domande** – aggiungi, modifica, riordina ed elimina le domande direttamente nella pagina, oppure modificale tutte insieme come testo (puoi incollarle da Excel o da Fogli Google). Esporta la raccolta in CSV.
- **Impostazioni** – titolo e sottotitolo del gioco, quante risposte giuste servono per vincere (5–50), quanti errori sono concessi (0 = nessun limite), tema dell'albero (Natale, Primavera, Spazio), ordine delle domande, risposte mescolate o no.
- **Condividi** – crea un link che contiene la raccolta: gli studenti lo aprono e giocano subito, anche con il pannello insegnante nascosto. In alternativa collega un foglio Google pubblicato come CSV: il link leggerà sempre la versione aggiornata.

## Formato CSV

Una domanda per riga, colonne separate da `;`, `,` o tabulazione:

```
domanda;risposta_giusta;sbagliata_1;sbagliata_2;sbagliata_3;spiegazione
```

Serve almeno una risposta sbagliata; la spiegazione è facoltativa. Con la riga d'intestazione si possono aggiungere altre colonne `sbagliata_4`, `sbagliata_5`… Vedi `domande-esempio.csv`.

## Per gli studenti

Si risponde con un clic o con i tasti `1`, `2`, `3`… A fine partita compare l'elenco delle domande sbagliate, con la risposta giusta, da ripassare.
