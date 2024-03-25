1. Il programma dovrà chiedere all'utente il numero di chilometri che vuole percorrere e l'età del passeggero.
2. Sulla base di queste informazioni dovrà calcolare il prezzo totale del viaggio, secondo queste regole:
    - il prezzo del biglietto è definito in base ai km (0.21 € al km)
    - va applicato uno sconto del 20% per i minorenni
    - va applicato uno sconto del 40% per gli over 65.

1. INPUT
    - [x] Chiediamo all'utente il numero di chilometri che vuole percorrere tramite prompt
    - [x] Chiediamo all'utente la sua età tramite prompt
    - [x] Impostiamo la quota fissa di 0.21€ al km


2. . ESECUZIONE LOGICA
    - [x] Calcoliamo l'importo base che l'utente dovrà facendo la moltiplicazione tra il numero di kilometri selezionati e la quota fissa di euro al kilometro.
    - [x] Calcoliamo lo sconto in base alla fascia di età:
        - Se (l'età dell' utente è inferiore ai 18 anni)
            + calcoliamo lo sconto del 20% sull'importo base. (Questo valore verrà successivamente utilizzato per fare il calcolo dell'importo finale).
        - Altrimenti se (l'età dell'utente è compresa tra i 18 e i 65 anni)
            + Non verrà applicato nessuno sconto al prezzo finale
        - Altrimenti (l'età dell' utente supera i 65 anni)
            + calcoliamo lo sconto del 40% sull'importo base. (Questo valore verrà successivamente utilizzato per fare il calcolo dell'importo finale).
    - [x] Applichiamo lo sconto all'importo finale.
    - [x] Arrotondiamo l'importo finale a due cifre significative dopo la virgola.

3. OUTPUT
    - [x] Stampiamo il prezzo finale in base all' informazioni fornite da utente