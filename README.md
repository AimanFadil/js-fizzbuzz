Ciao ragazzi,
Esercizio di oggi: FizzBuzz
nome repo: js-fizzbuzz
Consegna:
Scrivi un programma che stampi in console i numeri da 1 a 100,
ma che per i multipli di 3 stampi “Fizz” al posto del numero e per i multipli di 5 stampi “Buzz”.
Per i numeri che sono sia multipli di 3 che di 5 stampi “FizzBuzz”.
Prima di partire a scrivere codice poniamoci qualche domanda:
Come faccio a sapere se un numero è divisibile per un altro?
Abbiamo visto qualcosa di particolare che possiamo usare?
Consigli del giorno:
1. Scriviamo sempre prima dei commenti in italiano per capire cosa vogliamo fare
2. Proviamo ad immaginare le operazioni che vogliamo far svolgere al nostro programma così come lo faremmo "a mano"
BONUS:
Crea un container nel DOM , aggiungendo (attraverso la funzione `appendChild()` oppure con la classica concatenazione vista fin'ora) un elemento html con il numero o la stringa corretta da mostrare.

1.Dichiariamo la variabile max con valore 100.
2.inizializziamo un ciclo for 
    2.1.Con contatore = 1, condizione = 100 e incremento = i + 1
3.Creiamo 4 istruzioni condizionali
    3.1. if che ha per condizione: se la variabile i è un multiplo di 3 E di 5 allora verrà stampato FizzBuzz.
    Per stampare il risultato di questa variabile è necessario inserire : console.log('FizzBuzz') 
    3.2. else if che ha per condizione: se la variabile i è un multiplo di 3  allora verrà stampato Fizz.
    Per stampare il risultato di questa variabile è necessario inserire : console.log('Fizz')
    3.3. else if che ha per condizione: se la variabile i è un multiplo di 5  allora verrà stampato Buzz.
    Per stampare il risultato di questa variabile è necessario inserire : console.log('Buzz')
    3.4. else che non ha condizione quindi tutto ciò che non rientra nelle condizioni appena citate verrà stampato come numero normale.
    Per stampare il risultato di questa variabile è necessario inserire : console.log('i').
     
