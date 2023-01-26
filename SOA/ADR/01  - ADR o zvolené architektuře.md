# Rozhodnutí o zvolené architektuře

## ID
1

## Datum
21.01.2023

## Status
Schválené

## Context
Je třeba zvolit architekturu sytému pro registrace a platby kurzů pro širokou veřejnost i studenty.

## Decision
Pro vznikající systém registrací a plateb kurzů budeme využívat SOA (Service Oriented Architecture), architektura rozhraní bude REST.

Bude exisistovat server, na kterém budou nasazeny jednotlivé moduly poskytující funkcionalitu jendotlivých služeb. Jedním z modulů je frontendová aplikace, komunikující 
s monolitickými moduly na rozhraní REST pomocí protokolu HTTPS.

Moduly aplikace:
- Frontend (Uživatelské rozhraní)
- Modul správy kurzů
- Modul plateb - pro komunikaci s platební bránou
- Modul fakturací
- Modul správy uživatelů
- Modul administrační
    

## Consequences
Po zvolení této architektury, bude snadnější implementace budoucích změn, dále umožní v případě potřeby i snadnou škálovalnost. Oproti klasické monolitické architerktuře 
je tato varianta vývoje nákladnější a náročnější na realizaci.

[< Zpět](../ "Zpět do adresáře SOA")
