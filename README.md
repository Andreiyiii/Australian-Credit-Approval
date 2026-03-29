# Proiect AI - Australian Credit Approval

Acest proiect analizeaza si modeleaza setul de date **Australian Credit Approval (UCI)** pentru o problema de clasificare binara:

- `0` = cerere respinsa
- `1` = cerere aprobata

Scopul este intelegerea datelor si construirea unui flux de lucru complet de tip:

1. analiza exploratorie (EDA)
2. pregatirea datelor
3. modelare si evaluare

## Structura proiectului

- `analiza_date.ipynb` - notebook pentru analiza si intelegerea setului de date
- `australian.dat` - fisierul de date folosit in notebook-uri
- `australian.doc` - descrierea atributelor din dataset
- `requirements.txt` - dependinte Python


## Ce include analiza (`analiza_date.ipynb`)

- incarcare si inspectie initiala a datasetului
- distributia claselor pentru `A15`
- verificarea valorilor lipsa si a duplicatelor
- statistici descriptive pentru trasaturi numerice
- detectie outlieri (IQR)
- analiza corelatiilor cu targetul
- vizualizari pentru trasaturile cele mai informative

## Date si sursa

Dataset: **Statlog (Australian Credit Approval)**  
Sursa oficiala UCI: https://archive.ics.uci.edu/ml/datasets/Statlog+%28Australian+Credit+Approval%29


