#Qual'è il massimo?

Hai un insieme, inizialmente vuoto, ti verranno dati dei numeri da aggiungere o togliere dall'insieme.
Ti verrà chiesto a volte di dire qual'è il numero più grande tra i numeri dell'insieme.

##Funzioni

Dovrai implementare queste tre funzioni:
1. AddNumber(x), che deve aggiungere il numero x all'insieme.
2. EraseNumber(x), che deve togliere un numero dall'insieme.
3. MaxNumber(), che deve restituire il più grande numero nell'insieme.
4. nthNumber(n), che deve restituire l'n-esimo numero dell'insieme

##Goals

Questo problema prevede i seguenti goal, ossia obbiettivi che puoi prefiggerti di raggiungere
(se ne vedi altri di interessanti facci sapere che arricchiamo il problema):
- *linear*, Q <= 50000
- *constant-noremove*, Q <= 1000000 e non viene chiamata mai la funzione EraseNumber.
- *logn*, Q <= 100000
- *logn-no_libraries*, Q <= 100000 e non ti sarà permesso di includere alcuna libreria

