# Interview Kit

# 15/12/2023
### Interview #1
- Quali sono le differenze fra classe astratta ed interfaccia in Java?
- In un'istruzione della forma *float z = Z.attempt();*, sapendo che Z è una classe, cosa si può dire sul metodo *attempt*?
- Cos'è un design pattern?
- Qual è la differenza fra override e overload?
- Spiegare perchè un overload della seguente forma sia permesso o meno in Java e motivare la risposta:
    - float method1(int)
    - int method1(int)

# 13/12/2023
### Interview #1
- Scrivere un metodo in Java che prende come parametro un HashMap<String, String> e ritorni una List<String> contenente la concatenazione di ogni coppia chiave-valore nell'HashMap.
- Scrivere un metodo in Java che prende come parametro una List<String> _strings_ ed una List<Integer> _integers_ e ritorni _true_ se almeno metà degli elementi di _strings_ sono convertibili ad intero (TIP: usare _Integer.parseInt_) e corrispondano, da convertiti, ad un elemento in _integers_, altrimenti ritorna _false_.

### Interview #2
- Scrivere entrambi i metodi precedenti sfruttando lo stream programming
- Scrivere un metodo in Java che prende come parametro un HashMap<String, String> e ritorni una lista di interi che contiene la somma della lunghezza dei caratteri di ogni coppia chiave-valore dell'HashMap.
- Estendere questo metodo ritornando _true_ se più della metà delle lunghezza è strettamente maggiore di un parametro _k_ passato al metodo.
    
# 07/12/2023
### Interview #1
Nello schema precedente (01/12/2023) scrivere le seguenti query:
- Ritorna per ogni studente il nome e la media dei voti moltiplicata per il numero di esercizi consegnato.
- Ritorna per ogni corso la media dei voti.
- Ritorna per ogni corso il numero di studenti che lo seguono.

### Interview #2
- Scrivere un metodo in Java che prenda in input un array di interi e ritorni la somma degli elementi divisibili per 3. Sviluppare una versione iterativa usando un classico ciclo for, una versione che utilizza gli Stream di Java ed una versione ricorsiva che oltre all'array di interi prende come parametro la somma corrente e l'indice da cui bisogna leggere l'array.

# 01/12/2023
### Interview #1
Nel seguente schema:
  Student(
        id INTEGER PRIMARY KEY,
        name VARCHAR,
        course_id VARCHAR,
        exercises INTEGER
  )
  Marks(
        student_id INTEGER,
        grade INTEGER
  )
Scrivere le seguenti query:
- Ritorna il nome dello studente che ha preso il voto più alto fra quelli registrati.

# 29/11/2023
### Interview #1
- Scrivere un metodo Java che prenda come parametro due array di double A e B e ritorni la somma della prima metà degli elementi di A più il prodotto della seconda metà degli elementi di B
- In un'istruzione della forma *int y = A.count();*, sapendo che A è una classe, cosa si può dire sul metodo *count*?

## 24/11/2023
### Interview #1
- Scrivere un metodo Java che prenda come parametro un array di interi e ritorni la somma di tutti gli elementi che si trovano in indici che sono potenze di 2
- Scrivere un metodo Java che prenda come parametro due array di double A e B e ritorni la somma della prima metà degli elementi di A più il prodotto della seconda metà degli elementi di B
- In un'istruzione della forma *int x = obj.size();*, *size* cosa rappresenta all'interno dell'oggetto *obj*?
- In un'istruzione della forma *int y = A.count();*, sapendo che A è una classe, cosa si può dire sul metodo *count*?

## 17/11/2023
### Interview #1
- Cos'è un'interfaccia in Java?
- Cos'è un metodo astratto in Java?
- La classe astratta A ha un metodo astratto op(). B eredita da A ed implementa op(). La classe C, che eredita da B, può fare override di op()?
- Scrivere un metodo Java che prenda come parametro un array di interi e ritorni la somma di tutti gli elementi che si trovano in indici che sono potenze di 2
- Ad un servizio REST facciamo la seguente richiesta: GET /users/10/posts. Descrivere a cosa, intuitivamente, servirà questa richiesta.
- Scrivere metodo HTTP e URI di una richiesta col seguente scopo: "Inserisci un nuovo evento per l'utente con id 10"

### Interview #2
- Quali sono le differenze fra int e long in Java?
- Scrivere un metodo Java che prenda come parametro un array di interi e ritorni la somma di tutti gli elementi che si trovano in un indice i tale che i % 3 == 1
- All'interno del framework Spring, cos'è un repository ed a cosa serve?
- Scrivere una query in SQL che nel seguente schema:
  Student(
        id INTEGER PRIMARY KEY,
        name VARCHAR,
        course_id VARCHAR,
        exercises INTEGER
  )
  Marks(
        student_id INTEGER,
        grade INTEGER
  )
  Ritorni lo studente che ha preso il voto più basso fra quelli registrati.

