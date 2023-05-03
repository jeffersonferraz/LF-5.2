# Lernfeld 5.2
Objektorientierte Modellierung

## UseCase-Diagramm
<br><img src="/Diagramme/Use-Case-Diagramm.png"><br>

## *Domänenwörterbuch*

### Angestellter:

Der Angestellte führt den Verwaltungsprozess seitens des Autoverleihs durch.

Die folgenden Anwendungsfälle können durchgeführt werden.

- **Auto verleihen** <br>
Das Auto wird an Kunden ausgegeben, inkludiert den UseCase “Auto ausleihen” des ***Kunden***.

- **Übersicht ausgeben** <br>
Das System gibt eine Übersicht der verfügbaren Autos aus. Die Übersicht wird für den UseCase “Auto ausleihen” des ***Kunden*** benötigt.

- **Auto entgegennehmen** <br>
Das Auto wird nach dem Verleih entgegengenommen. Inkludiert den UseCase “Auto zurückgeben” des ***Kunden***.

### Kunde:

Der Kunde möchte bei der Autovermietung ein Auto ausleihen. Die folgenden Anwendungsfälle können dann durchgeführt werden.

- **Auto ausleihen** <br>
Der Kunde wählt ein Auto und leiht es aus. Dazu wird den UseCase “Übersicht ausgeben” des ***Angestellten*** genutzt.

- **Auto zurückgeben** <br>
Der Kunde gibt das Auto zurück. Der UseCase “Auto entgegennehmen” des ***Angestellten*** wird dabei auch ausgeführt.

- **Auto vorbestellen** <br>
Der Kunde bestellt ein Auto zur Ausleihe vor. Dieser UseCase kann vor dem UseCase “Auto ausleihen” ausgeführt werden.

- **Auto volltanken** <br>
Der Kunde tankt das Auto, bevor er es zurückgibt. Dieser UseCase ist im UseCase “Auto zurückgeben” inkludiert.

### Premiumkunde:
Verfügt über alle Möglichkeiten des Kunden, mit jedoch Vorteile. Spezielle UseCases für den Premiumkunden:

- **Auto an Nachtschalter zurückgeben** <br>
Das Auto kann außerhalb der regulären Öffnungszeiten zurückgegeben werden. Darauf folgt der UseCase “Auto zurückgeben”.


## Aktivitätsdiagramm
<br><img src="/Diagramme/Aktivitätsdiagramm.png"><br>

## Klassendiagramm
<br><img src="/Diagramme/Klassendiagramm.png"><br>
