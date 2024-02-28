# USED CAR DEALER DATABASE TABLE

| Colonne               | Tipo         | Attributi                  |
| --------------------- | ------------ | -------------------------- |
| id                    | BIGINT       | PRIMARY_KEY AUTO_INCREMENT |
| costo                 | FLOAT(6,2)   | NOTNULL                    |
| modello               | VARCHAR(40)  | NOTNULL                    |
| km_percorsi           | MEDIUMINT    | NOTNULL                    |
| condizioni            | CHAR(1)      | NOTNULL DEFAULT(A)         |
| casa_di_produzione    | CHAR(3)      | NOTNULL                    |
| anno_rilascio_modello | DATE         | NULL                       |
| immatricolazione      | DATE         | NOTNULL                    |
| incidenti             | BOOL/TINYINT | NOTNULL                    |
| garanzia              | BOOL/TINYINT | NOTNULL                    |
| ultima_revisione      | DATE         | NOTNULL                    |
