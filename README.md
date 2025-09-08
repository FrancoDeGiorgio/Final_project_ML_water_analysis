# Final_project_ML_water_analysis
 Modello predittivo di machine learning, capace di fornire previsioni accurate a partire dai dati esplorati.


# Sommario del Progetto

Ecco un riepilogo dei passaggi chiave del progetto:

* [1. Introduzione](#1.-Itroduzione)
* [2. Caricamento Dati e Analisi Preliminare](#2.-Caricamento-Dati-e-Analisi-Preliminare)
* [3. Suddivisione del Dataframe](#3.-Suddivisione-del-Dataframe)
* [4. Analisi Esplorativa dei Dati (EDA)](#4.-Analisi-Esplorativa-dei-Dati-(EDA))
* [5. Gestione dei Valori Mancanti](#5.-Gestione-dei-Valori-Mancanti)
* [6. Test di Ipotesi](#6.-Test-di-Ipotesi)
* [7. Test Modelli Base](#7.-Test-Modelli-Base)
* [8. Tuning Modelli Selezionati con GridSearchCV](#8.-Tuning-Modelli-Selezionati-con-GridSearchCV)
* [9. Valutazione Finale sul Set di Test](#9.-Valutazione-Finale-sul-Set-di-Test)
* [10. Analisi Finale e Conclusioni](#10.-Analisi-Finale-e-Conclusioni)


## Introduzione
Realizzare per un’azienda specializzata in  tecnologie per il monitoraggio ambientale e la tutela delle risorse idriche un modello predittivo di machine learning, capace di fornire previsioni
accurate a partire dai dati esplorati. L’azienda collabora con enti pubblici e privati per garantire l’accesso a un’acqua pulita e sicura.

| Colonna          | Descrizione                                                                 |
|------------------|------------------------------------------------------------------------------|
| **Unità di misura** | **ppm = parti per milione · μg/L = microgrammi per litro · mg/L = milligrammi per litro** |
| ph               | pH dell’acqua (da 0 a 14).                                                   |
| Hardness         | Capacità dell’acqua di precipitare il sapone (mg/L).                         |
| Solids           | Solidi totali disciolti (ppm).                                               |
| Chloramines      | Quantità di clorammine (ppm).                                                |
| Sulfate          | Quantità di solfati disciolti (mg/L).                                        |
| Conductivity     | Conducibilità elettrica dell’acqua (μS/cm).                                  |
| Organic_carbon   | Quantità di carbonio organico (ppm).                                         |
| Trihalomethanes  | Quantità di trialometani (μg/L).                                             |
| Turbidity        | Misura della proprietà di emissione della luce dell’acqua (NTU).             |
| Potability       | Indica se l’acqua è potabile (1 = potabile, 0 = non potabile).               |
