Extracted from https://gitlab.com/ch-tbz-it/Stud/m324/-/blob/main/Projekt/Projekt4_Ticketsystem.md?ref_type=heads

[TOC]

# Projekt 4: Ticketsystem

Sie erstellen eine Applikation mit der Sie Tickets und Mitarbeiter verwalten können. Sie haben dabei die Rolle eines Anbieters und administrieren die Inhalte

Die folgenden User Stories sind vorgegeben, welche Sie in während der Leistungsmessung bearbeiten werden.

**Achtung**: Beide Mikroservices sind separate Projekte und sollen so behandelt werden. Sie können Sie sich gerne auch dazu entscheiden beide Mikroservices in unterschiedlichen Programmiersprachen abzubilden. Dies hat dann aber einen Mehraufwand bei den CI/CD Pipelines.

**Datenbank**: Da beide Mikroservices als separate Projekte gelten, sollten die auch unterschiedliche Datenbanken verwenden. Sie dürfen einfachhalber die gleiche Datenbank verwenden, dürfen aber nicht die Daten des anderen Mikroservice laden. Also konkret, Der Endpoint von User Story 3 muss die Mitarbeiter aus dem Endpoint von User Story 2 auslesen und nicht aus der Datenbank.



## Mikroservice 1: Verwaltung von Mitarbeitern

### User Story 1: Mitarbeiter erfassen

### User Story

Als Administrator des Systems möchte ich neue Mitarbeiter mit den relevanten Eigenschaften erfassen können, damit die Mitarbeiterdaten zentral verwaltet und für interne Prozesse genutzt werden können.

**Abnahmekriterien**
1. Der Administrator kann den *Vornamen* des Mitarbeiters eingeben (z. B. "Max").
2. Der Administrator kann den *Nachnamen* des Mitarbeiters eingeben (z. B. "Muster").
3. Der Administrator kann das *Beitrittsdatum* des Mitarbeiters zur Firma eingeben (z. B. "15.05.2021").
4. Der Administrator kann den *Skilllevel* als Supportmitarbeiter angeben (eine Zahl zwischen 1 und 5, z. B. 4).
5. Während der Erfassung wird eine eindeutige ID automatisch für jeden Mitarbeiter generiert.
6. Eine Validierung stellt sicher, dass der *Skilllevel* nur eine Zahl zwischen 1 und 5 ist.
7. Nach erfolgreicher Erfassung wird der Mitarbeiter in der Systemübersicht angezeigt.
8. Fehlerhafte Eingaben führen zu klaren Fehlermeldungen, die den Administrator zur Korrektur anleiten.

### User Story 2: Alle Mitarbeiter auslesen

### User Story

Als Administrator des Systems möchte ich alle erfassten Mitarbeiter auslesen können, damit ich eine Übersicht der bereits erfassten Mitarbeiter erhalte.

**Abnahmekriterien**
1. Der Administrator kann eine Liste aller erfassten Mitarbeiter abrufen.
2. Alle Felder der Mitarbeiter (Vorname, Nachname, Beitrittsdatum, Skilllevel, eindeutige ID) werden vollständig zurückgeliefert.
3. Die angezeigte Liste ist übersichtlich und strukturiert.
4. Der Abruf funktioniert auch bei einer großen Anzahl von erfassten Mitarbeitern ohne Verzögerungen.
5. Falls keine Mitarbeiter vorhanden sind, wird eine entsprechende Meldung angezeigt.
6. Fehlerhafte Abfragen führen zu klaren Fehlermeldungen.

## Mikroservice 2: Verwaltung von Tickets

### User Story 3: Ticket erfassen

### User Story

Als Administrator des Systems möchte ich Tickets erfassen und einem Mitarbeiter zuweisen können, damit die Bearbeitung von Aufgaben transparent verwaltet und der Fortschritt nachvollziehbar ist.

**Abnahmekriterien**
1. Der Administrator kann den *Status* des Tickets auswählen: Open, In Progress, Review, Done.
2. Der Administrator kann einen *Titel* für das Ticket eingeben.
3. Der Administrator kann einen *Text* zur Beschreibung des Tickets eingeben.
4. Der Administrator kann das *Datum*, an dem das Ticket in den Status "Review" gesetzt wurde, eingeben (UTC).
5. Der Administrator kann das *Datum*, an dem das Ticket in den Status "Done" gesetzt wurde, eingeben (UTC).
6. Ein *Mitarbeiter* muss dem Ticket immer zugewiesen werden. Ohne Zuweisung kann das Ticket nicht gespeichert werden.
7. Eine Validierung stellt sicher, dass die Datumsangaben (Review- und Done-Datum) nur gesetzt werden können, wenn die entsprechenden Statuswechsel erfolgt sind.
8. Nach erfolgreicher Erfassung wird das Ticket mit allen Details in der Systemübersicht angezeigt.
9. Fehlerhafte Eingaben (z. B. fehlender Mitarbeiter oder falsches Datum) führen zu klaren Fehlermeldungen, die den Administrator zur Korrektur anleiten.

**Wichtig:** Dieser Endpoint verwendet den ersten Microservice um die Eingabe des Mitarbeiters zu validieren, muss also den Endpoint aufrufen.

