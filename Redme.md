<!--
Consegna:
Modellizzare la struttura di una tabella
per memorizzare tutti i dati riguardanti
delle auto usate messe in vendita da un concessionario
-->

# Table Name: Used_Cars

- id: BIGINT | AUTO_INCREMENT, UNIQUE, NOTNULL
- brand: VARCHAR(255) | NOTNULL
- model: VARCHAR(102) | NOTNULL <!-- ACTUAL LONGEST NAME BEING 51 CHARS -->
- color: VARCHAR(46) | NOTNULL <!-- ACTUAL LONGEST NAME BEING 23 CHARS -->
- km: FLOAT(7,1) | NOTNULL
- year: YEAR | NOTNULL
- price: DECIMAL(9,2) | NOTNULL
- cv: VARCHAR(30) | NULL
- doors: TINYINT | NULL
- description: TEXT| NULL
- notes: TEXT| NULL
- image: VARCHAR(255) | NULL