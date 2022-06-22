# Icon_Recruit_Restaurant
In questo progetto vogliamo predire il numero di visitatori in un ristorante.

Il risoratore dovrà fornire al sistema:
- meteo (pioggia e temperatura)
- giorno feriale/festivo
- situazione prenotazioni alberghi più vicini
- eventi 

Tenendo conto della distanza tra ristorante e prenotazioni degli alberghi vicini, si calcola una stima di probabili coperti.

Il meteo è composto da temperatura -> range di valori da 1 a 5 (molto bassa - molto alta)  e  pioggia -> valore booleano (0 - 1)
                        
Per quanto riguada gli eventi vi è un indicatore da 0 a 3 (nessun evento - evento poco importante - evento importante - evento molto importante) 


**COSE FATTE:**

- Classificatore con regressione lineare completato e funzionante
- Prendere temperatura e pioggia da database
- Chiedere all'utente gli altri parametri
- Implementata ricerca del grafo con BFS

**COSE DA FARE:**

- Fare restituire a BFS anche la distanza effettiva del percorso
- Verificare che BFS è un buon algoritmo
- Utilizzare prolog per vincoli ecc
- Implementare l'algoritmo di ricerca CSP
- Sistemare tutto

