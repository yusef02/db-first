# db first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

|        FIELD        |     TYPE     |            ATTRIBUTES            |   INDEXES   |
| :-----------------: | :----------: | :------------------------------: | :---------: |
|         id          |     INT      | NOT NULL,UNSIGNED,AUTO INCREMENT | PRIMARY KEY |
|     kilometers      |  MEDIUMINT   |        NOT NULL,UNSIGNED         |     ---     |
|        model        | VARCHAR(30)  |             NOT NULL             |     ---     |
|        price        |  FLOAT(7,2)  |        NOT NULL,UNSIGNED         |     ---     |
|    matriculation    |     DATE     |             NOT_NULL             |     ---     |
| piston displacement | DECIMAL(4,3) |        NOT_NULL, UNSIGNED        |     ---     |
|     conditions      |     TEXT     |               NULL               |     ---     |
|        color        | VARCHAR(15)  |            DEFAULT(0)            |             |
