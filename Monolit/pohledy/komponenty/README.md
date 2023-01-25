# Pohled komponent

Tento pohled ukazuje komponenty systému pro registrace

## Primary presentation

### UML

![Diagram komponent](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/6c99746569b72b512de98eee781bb2a15e580592/Monolit/assets/Monolit_component-diagram.jpg "Diagram komponent")

### Vysvětlivka diagramu

- **Komponenta** - Komponenta je blok logické jednotky systému, o něco vyšší abstrakce než třídy.

<img src="https://github.com/michaelslavev/4IT575-seminarni-prace/blob/6c99746569b72b512de98eee781bb2a15e580592/Monolit/assets/prvky-diagram%C5%AF/Component.jpg" alt="Komponenta" width="200"/>

- **Subsystem** - Subsystem je logická část systému, o úroveň vyšší abstrakce jak komponenty.

<img src="https://github.com/michaelslavev/4IT575-seminarni-prace/blob/6c99746569b72b512de98eee781bb2a15e580592/Monolit/assets/prvky-diagram%C5%AF/Subsystem_app.jpg" alt="Označení subsystému" width="200"/>

- **Rozhraní** - Rozhraní poskytované nebo konzumované komponentou. V této tzv. lollipop notaci z levé strany konzumované, z pravé poskytované. V diagramu se objevují i odděleně, kde je půlkruh konzumované a kruh poskytované rohraní.

<img src="https://github.com/michaelslavev/4IT575-seminarni-prace/blob/6c99746569b72b512de98eee781bb2a15e580592/Monolit/assets/prvky-diagram%C5%AF/Interface_empty.jpg" alt="Označení rozhraní" width="100"/>

- **Asociace** - Asociace značí semantický vztah mezi komponentami.

<img src="https://github.com/michaelslavev/4IT575-seminarni-prace/blob/34c5a0e14131c9ad59a4973c251e47fa75ead01f/Monolit/assets/prvky-diagram%C5%AF/Line.jpg" alt="Označení asociace" width="30"/>

- **Závislost** - Závislost značí vztah, kde je jedna komponenta pro svojí funkčnost závislá na té druhé. Šipka vede od závislé komponenty.

<img src="https://github.com/michaelslavev/4IT575-seminarni-prace/blob/34c5a0e14131c9ad59a4973c251e47fa75ead01f/Monolit/assets/prvky-diagram%C5%AF/Dependency.jpg" alt="Označení závislosti" width="100"/>

- **Port** - Port slouží k vystavení rozhraní z komponenty/subsystému.

<img src="https://github.com/michaelslavev/4IT575-seminarni-prace/blob/34c5a0e14131c9ad59a4973c251e47fa75ead01f/Monolit/assets/prvky-diagram%C5%AF/Port.jpg" alt="Označení portu" width="100"/>

## Element catalog

- **Subsystémy**

  - **Aplikace** - Celá aplikace v monolitické architektuře.
  - **DBMS** - Část systému s databází.
  - **Externí** - Externí část systému, která je ale potřebná pro funkčnost.

- **Komponenty**

  - **Monolit** - Jedna komponenta obsahující prezentační, business a persistentní vrstvu.
  - **Prezentační vrstva** - Uživatelské rozhraní.
  - **Business logika** - Veškerá business logika aplikace.
  - **Persistentní vrstva** - Vrstva pro persistenci dat, ORM a komunikaci s databází.
  - **Platební brána** - Externí komponenta umožňující platby.
  - **Databáze** - Databáze v MySQL obsahující všechna data.

- **Rohraní**

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

[< Zpět](../../ "Zpět do adresáře Monolit")
