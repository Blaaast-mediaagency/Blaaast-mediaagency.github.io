# BLAAAST — Sito web

Sito dell'agenzia di comunicazione BLAAAST, ospitato su GitHub Pages con dominio custom `blaaast.it`.

## Struttura

```
├── index.html      # Home page
├── css/style.css   # Design system e stili
├── js/main.js      # Interazioni (menu, reveal, header)
├── favicon.svg     # Favicon
├── assets/         # Immagini (vuoto per ora)
└── CNAME           # Dominio custom
```

## Tecnologie

Sito statico puro: HTML5, CSS3 e JavaScript vanilla. Nessun framework,
nessun build step. Deploy diretto su GitHub Pages.

## Come personalizzare

- **Testi**: modifica i contenuti direttamente in `index.html`
- **Colori e font**: le variabili CSS sono in cima a `css/style.css` (sezione `:root`)
- **Contatti**: sostituisci email e telefono placeholder in `index.html`
- **Lavori**: le card nella sezione "Selected work" hanno immagini segnaposto
  colorate; sostituiscile con immagini reali in `assets/`
- **Footer**: aggiorna P.IVA e link social

## Deploy

Il sito si aggiorna automaticamente a ogni `git push` sul ramo di pubblicazione
di GitHub Pages.
