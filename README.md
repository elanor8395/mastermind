# mastermind
Uni project for the Advanced Programming course.

## History
Mastermind is a code-breaking game for two player that is based on an older, paper based game called Bulls and Cows. The modern game with pegs was invented in 1970 by Mordecai Meirowitz, an Israeli postmaster and telecommunications expert. A computer adaptation of it was run on Cambridge University’s Titan computer system, where it was called 'MOO'.

### How to play
In the original version [translate]

Nella versione originale di Mastermind, il codice segreto è di quattro cifre e il codificatore ha a disposizione, per comporlo, le dieci cifre del sistema decimale standard (0,1,2,3,4,5,6,7,8,9). Esistono numerose versioni successive, la più famosa è quella in cui al posto dei numeri si usano dei pioli di 6 colori differenti. Mastermind è uno dei giochi utilizzati all'interno del Mind Sports Olympiad, competizione multidisciplinare per promuovere giochi di abilità mentale.

Dopo che il codificatore ha composto il codice, il decodificatore fa il suo primo tentativo, cercando di indovinare il codice. Il codificatore, appena il suo avversario ha completato il tentativo, fornisce degli aiuti comunicando:

Il numero di cifre giuste al posto giusto, cioè le cifre del tentativo che sono effettivamente presenti nel codice al posto tentato, con pioli neri.
Il numero di cifre giuste al posto sbagliato, cioè le cifre del tentativo che sono effettivamente presenti nel codice, ma non al posto tentato, con pioli bianchi.
Non bisogna comunicare quali cifre sono giuste o sbagliate ma solo quante. Se il decodificatore riesce ad indovinare il codice entro il numero di tentativi predeterminati (solitamente i tentativi sono 9) allora quest'ultimo vince la partita, altrimenti vince il codificatore.

# Versione con carta e penna
Si può giocare a Mastermind utilizzando solo carta e penna con i numeri al posto dei colori.

Denominato nella versione americana Bulls and Cows.

Due giocatori, a turno, tentano di indovinare il numero scelto dell'avversario comunicandogli una serie di cifre.

Il punteggio si compone di due tipi di punti che sono segnati sul foglio di gioco con dei quadratini (o anche triangoli) e con dei cerchietti.

Si ottiene un punto se nel numero comunicato c'è una cifra che è presente nel numero segreto dell'avversario. Si ha un quadrato (o un triangolo) se la cifra indovinata occupa precisamente la stessa posizione, mentre si ha un cerchio se la cifra è presente nel numero segreto dell'avversario, ma in una posizione diversa.

Ad esempio se il numero comunicato è 1234 ed il numero segreto è 1543, il punteggio è di un quadrato (o un triangolo) e due cerchi in quanto la cifra 1 è stata indovinata proprio nella sua effettiva posizione, mentre le cifre 3 e 4, pur essendo presenti nel numero segreto, si trovano in posizioni diverse.
