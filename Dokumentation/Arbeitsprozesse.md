# Meetings / Arbeitsprozesse

Unser Team arbeitet **Scrum**-like, angepasst an den Schulalltag: Wir machen ein Meeting einmal pro Woche im Unterricht.

## Rollen

| Rolle | Person | Aufgabe |
|---|---|---|
| Entwicklungsteam | Alle Teammitglieder | Setzt die Issues um, testet und dokumentiert |

## Sprints

- Ein Sprint dauert **1 Woche** (von Unterrichtstag zu Unterrichtstag).
- Am Ende jedes Sprints soll ein lauffähiges, getestetes Inkrement auf `main` liegen.

## Events

| Event | Wann | Dauer | Inhalt |
|---|---|---|---|
| Meeting | Ende des Unterrichtstags | 15- 30 min | Issues und Arbeit die erledigt wurde besprechen, notieren, reflektieren und planen für das nächste mal.|
Die Ergebnisse aller Meetings werden in der [Meeting-Dokumentation](meeting_documentations.md) festgehalten.

## Artefakte

- **Product Backlog:** Alle GitHub Issues sind auf dem Kanban Board, nach Priorität sortiert.
- **Sprint Backlog:** Die Issues, die im Sprint Planning für den aktuellen Sprint ausgewählt wurden.
- **Inkrement:** Der lauffähige Stand auf `main` am Ende des Sprints.

## Ablauf eines Tasks

1. Issue auf dem Kanban Board von **Todo** nach **In Progress** schieben und sich selbst zuweisen.
2. Branch erstellen: `<Issue-Nummer>-<kurze-beschreibung>` (Automatic innerhalb dem Issue erstellen).
3. Umsetzen, committen und einen Pull Request auf `main` eröffnen.
4. Issue nach **Review** schieben. Ein anderes Teammitglied prüft den Pull Request.
5. Nach dem Merge das Issue nach **Done** schieben.


