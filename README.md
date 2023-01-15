# DiagClassifier

Per l'esecuzione di questo progetto, è necessario installare i seguenti componenti,
utilizzando la procedura adeguata a seconda dell'ambiente con cui si sta lavorando
(quindi pip, conda ecc.):

#### CLASSIFICATION:
- sklearn
- numpy
- pandas
- matplotlib

#### DATASET MANAGER:
- seaborn
- tensorflow
- keras

#### OPENCV:
- cv2

I file notAugmentedDataset.csv, augmentedDataset.csv e CNNFeatureExtraction.csv sono i dataset per la classificazione, la cui generazione è affidata al dataset_manager.ipynb. Altri file csv presenti rappresentano versioni precedenti del dataset i cui dettagli sono reperibili all' interno del codice stesso.

Il notebook openCV.ipynb gestisce la segmentazione delle fotografie presenti nel dataset.

Tutti gli esperimenti di classificazione sono stati effettuati nel notebook Classification.ipynb.

Inoltre, il codice viene rilasciato in formato Jupyter Notebook (.ipynb), quindi è
necessaria anche l'integrazione con Jupyter per la corretta esecuzione cella per cella.
Una volta aperti i notebook in Jupyter, basterà lanciare l'esecuzione per ottenere i risultati.
