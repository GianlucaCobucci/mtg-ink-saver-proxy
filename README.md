# MTG Ink-Saver Proxy

Genera un PDF A4 (9 carte/pagina, 63x88 mm) di proxy Magic in bianco e nero a basso consumo di inchiostro:
riquadro illustrazione vuoto e costo di mana con i simboli (da Scryfall) in bianco e nero.

Apri `index.html` (o la pagina GitHub Pages), incolla la decklist e premi "Genera PDF".

## Dimensioni di stampa
Stampa sempre al 100% / "Dimensioni reali" (non "Adatta alla pagina"). Se le carte escono comunque un po' più piccole,
usa il pulsante "Pagina di calibrazione", misura la linea di 100 mm e inserisci nel campo "Scala di stampa" il valore 10000 / X.
La pagina funziona senza CDN: jsPDF e i simboli di mana sono inclusi nella cartella; serve internet solo per Scryfall.
