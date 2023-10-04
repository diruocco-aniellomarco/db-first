**esercizio di oggi: Database First**

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

| COLONNA               | TIPO        | ATTRIBUTI           | COMMENTI                      |
| --------------------- | ----------- | ------------------- | ----------------------------- |
| targa                 | VARCHAR(10) | PRIMARY_KEY         |
| modello               | VARCHAR(50) | NOTNULL             |
| marca                 | VARCHAR(50) | NOTNULL             |
| colore_carrozzeria    | VARCHAR(15) | NULL                |
| alimentazione         | VARCHAR(1)  | NOTNULL             | B=benzina;D=disel;M=metano... |
| km_percorsi           | FLOAT(9,3)  | NOTNULL, DEFAULT(0) |
| airbag                | TINYINT(1)  | NULL, DEFAULT(0)    |
| numero_porte          | TINYINT(1)  | NULL, UNSIGNED      |
| cilindrata            | SMALLINT    | NULL, UNSIGNED      |
| anno_immatricolazione | YEAR        | NOTNULL             |
| costo_acquisto        | MEDIUMINT   | NOTNULL             |
| costo_riparazione     | SMALLINT    | NOTNULL, DEFAULT(0) |
| prezzo_minimo_vendita | MEDIUMINT   | NOTNULL             |
