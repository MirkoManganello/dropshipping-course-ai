# Corso — Da zero a 1K con lo store AI

Corso pratico in **16 moduli** sul dropshipping assistito da AI, con un **calcolatore di profittabilità interattivo**. È un sito statico a pagina singola: nessun build, nessuna dipendenza, tutto in un unico `index.html`.

Il materiale è stato **ricostruito da due video** e riorganizzato in moduli didattici, con un **reality check** critico che distingue il metodo reale dal marketing.

- **Parte 1 · Metodo veloce** (moduli 00–08): store con AI builder, prodotto virale, TikTok Ads.
- **Parte 2 · Metodo avanzato** (moduli 09–15): deep research, tema custom, conversione, calcolo dei margini.
- **Strumento**: calcolatore break-even (CPA, ROAS, CPC) e target al margine desiderato.

> ⚠️ **Nota.** Contenuto a scopo **educativo**. Nessun risultato economico è garantito. Alcune tecniche citate nei video-fonte (riuso di video altrui, "scarsità finta") comportano rischi legali: vedi la sezione *Reality check* nella pagina.

## Anteprima in locale

È solo HTML, quindi puoi aprire `index.html` con doppio clic. Per servirlo come farebbe il web:

```bash
# Python 3
python -m http.server 8000
# poi apri http://localhost:8000
```

## Deploy su GitHub Pages

Il repo include un workflow (`.github/workflows/deploy.yml`) che pubblica automaticamente il sito a ogni push su `main`.

1. Crea un repository vuoto su GitHub (senza README/licenza, così non vai in conflitto).
2. Collega e fai push (vedi i comandi che ti sono stati forniti).
3. Su GitHub: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. Dopo il primo push, il sito è online su `https://<tuo-utente>.github.io/<nome-repo>/`.

## Struttura

```
.
├── index.html                  # il corso completo (pagina singola)
├── README.md
├── LICENSE
└── .github/workflows/deploy.yml
```

## Licenza

[MIT](LICENSE) per il codice del sito. I contenuti didattici sono una rielaborazione a fini educativi.
