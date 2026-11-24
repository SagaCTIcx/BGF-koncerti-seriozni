# Koncertni kalendar

Jednostavna stranica za praćenje koncerata na koje idemo zajedno sa prijateljima, da svi na jednom mestu vide kada je sledeći.

## Mogućnosti

- Brojač do sledećeg koncerta koji odbrojava uživo
- Hronološki pregled svih koncerata u sezoni; održani su zatamnjeni
- Detalji za svaki koncert: izvođači, program i napomene
- YouTube pretraga za svaku kompoziciju, za slušanje pre koncerta
- Dodavanje u Google kalendar, ili izvoz svih termina kao `.ics` fajl

## Tehnički

- Jedan statički `index.html` (HTML, CSS i vanilla JavaScript)
- Bez build koraka, bez zavisnosti i bez servera
- Vreme se računa po zoni `Europe/Belgrade`, uključujući prelazak na letnje računanje vremena
- Hostovano na GitHub Pages

## Izmene

Podaci o koncertima nalaze se u nizu `concerts` na početku `<script>` dela u `index.html`. Posle izmene je dovoljno commitovati fajl, a GitHub Pages osveži stranicu za minut ili dva.
