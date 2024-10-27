# Airbus ship detection

## Dreamteam2024 csapat
## Csapattagok: Horváth Dóra (F0B9YK), Kiss Blanka Zselyke (C6037J), Nyiri Balázs (REMAIO)

### Projekt leírása
A projekt célja műholdas képek alapján hajók szegmentálása. Az adatokat a Kaggle Airbus ship detection challenge oldaláról töltöttük le (kaggle.com/c/airbus-ship-detection). Rendelkezésünkre állnak a képek, valamint a hajók körüli bounding box-hoz tartozó maszkok rle kódolással.

### Fájlok
- DL_NHF.ipynb: Az adatok letöltése és előkészítése.
  
### Futtatás
A projektet lokálisan futtattuk Jupyter Notebook segítségével, mivel az adathalmaz túl nagy ahhoz, hogy megfelelően kezelhető legyen Colabban. Azonban a train-test-validation adathalmazok előkészítésekor a teljes adathalmaz betöltésénél a Jupyter Notebook memóriája is megtelt, így egy kisebb részét töltjük be az adatoknak, amíg nem találunk megfelelő erőforrásokkal rendelkező környezetet.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DL_NHF/DL_NHF.ipynb)
