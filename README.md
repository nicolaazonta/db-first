# db-first:
- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## data types:
- strings: [ varchar(number), char(number), text, longtext ]
- number: [ tinyint, small/medium int, int, int, bigint ]
- decimals: [ float(i,d), double(i,d), decimal(i,d) ]
- dates: [ DATETIME, DATE, YEAR, TIME, TIMESTRAP ]

## data attributes:
- PK -> primary key
- AI -> auto increment
- NN -> NOT NULL
- UNIQUE 

## entity name: book

## table name: cars

## table columns:

- id        | INT | PK, AI, NN, UNIQUE | INDEX
- brand     | VARCHAR(30) | NOTNULL | INDEX 
- model     | VARCHAR(40) | NOTNULL | INDEX
- variant   | VARCHAR(50) |
- body_type | VARCHAR(50) |
- fuel_type | VARCHAR(30) | 
- reg_year  | YEAR | INDEX
- country   | VARCHAR (30) |
- price     | SMALLINT | NOTNULL | INDEX
- mileage   | INT | NOTNULL | INDEX
- power     | TINYINT | NOTNULL
- gear      | VARCHAR(40) | NULL
- doors     | VARCHAR(20) | NULL
- seller    | VARCHAR(40) | NULL
- ?image?   | TEXT | NULL