### Interview #3
- Cos'è un metodo final in Java?
- Cos'è una variabile final in Java?
- A cosa serve la keyword static in Java applicata a variabili e metodi?
- Scrivere un metodo Java che prenda come parametro due array di interi A e B e ritorni il prodotto di tutti gli elementi negli indici i tali che A[i] == B[i] / 2 e i % 2 == 1.
- Scrivere una query in SQL che nel seguente schema:
  Student(
        id INTEGER PRIMARY KEY,
        name VARCHAR,
        course_id VARCHAR,
        exercises INTEGER
  )
  Marks(
        student_id INTEGER,
        grade INTEGER
  )
  Ritorni la lista di corsi ordinati in senso decrescente in base al voto medio degli studenti che ne fanno parte.

## 25/10/2023
### Interview #1
- Cosa cambia fra int, float e double?
- In un codice del tipo *try { ... } catch(InputError e) { ... }*, InputError eredita da quale classe della libreria standard Java?
- Scrivere un metodo Java che prenda come parametro un array di double e stampi tutti gli elementi che si trovano ad un indice dispari.
  
### Interview #2
- Qual è la differenza fra classe astratta ed una non-astratta? E fra classe astratta ed interfaccia?
- Scrivere un metodo Java che prenda come parametro un array di double e stampi tutti gli elementi che si trovano ad un indice dispari se presente nella prima metà dell'array, e quelli presenti ad un indice pari nella seconda metà dell'array.
- Scrivere una query in SQL che nel seguente schema:
  Student(
        id INTEGER PRIMARY KEY,
        name VARCHAR,
        course_id VARCHAR,
        exercises INTEGER
  )
  Marks(
        student_id INTEGER,
        grade INTEGER
  )
  Ritorni lo studente che ha preso il voto più basso fra quelli registrati.

## 23/10/2023
### Interview #1
- Qual è la definizione di classe astratta?
- Qual è la differenza fra classe astratta ed interfaccia?
- Quanti bit vengono utilizzati per rappresentare una variabile di tipo *byte* e qual è il range rappresentabile in questa unità?
- In un'istruzione del genere: *List<String> names = ...;*, *String* cos'è per quest'oggetto di tipo *List*?
- Scrivere una query in SQL che nel seguente schema:
  Student(
        id INTEGER PRIMARY KEY,
        name VARCHAR,
        course_id VARCHAR,
        exercises INTEGER
  )
  Marks(
        student_id INTEGER,
        grade INTEGER
  )
  Ritorni lo studente che ha preso il voto più alto fra quelli registrati.
- Scrivere un metodo Java che prenda come parametro un array di interi e stampi tutti gli elementi che si trovano ad un indice divisibile per 3.

## 20/10/2023
### Interview #1
- Qual è la differenza fra short e int in Java? Quali sono i range di valori rappresentabili con questi tipi di dato?
- In un'istruzione della forma *String str = obj.name;*, *name* cosa può rappresentare all'interno dell'oggeto *obj*?
- Scrivere una query in SQL che sulla seguente tabella:
  Student(
        name VARCHAR,
        course_id VARCHAR,
        exercises INTEGER
  )
  Ritorni tutti gli studenti iscritti al corso "SQL 10" che non hanno svolto alcun esercizio.
- Avendo nello stesso database dell'esercizio precedente la seguente tabella:
  Marks(
        student_name VARCHAR,
        grade INTEGER
  )
  Ritornare per ogni corso la media dei voti (I voti sono rappresentati dalla colonna 'grade').

## 18/10/2023
### Interview #1
- Qual è la definizione di classe astratta?
- Qual è la definizione di interfaccia in OOP?
- Quali sono le differenze fra una variabile di tipo "char[]" ed una di tipo "String"?
- Scrivere un metodo che prende in input due array di char A e B e ritorni un array di char C contenenti i caratteri di B invertiti di ordine seguiti dai caratteri in A nello stesso ordine in cui si trovano. Esempio: A = [c, d, e], B = [f, c, b], C = [b, c, f, c, d, e]

## 13/10/2023
### Interview #1
- Cos'è un'interfaccia nel contesto dell'OOP?
- Cosa differenzia un'interfaccia da una classe astratta?
- Qual è la differenza fra int e long in Java?
- Qual è il range di valori interi con segno rappresentabile con un byte?
- Scrivere una query in SQL che sulla seguente tabella:
  Users(
        name VARCHAR,
        followers INTEGER,
        nationality VARCHAR
  )
  Ritorni, per ogni nazionalità presente nel database, la media dei follower degli utenti di una determinata nazionalità.
- Scrivere un metodo che prende come parametro un array di double e ritorni un array di interi in cui all'i-esima posizione è presente il casting ad intero dell'i-esimo elemento dell'array di input se esso è positivo, 0 altrimenti. 

## 06/10/2023
### Interview #1
- Qual è la differenza fra float e double?
- Qual è la definizione di classe astratta?
- Nel contesto di un database relazionale, si vuole imporre che la colonna X della tabella A faccia da riferimento all'identificatore di un'altra tabella B. Quale costrutto va utilizzato?
- Scrivere un metodo che prende come parametro un array di interi ed un intero n e restituisce il massimo fra gli ultimi n elementi dell'array.

### Interview #2
- Quali differenze ci sono fra una List ed un Set?
- Cos'è un'interfaccia nel contesto dell'OOP?
- A cosa servono le operazioni di JOIN e UNION in un database SQL?
- Scrivere un metodo che prende come parametro un array di float e restituisce il minimo valore presente nella prima metà dell'array.
