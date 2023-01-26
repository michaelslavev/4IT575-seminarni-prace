# Rozhodnutí o platební bráně

## ID
3

## Datum
26.01.2023

## Status


## Context
Je třeba zvolit platební bránu třetí strany.

Možní dodavatele platebních bran:
- Comgate
    - Režim sazebníku - Pevné sazby
    - Poplatek z platby kartou (spotř., EU) - 0,59 až 0,79 %
    - Poplatek z transakcí, Kč - 1,80 až 2,40
    - Měsíční poplatek, Kč - 0 až 149
    - Aktivační poplatek, Kč - není
    - Převod na bankovní účet, Kč - není
- GoPay
    - Režim sazebníku - MIF++
    - Poplatek z platby kartou (spotř., EU) - 0,9 až 2,26 %
    - Poplatek z transakcí, Kč - 3
    - Měsíční poplatek, Kč - 0 až 190
    - Aktivační poplatek, Kč - není
    - Převod na bankovní účet, Kč - 10
- PayU
    - Režim sazebníku - Pevné sazby
    - Poplatek z platby kartou (spotř., EU) - 1,45 %
    - Poplatek z transakcí, Kč - 1
    - Měsíční poplatek, Kč - není
    - Aktivační poplatek, Kč - 999
    - Převod na bankovní účet, Kč - není


## Decision
Pro vznikající systém a modul plateb budeme využívat platební bránu třetí strany od dodavtele Comgate.
Komunikace s platební bránou bude probíhat na rozhraní REST API pomocí zabezpečeného protokolu HTTPS.

## Consequences
Nevýhodou toho řešení je měsíční poplatek za provoz.

Výhodou jsou nízké nízké procentuelní poplatky za platby kartou a pevný režim sazeb. 

[< Zpět](../ "Zpět do adresáře SOA")
