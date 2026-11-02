# Atlante Mineralogico

Sito web didattico su minerali e para-gemme: catalogo con oltre 100 campioni, schede tecniche,
confronto interattivo e visualizzazione 3D delle strutture cristalline (file CIF + three.js).

## Come usarlo

Nessuna installazione richiesta: scarica il progetto (**Code → Download ZIP**) oppure

```bash
git clone https://github.com/Ale11-tobi/atlante-mineralogico.git
```

e apri `index.html` nel browser. Per caricare correttamente i file CIF è consigliato un server locale:

```bash
npx serve .
```

## Struttura

- `index.html`, `styles.css`, `script.js` – il sito
- `assets/cif/` – strutture cristalline (Crystallography Open Database)
- `assets/images/` – immagini dei minerali (Wikimedia Commons)
- `assets/vendor/three.min.js` – three.js (licenza MIT)
- `tools/` – script per rigenerare le mappe di immagini e CIF

## Licenza

Codice rilasciato con licenza MIT (vedi `LICENSE`). Le immagini provengono da Wikimedia Commons e
i file CIF dal Crystallography Open Database: restano soggetti alle rispettive licenze.
