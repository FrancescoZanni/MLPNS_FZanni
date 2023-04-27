Il grafico originale è preso da una relazione svolta per il corso "Laboratorio di fisica computazionale".  
Per dare contesto la relazione tratta di una stima dell'energia del livello fondamentale per sistemi con potenziale armonico, anarmonico e a doppia buca. Il grafico si riferisce al potenziale a doppia buca e mostra risultati ottenuti per diversi valori di un parametro $\lambda$.  

![image](https://github.com/FrancescoZanni/MLPNS_FZanni/blob/main/vis/E0DW.PNG)

Il grafico è stto migliorato sotto diversi aspetti: 
![image](https://github.com/FrancescoZanni/MLPNS_FZanni/blob/main/vis/E0remade.png)


Il problema principale era nel'utilizzo degli elementi grafici, le modifiche sono le seguenti
- Non era presente corrispondenza di colori tra i punti relativi alla simulazione e la linea di fit
- Non c'era continuità di scelta all'interno delle linee di fit (una risultava trattetggiata al contrario di tutte le altre)
- L'utilizzo di un plot con le barre di errore per i dati simulati era superfluo e risultava ambiguo: l'errore, relativo all'asse verticale, è troppo piccolo per la scala del grafico: di conseguenza la barra di errore non è visibile, se ne osservano soltanto i limitatori superiore e inferiore, che sembrano coincidere e fanno supporre che l'errore sia al contrario sull'asse x. Questo elemento è quindi fonte di ambiguità ed è stato rimosso in quanto non porta informazioni rilevanti
- Nella legenda è stato affiancato ogni fit ai relativi dati
- È stata rimossa la griglia, che appensantisce la visualizzazione e non porta beneficio
- È stata inserita una didascalia, che chiarisce il contesto e le informazioni da trarre dal grafico
- Sono stati modificati i tick sull'asse y, essendo il calcolo dell'intercetta l'obiettivo del fit si inserisce come tick il risultato ottenuto per ciascun fit 
- È stato scelto un set di colori che fosse compatibile con ogni tipo di daltonismo
- È stata aumentata la trasparenza delle linee di fit, in questo modo si dà maggiore importanza visiva ai punti ottenuti tramite simulazione.  



(Il codice è quello utilizzato per ottenere il grafico migliorato, non so perchè ma gitHub non mostra il risultato, che tuttavia è esattamente quello mostrato in questo README)



