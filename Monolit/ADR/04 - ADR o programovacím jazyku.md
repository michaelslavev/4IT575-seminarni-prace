# Rozhodnutí o programovacím jazyku

## ID
4

## Datum
26.01.2023

## Status
Schválené

## Context
Je třeba zvolit framework pro vytvoření systému registrace a platby kurzů pro širokou veřejnost i studenty pro server-side render aplikaci.

Tým vybírá z následujících alternativ:
- Symfony (PHP)
- Ruby on rails
- Next.js
- Spring
- ASP.NET
- Django

## Decision
Pro vznikající systém registrací a plateb kurzů bude využit framework Symfony.

## Consequences
PHP je nejvíce využívaným programovacím jazykem na straně serveru, který podporuje objektově orientované programování. Jelikož vnikl před skoro 30 lety,
tak nabízí mnoho frameworků, ze kterých si lze vybírat. Jedná se o open-source alternativu, což je pro projekt velice výhodné z důvodu nízkého rozpočtu
na IT. Syntaxe jazyka je jednoduchá a existuje velmi rozsáhlá dokumentace, což opět kompenzuje nízký rozpočet na IT, jelikož vývojáři nebudou mít
potíže se jazyk naučit, pokud to bude potřeba.

Symfony má velice rozsháhlou komunitu, je vhodné pro vývoj MVC aplikací a skill base vývojového týmu je orientovaný na tento framework.

[< Zpět](../ "Zpět do adresáře Monolit")
