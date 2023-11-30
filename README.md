# Térinformatika Beadandó
Bevezetés
---------
A térkép a Leaflet nevű, interaktív térképek létrehozására szolgáló nyílt forráskódú JavaScript könyvtárat használja.
Ez a Leaflet projekt egy egyszerű webtérkép, amely bemutatja Párizs különböző nevezetességeit, beleértve a látnivalókat, a metró térkép átfedést és egy poligont, amely a "Field The Mars" területet ábrázolja. 

Térkép jellemzők
----------------
- Jelzőpontok
Öt jelzőpont, amelyek Párizs kulcsfontosságú nevezetességeit képviselik: Eiffel-torony, Notre-Dame, Louvre, Musée d'Orsay és Az Arkád.
Minden jelzőpont rendelkezik egy egyedi ikonnal (location-icon.png) és egy felugró ablakkal további információkkal.
- Metró térkép átfedés
Egy 1939-es párizsi metró térkép átfedése.
- GeoJSON poligon
Egy GeoJSON poligon, amely a "Field The Mars" területet ábrázolja Párizsban.
- Alaptérképek
Két alaptérkép: OpenStreetMap és OpenStreetMap HOT (Humanitárius OpenStreetMap Team).

Rétegek és Rétegvezérlés
------------------------
Rétegcsoportokat hoztak létre minden jellemző kategóriához: Helyek, Metró és Field The Mars.
Az alaptérképek (OpenStreetMap és OpenStreetMap HOT) külön rétegvezérlési kategóriába tartoznak.
A Rétegvezérlés lehetővé teszi a felhasználók számára, hogy be- és kikapcsolják az egyes rétegek láthatóságát a térképen.

Adatok
------
A nevezetességek építéséről megjelenített adatokat a Wikipédióról vannak származtatva.
- https://hu.wikipedia.org/wiki/Eiffel-torony
- https://hu.wikipedia.org/wiki/Musée_d’Orsay
- https://hu.wikipedia.org/wiki/Notre-Dame-székesegyház_(Párizs)
- https://hu.wikipedia.org/wiki/Louvre
- https://hu.wikipedia.org/wiki/Arc_de_Triomphe