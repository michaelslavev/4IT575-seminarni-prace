# Rozhodnutí o platební metodě

## ID
2

## Datum
26.01.2023

## Status


## Context
Je třeba zvolit platební metodu pro systém platby kurzů pro širokou veřejnost i studenty.
Možnosti implementace jsou interní řešení a platební brána třetí strany.

## Decision
Pro vznikající systém a modul plateb budeme využívat platební bránu třetí strany, kounikující na rozhraní REST pomocí zabezpečeného protokolu HTTPS.

## Consequences
Platební brána třetí strany je vhodným řešením pro aktuální stav - obsahuje všechny potřebné funkcionlity:
- platba kartou
- bankovním převodem
- Apple Pay
- Google Pay
- click to pay
- uložení platební karty pro další platby

Nevýhodou toho řešení je závislost (vendor lock-in) na dodavateli řešení a poplatky za provdené platby.

Výhodou jsou nízké náklady na zavedení a snadná integrace do systému. 

[< Zpět](../ "Zpět do adresáře Monolit")
