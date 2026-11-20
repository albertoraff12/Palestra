# Allenamenti

App web per tenere traccia degli allenamenti: Scheda A, Scheda B, Scheda C, note e consigli.
Esercizi spuntabili e modificabili, ultimo carico per esercizio, timer dei recuperi.
Funziona offline e si installa sulla schermata Home dell’iPhone.

## Pubblicazione su GitHub Pages
1. Crea un nuovo repository (ad esempio `allenamenti`).
2. Carica nella radice del repository tutti i file di questa cartella: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png`.
3. Vai in Settings → Pages → Build and deployment → Source: *Deploy from a branch*, branch `main`, cartella `/ (root)`.
4. Dopo un minuto circa l’app è online su `https://<tuo-utente>.github.io/allenamenti/`.

## Installazione su iPhone
1. Apri l’indirizzo in Safari.
2. Tocca Condividi → *Aggiungi alla schermata Home*.
3. Usa l’app dall’icona: su iOS i dati dell’icona Home sono separati da quelli di Safari, quindi inserisci gli esercizi e i carichi solo da lì.

## Note
- I dati (spunte, carichi, note, modifiche alle schede) sono salvati nel browser del dispositivo (localStorage): non si sincronizzano tra dispositivi e si perdono se cancelli i dati del sito.
- Per aggiornare l’app dopo una modifica ai file, cambia il nome della cache in `sw.js` (`allenamenti-v1` → `allenamenti-v2`).
