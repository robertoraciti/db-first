### Consegna

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!

### Svolgimento

| COLONNA               | TIPO        | ATTRIBUTI                  |
| --------------------- | ----------- | -------------------------- |
| ID                    | BIGINT      | PRIMARY_KEY,AUTO_INCREMENT |
| MARCA                 | VARCHAR(30) | NOT NULL                   |
| MODELLO               | VARCHAR(30) | NOT NULL                   |
| PORTE                 | TINYINT(1)  | NULL, UNSIGNED             |
| COLORE                | VARCHAR(20) | NULL                       |
| KM_PERCORSI           | SMALLINT    | NULL, UNSIGNED             |
| ANNO_IMMATRICOLAZIONE | YEAR        | NOT NULL                   |
| ALIMENTAZIONE         | CHAR(1)     | NOT NULL                   |
| CAMBIO                | CHAR(1)     | NULL                       |
| CILINDRATA            | SMALLINT    | NOT NULL, UNSIGNED         |
| POSTI                 | TINYINT     | NULL, UNSIGNED             |
| PREZZO                | FLOAT(8,2)  | NULL                       |
| TIPOLOGIA             | VARCHAR(20) | NULL                       |
| TARGA                 | CHAR(7)     | NULL, UNIQUE               |
