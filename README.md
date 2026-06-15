# R9FH2F-Gazszintmero
Digitalis technika beadando - Gazszintmero

Vígh László 

R9FH2F 

 

Projektmunka: Gázszintmérő kijelzővel 

 

https://www.tinkercad.com/things/16a0WbZxaBb-r9fh2f-gazszintmero?sharecode=O5xaodDuQzTyqaQENLzipN6vlqGktQCkkPXOwj98EfQ 

 

A projekt célja eredetileg klórgázszint mérésére szolgáló műszer lett volna, de nem találtam meg a megfelelő modult, így egy sima gázszintmérőt építettem meg a Tinkercad-ben. 


Alkatrészek listája: 

Arduino Uno R3 

1 db 7 szegmenses LED kijelző 

1 db LCD 16x2 (I2C) kijelző 

3 db 220 Ω-os ellenállás 

1 db 4,7 kΩ-os ellenállás 

1 db Breadboard 

1 db Piezo 

 

Megvalósítás: 

A tervemet a Tinkercad oldalán valósítottam meg. A célom az volt hogy egy olyan eszközt építsek meg ami a gázkoncentráció szintjét méri és egy kijelző segítségével kiírja az aktuális értékszintet plusz egy Lcd kijelző is jelzi az aktuális értéket ami kiegészítésképpen szöveges üzenettel is jelzi a 3 fokozatot ami: Megfelelő --> Figyelem --> Riadó! . Az értékek jelzéséhez ledeket is beépítettem a panelra, ahol a zöld LED lassan villog, jelezve hogy minden rendben. A sárga LED-re villogást állítottam be, plusz egy Piezo hangszórót is bekötöttem, ami csippanó jelzéssel figyelmeztet hogy a gázszint megnövekedett. Ha a szint kritikus, vagyis elérte a veszélyes szintet, akkor a piros LED folyamatosan világít és a Piezo folyamatosan sípol.

A többi információt a feltöltött dokumentumban találja.
