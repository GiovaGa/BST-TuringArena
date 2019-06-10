#Mantenimento dinamico del valore massimo attuale:


Devi mantenere un insieme di numeri interi. L'insieme è inizialmente vuoto,
e dovrai gestire una sequenza di inserimenti od eliminazioni di valori interi nell'insieme.
Sempre nel dinamico, dovrai inoltre gestire due tipi di query:
1. dato un intero, stabilire se esso sia attualmente presente nell'insieme;
2. conoscere quale sia il massimo valore intero attualmente presente nell insieme.


##Funzioni

Dovrai implementare le seguenti funzioni che operano su un insieme astratto $S$, inizialmente vuoto:
1. AddNumber(x), che deve aggiungere il numero $x$ all'insieme (ossia $S' := S \cup \{x\}$).
2. EraseNumber(x), che deve togliere il numero $x$ dall'insieme (ossia $S' := S \setminus \{x\}$).
3. isPresent(x), che deve dire se il numero $x$ sia attualmente presente nell'insieme.
4. MaxNumber(), che deve restituire il più grande numero nell'insieme.
5. nthNumber(n), che deve restituire l'$n$-esimo numero dell'insieme (come ordinato per grandezza crescente).

##Goals

Questo problema prevede i seguenti goal, ossia obbiettivi che puoi prefiggerti di raggiungere
(se ne vedi altri di interessanti facci sapere che arricchiamo il problema):
- *linear*, $Q \leq 1000$
- *constant-noremove*, $Q \leq 1000000$, senza query di tipo 2 e 5 (ossia non vengono mai chiamate le funzioni EraseNumber e nthNumber(n)).
- *logn*, $Q \leq 100000$, senza query di tipo 5
- *logn-no_libraries*, $Q \leq 100000$, senza query di tipo 5. Non ti sarà permesso di includere alcuna libreria
- *logn-nth*, $Q \leq 100000$, e dovrai gestire anche query di tipo 5.
- *logn-nth-no_libraries*, $Q \leq 100000$, non ti sarà permesso di includere alcuna libreria e dovrai gestire anche query di tipo 5.
