db-first
Sviluppare una tabella che riguarda le auto di un concessionario di auto usate.
La seguente tabella dovrà contenere i dati che possono servire al gestore di attività.
Pensate prima ai campi che servono,
poi al tipo di dato che devono conservare ed infine agli attributi.



‘Concessionario auto usate'


CAMPO                 TIPO DI DATO              ATTRIBUTO

ID                    Numero incrementale       PRIMARY KEY, UNIQUE, AI

Immatricolazione      Data DATE                 NOTNULL

Km                    Numero SMALL               NOTNULL

Marca                 varchar(20)               NOTNULL

Modello               varchar(20)               NOTNULL

Prezzo                Numero FLOAT(8,2)         NOTNULL

Carrozzeria           varchar(40)

Alimentazione         varchar(20)

Colore                varchar(20)

Disponibilità         Boolean TINYINT           DEFAULT(0)

Foto                  Boolean TINYINT           DEFAULT(0)
