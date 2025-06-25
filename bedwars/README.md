# Bedwars wereld opzetten
(je moet /op hebben om de /bw admin commands te kunnen gebruiken)

### stap 1: maak de arena
- ga naar de map 
```
/mvtp (mapnaam)
```

- zet deze map als arena
```
/bw admin (mapnaam) add
```

### stap 2: grootte van de arena selecteren
- ga naar 1 van de hoeken buiten bereik van eilanden bovenaan
```
/bw admin (mapnaam) pos1
```

- ga naar tegenoverstaande hoeken buiten bereik van eilanden onderaan
```
/bw admin (mapnaam) pos2
```

### stap 3: teams toevoegen
- voeg teams toe voor elke spawn dat er in de map is
```
/bw admin (mapnaam) team add (kleur zonder hoofdletters) (kleur met hoofletters) (spelers per team)
```

### stap 4: teams spawn toevoegen
- ga op de spawnplaats staan van het team (2de blok voor spawner, naar buiten kijken met ong een tilt van 90 graden:
```
/bw admin (mapnaam) team spawn (kleur)
```

### stap 5: teams bed toevoegen
- ga op het bed staap van een team, ga naar het hoofdstuk ervan en kijk naar beneden naar het hoofstuk van het bed:
```
/bw admin (mapnaam) team bed (kleur)
```

### stap 6: spawners toevoegen
- ga op de blok staan waar het moet spawnen (! op eiland zelf is alleen iron en gold (op dezelfde blok en dat is het middelste blok bij spawners, diamond op de apparte eilanden en emeralds in het midden):
```
/bw admin (mapnaam) spawner add (ore) (true/false (bij iron en gold --> false , bij diamond en emerald --> true)
```

### stap 7: shop toevoegen
- als je naar een eiland toevliegt moet voor de shop aan de linkerkant de dealer komen. ga is spectator mode, vlieg naar binnen, ga in cretive mode, sta op de grond, ga in de middelste van de 3 blokken staan, doe het volgende command en dan weer spectator mode
```
/bw admin (mapnaam) store add Dealer
```

### stap 8: upgrade shop toevoegen
- als je naar een eiland toevliegt moet voor de shop aan de rechterkant de upgradeShop komen. ga is spectator mode, vlieg naar binnen, ga in cretive mode, sta op de grond, ga in de middelste van de 3 blokken staan, doe het volgende command en dan weer spectator mode
```
/bw admin (mapnaam) store add upgradeShop upgradeShop.yml false
```

### stap 9: bepaal de lobby
- ga naar het vliegende platform, sta op de grond, kijk recht naar voor en sta in het midden van het platform
```
/bw admin (mapnaam) lobby
```

### stap 10: bepaal de spectator spawnplaats
- ga in creative aan de onderkant van het vliegende eiland staan en kijk recht naar beneden:
```
/bw admin (mapnaam) spec
```
### stap 11: map opslaan/aanpassen
- map opslaan:
```
/bw admin (mapnaam) save
```
-map aanpassen later:
```
/bw admin (mapnaam) edit
```

### stap 12: join sign toevoegen
- ga naar de bedwars lobby:
```
/mvtp bedwars_lobby
```
- plaats een sign met deze inhoud:
```
[bedwars]
(mapnaam)
```
