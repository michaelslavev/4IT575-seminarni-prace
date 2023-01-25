# Pohled komponent

Tento pohled ukazuje komponenty systému pro registrace

## Primary presentation

### UML

![Diagram komponent](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/a639e43ee656512c83023e5d2e2e88c45b5c2c3e/SOA/assets/SOA_component-diagram.jpg "Diagram komponent")

### Vysvětlivka diagramu

- **Komponenta** - Komponenta je blok logické jednotky systému, o něco vyšší abstrakce než třídy.

![Komponenta](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/SOA/assets/prvky-diagram%C5%AF/Komponenta.jpg "Označení komponenty")

- **Subsystem** - Subsystem je logická část systému, o úroveň vyšší abstrakce jak komponenty.

![Subsystem](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/SOA/assets/prvky-diagram%C5%AF/Subsystem.jpg "Označení subsystému")

- **Rozhraní** - Rozhraní poskytované nebo konzumované komponentou. V této tzv. lollipop notaci z levé strany konzumované, z pravé poskytované. V diagramu se objevují i odděleně, kde je půlkruh konzumované a kruh poskytované rohraní.

![Rozhraní](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/SOA/assets/prvky-diagram%C5%AF/Interface.jpg "Označení rozhraní")

- **Asociace** - Asociace značí semantický vztah mezi komponentami.

![Asociace](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/SOA/assets/prvky-diagram%C5%AF/Line.jpg "Označení asociace")

- **Závislost** - Závislost značí vztah, kde je jedna komponenta pro svojí funkčnost závislá na té druhé. Šipka vede od závislé komponenty.

![Závislost](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/SOA/assets/prvky-diagram%C5%AF/Dependency.jpg "Označení závislosti")

- **Port** - Port slouží k vystavení rozhraní z komponenty/subsystému.

![Port](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/SOA/assets/prvky-diagram%C5%AF/Port.jpg "Označení portu")

## Element catalog

- **Subsystémy**

  - **Frontend** - Část systému s grafickým rozhraním pro uživatele.
  - **Backend** - Část systému s aplikační logikou na serveru.
  - **DBMS** - Část systému s databází.
  - **Externí** - Externí část systému, která je ale potřebná pro funkčnost.

- **Komponenty**

  - **Uživatelské rozhraní** - Grafické rozhraní pro uživatele, pomocí něhož bude uživatel spravovat aplikaci.
  - **Enterprise service bus** - Komunikační systém mezi aplikacemi v SOA.
  - **Správa kurzů** - Služba přes kterou jsou spravovány kurzy.
  - **Správa uživatelů** - Služba pro správu uživatelů.
  - **Fakturace** - Služba, která generuje a zasílá faktury a daňové doklady uživatelům.
  - **Administrace** - Služba pro administraci aplikace.
  - **Platby** - Služba pro komunikaci se serverem platební brány.
  - **Platební brána** - Externí komponenta umožňující platby.
  - **Databáze** - Databáze v MySQL obsahující všechna data.

- **Rohraní**

  - **Endpointy** - Vystavené endpointy pro komunikaci se službami.
  - **Kurzy** - Data a funkce ohledně kurzů.
  - **Uživatelé** - Data a funkce ohledně uživatelů.
  - **Faktury, daňové doklady** - Data a funkce ohledně fakturace.
  - **Administrace** - Data a funkce ohledně administrace.
  - **Platby** - Data a funkce ohledně plateb.
  - **API pro platební operace** - Vystavená REST API serveru platební brány.
  - **Data** - Veškerá data aplikace, která jsou uložena v databázi.

## Context diagram

TODO

## Variability guide

TODO

## Rationale

TODO

## Related Views

TODO

[< Zpět](../../../README.md "Zpět na přehled seminární práce")
