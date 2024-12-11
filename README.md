`combineanalisis.ipynb` és un Jupyter Notebook dissenyat per a tasques d'anàlisi de dades i aprenentatge automàtic, amb un enfocament en la preprocessament, l'entrenament de models i l'avaluació. Utilitza biblioteques de Python per gestionar datasets, implementar diversos algoritmes d'aprenentatge automàtic i generar visualitzacions informatives.

## Funcionalitats

- **Preprocessament de dades**:
  - Gestiona dades mancants mitjançant tècniques com la imputació KNN.
  - Codifica variables categòriques utilitzant One-Hot Encoding.
  - Escala dades mitjançant tècniques d'estandardització.

- **Models d'aprenentatge automàtic**:
  - Implementa models de regressió com Regressió Lineal, Lasso, Ridge, ElasticNet i Random Forest
  - Admet algoritmes de classificació com Regressió Logística, SVM i Random Forest.
  - Utilitza SMOTE per sobremostrar datasets desbalancejats.

- **Avaluació de models**:
  - Calcula mètriques com R^2, precisió, recall, F1-score i log-loss.
  - Traça corbes ROC i de precisió-recall per a tasques de classificació.

- **Visualització**:
  - Utilitza Matplotlib i Seaborn per crear gràfics descriptius i informatius.

## Requisits previs

Assegura't de tenir instal·lades les següents dependències:

```bash
pip install pandas numpy statsmodels matplotlib seaborn scikit-learn imbalanced-learn
```

A més, necessites Python 3.7 o superior i Jupyter Notebook per executar el fitxer.

## Estructura

- **Celes de codi**: Executen tasques específiques, com importar biblioteques, processar dades, entrenar models i generar avaluacions.
- **Celes de markdown**: Proporcionen explicacions sobre passos de preprocessament, decisions preses i idees clau derivades de l'anàlisi.

## Instruccions d'ús

1. **Configuració**:
   - Clona el repositori o descarrega el fitxer `combineanalisis.ipynb`.
   - Instal·la les dependències necessàries indicades als requisits previs.

2. **Executa el Notebook**:
   - Obre el notebook amb Jupyter Notebook o Jupyter Lab.
   - Executa cada cela seqüencialment per realitzar el preprocessament de dades, l'entrenament de models i l'avaluació.

3. **Dades d'entrada**:
   - Modifica el notebook per carregar el teu dataset (per exemple, un fitxer CSV o Excel).
   - Ajusta els passos de preprocessament segons les necessitats del teu dataset.

4. **Visualitzacions**:
   - Inspecciona els gràfics generats al notebook per obtenir idees sobre les dades i el rendiment del model.

## Notes

- El notebook assumeix un coneixement bàsic de programació en Python i de conceptes d'aprenentatge automàtic.
- Modifica els hiperparàmetres dels models d'aprenentatge automàtic per optimitzar el rendiment per al teu dataset.
- Per a datasets desbalancejats, el notebook utilitza SMOTE per equilibrar les classes de manera efectiva.


