# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.





ID:                         [1]                  BIGINT                   NOT NULL, UNIQUE, AUTOINCREMENT
Marca:                      [Audi]               VARCHAR(20)              NOT NULL
Modello:                    [Berlina]            VARCHAR(25)              NOT NULL
Segmento:                   [Sport]              VARCHAR(25)              NOT NULL
Cilindrata:                 [1.600]              FLOAT(4,2)               NOT NULL
Potenza:                    [85KW]               VARCHAR(5)               NOT NULL
Alimentazione:              [Disel]              VARCHAR(25)              NOT NULL
Porte:                      [5]                  VARCHAR(7)               NOT NULL
Cambio:                     [Manuale]            VARCHAR(12)              NOT NULL
Colore:                     [Nero]               VARCHAR(25)              NOT NULL
Descrizione                 [Lorem10]            TEXT                     NULL
Immatricolazione:           [2022]               YEAR                     NOT NULL
Prezzo:                     [14.000,00]          DECIMAL(6, 2)            NOT NULL
Classe di emissione:        [Euro8]              VARCHAR(6)               NOT NULL
