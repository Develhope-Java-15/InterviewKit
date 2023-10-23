# Interview Kit

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
