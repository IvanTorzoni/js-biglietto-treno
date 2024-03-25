1. Il programma dovrà chiedere all'utente il numero di chilometri che vuole percorrere e l'età del passeggero.
2. Sulla base di queste informazioni dovrà calcolare il prezzo totale del viaggio, secondo queste regole:
    - il prezzo del biglietto è definito in base ai km (0.21 € al km)
    - va applicato uno sconto del 20% per i minorenni
    - va applicato uno sconto del 40% per gli over 65.

1. INPUT
    - [x] Chiediamo all'utente il numero di chilometri che vuole percorrere tramite prompt
    - [x] Chiediamo all'utente la sua età tramite prompt
    - [x] Impostiamo la quota fissa di 0.21€ al km


2. ESECUZIONE LOGICA
    - [ ] Impostiamo i range di età per gli utenti (da 0 a meno di 18 anni, da anni uguali o superiori ai 18 e da anni minori di 65 anni, da anni pari o superiori ai 65 anni) 
    - [ ] Calcoliamo i soldi che l'utente dovrà dare, sulla base dei km selezionati
    - [ ] Calcoliamo lo sconto degli utenti minorenni e degli utenti anziani
    - [ ] Applichiamo lo sconto degli utenti minorenni e degli utenti anziani
    - [ ] Arrotondiamo il costo finale a due cifre significative dopo la virgola

    - Se (l'età dell' utente è inferiore ai 18 anni)
        + calcolerà i soldi che dovrà pagare in base ai km
        + calcolerà lo sconto del 20%
        + esegue la sottrazione dello sconto al prezzo totale
        + arrotonderà il prezzo totale a due cifre significative
    - Altrimenti se (l'età dell' utente è di anni pari e superiori a 18 fino ad anni inferiori ai 65)
        + calcolerà i soldi che dovrà pagare in base ai km
        + arrotonderà il prezzo totale a due cifre significative
    - Altrimenti (l'età dell' utente supera i 65 anni)
        + calcolerà i soldi che dovrà pagare in base ai km
        + calcolerà lo sconto del 40%
        + esegue la sottrazione dello sconto al prezzo totale
        + arrotonderà il prezzo totale a due cifre significative

3. OUTPUT
    - [ ] Stampiamo il prezzo finale in base all' informazioni fornite da utente