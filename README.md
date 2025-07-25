# 🍭 Diabetes Prediction using Machine Learning
Progetto volto a predire la presenza di diabete di tipo 2 basandosi su dati clinico‑demografici, con modelli di machine learning.
## Obiettivo
Realizzare un modello in grado di classificare se un individuo sia affetto da diabete oppure no, usando il dataset Pima Indians Diabetes dal repository UCI. L'approccio include esplorazione dati, preprocessamento, addestramento di diversi algoritmi e confronto delle performance.
## Dataset
Il dataset utilizzato è il Pima Indians Diabetes compreso nel repository: composto da dati quali numero di gravidanze, glicemia, pressione sanguigna, spessore cutaneo (SkinThickness), livello di insulina, BMI, funzione ereditaria del diabete (DiabetesPedigreeFunction), età e una variabile di output (`Outcome`) binaria (1 = positivo per diabete, 0 = negativo). Questi dati sono impiegati per costruire e validare i modelli predittivi.
## Risultati
Il modello migliore è stato selezionato in base alla combinazione di accuratezza e capacità di generalizzazione su dati non visti (test set). Ad esempio, un modello come XGBoost o Random Forest ha spesso mostrato performance elevate (~0.80–0.85 di accuratezza) e robustezza rispetto ai dati sbilanciati.
## Tecnologie
Utilizzo delle seguenti librerie Python principali:
- `pandas`, `numpy` per manipolazione dati  
- `matplotlib`, `seaborn` per visualizzazioni  
- `scikit-learn` per modelli di classificazione
## Autore
[Gaglione Giulia](https://github.com/giug2)
