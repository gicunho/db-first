# Database Auto usate:

## (table) Cars:

- id                               INT | PRIMARY_KEY | UNIQUE | NOTNULL | AUTO_INCREMENT           
- make                             VARCHAR(50) | NOTNULL
- model                            VARCHAR(50) | NOTNULL
- variant                          VARCHAR(50) | NULL
- body type                        VARCHAR(100) | NULL
- year                             YEAR | NOTNULL
- fuel type                        VARCHAR(50) | NULL
- new                              TINYINT | 0 or 1 | NULL
- used                             TINYINT | 0 or 1 | NULL
- mileage                          SMALLINT | NOTNULL
- power                            VARCHAR(50) | NOTNULL
- gear                             VARCHAR(50) | NOTNULL
- n° doors                         TINYINT | NULL
- n° seats                         TINYINT | NULL
- body color                       VARCHAR(50) | NOTNULL
- interior color                   VARCHAR(50) | NULL
- euro emssion class               TINYINT | NULL
- price                            VARCHAR(50) | NOTNULL
- previous owners                  TINYINT | NULL
- had accident                     TINYINT | 0 or 1 | NULL
