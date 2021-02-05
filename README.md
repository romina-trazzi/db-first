# database name : Videogames_Negozio
# nome tabella : Videogames

- id BIGINT PRIMARYKEY NOTNULL AUTO_INCREMENT
- isbn string VARCHAR(10) NOTNULL UNIQUE

- titolo string TEXT(1500) NOTNULL
- descrizione string TEXT NULL
- genere string VARCHAR(20) NOTNULL

- modalità_gioco string VARCHAR(20) NULL
- piattaforma string VARCHAR(30) NULL

- produttore string VARCHAR(30) NULL
- anno_uscita date YEAR NOTNULL
- prezzo int FLOAT(3,2) 999,99 NULL

- cover string VARCHAR() NULL

- lingua_originale string VARCHAR(20) NOTNULL
- sottotitoli int TINYINT NULL DEFAULT(1)

- disponibile int TINYINT NULL DEFAULT(1)
- quantità int SMALLINT NULL DEFAULT(0)




