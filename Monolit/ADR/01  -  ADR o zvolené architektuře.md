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
Pro vznikající systém registrací a plateb kurzů budeme využívat monolitickou architekturu.

Bude exisistovat server, na kterém bude nasazena aplikace poskytující požadovanou funkcionalitu. Komunikace s uživatelem bude probíhat pomocí protokolu HTTPS.   

## Consequences
Zvolením této architektury je snadná a rychlá implementace požadované funkcionality, což umožňuje splnění požadvků na nízké náklady a rychlost dodání. Další výhodou je 
jednotný codebase, umožňující menší náklady na vývoj.
Nevýhodou tohoto řešení je nízká škálovatelnost a složitá implementace budou změn.

[< Zpět](../ "Zpět do adresáře Monolit")
