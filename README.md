# Modelització de sistemes electorals amb cadenes de Markov

Projecte sobre cadenes de Markov per a l’assignatura de Modelització i Simulació.

### Organització del repositori

- `dataset/*`  
  Dades originals descarregades directament d’[IDESCAT](https://www.idescat.cat/pub/?id=elepc&n=6011&t=202400), corresponents als resultats electorals a Catalunya de l'any 1980 al 2024.

- `data_processing.ipynb`  
  Notebook de preprocessament i transformació de les dades. Inclou neteja, agregació de partits i construcció del conjunt de dades final.

- `data.csv`  
  Dades processades en format tabular, amb els partits com a variables i els anys electorals com a observacions.

- `main.ipynb`  
  Anàlisi principal basada en cadenes de Markov per a la modelització de l’evolució temporal del sistema electoral.

## Resultats