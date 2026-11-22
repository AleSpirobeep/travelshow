# Travel Show

Un sito per ogni viaggio. La home (`index.html`) è la vetrina; ogni viaggio vive nella sua cartella,
statico e senza build: si apre `index.html` e funziona.

```
index.html   → la vetrina dei viaggi
lapponia/    → Lapponia, 3–9 dicembre 2026 (programma, luoghi, checklist, mappe)
```

Online: <https://alespirobeep.github.io/travelshow/>

## Aggiungere un viaggio

1. Copiare la cartella di un viaggio esistente (per esempio `lapponia/`) con un nuovo nome.
2. Riscrivere `js/data.js` (LUOGHI, GIORNI, CHECKLIST) e i testi delle quattro pagine.
3. Aggiungere la card nella vetrina `index.html`.

## GitHub Pages

Da **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*,
Branch = `main`, cartella `/ (root)` → **Save**. Dopo circa un minuto il sito è online.
