# medicappbinet-sito

Sito statico di MediCappbinet! (IT/EN), sulla struttura del sito di AutOK. Nessuna build: `index.html`, `privacy.html`, `termini.html` e `assets/` (icona, favicon, PDF di Privacy e Termini).

## Pubblicazione (GitHub Pages)
1. Crea un repository (nome suggerito: `medicappbinet-sito`) e carica il contenuto di questa cartella nella radice (`.nojekyll` incluso).
2. Settings > Pages: sorgente = ramo principale, cartella radice.
3. Indirizzo delle norme sulla privacy da dare a Play Console: `https://<tuo-utente>.github.io/medicappbinet-sito/privacy.html` (Google Play non accetta un PDF).

## Cose da controllare prima di pubblicare
- I testi di Privacy e Termini sono la mia BOZZA, gli stessi dell'app (`res/raw` e `res/raw-en`): vanno fatti rivedere. Non sono una consulenza legale.
- Email di contatto e nome dello sviluppatore ("AVLAM App", `sviluppo.app.am@gmail.com`) presi dal sito di AutOK: confermare.
- Nessun badge/link di Google Play finche' l'app non e' pubblica ("In arrivo su Google Play").
- Non si dichiara che l'app e' gratuita: decisione ancora da prendere.
- Se cambiano le funzioni dell'app, aggiornare i blocchi della pagina principale. I font arrivano da Google Fonts (come nel sito di AutOK).

## Aggiornare i testi
Privacy e Termini esistono in tre posti da tenere uguali: nell'app (`res/raw*/privacy.txt`, `termini.txt`), nelle pagine `privacy.html`/`termini.html` e nei quattro PDF in `assets/` (si rifanno stampando le pagine in PDF dal browser).
