Extracted from https://gitlab.com/ch-tbz-it/Stud/m324/-/blob/main/LernenMitKI/Promptbibliothek_M324.md?ref_type=heads

# Promptbibliothek M324

Diese Prompts sind Startpunkte. Sie müssen mit dem konkreten Auftrag, dem eigenen Zwischenstand, relevanten Dateien, Fehlermeldungen, Pipeline-Ausgaben und Testergebnissen ergänzt werden.

## DevOps-Tutor und Lerncoach

Nutzen Sie diesen Dialog nach einer ersten eigenen Grundlagenarbeit. Allgemeine Referenz: [KI-Kompetenz](https://gitlab.com/ch-tbz-it/Stud/allgemein/ki-kompetenz). Die [Team-Fachgespräche](../Projekt/Team-Fachgespraeche.md) selbst finden ohne KI statt.

```prompt
[Rolle]
Sei mein Tutor, Coach und Sparringpartner für M324. Gib keine fertige Lösung für meinen Auftrag.
[Lernziel und Stand]
Ich möchte [Zusammenhang] verstehen. Meine erste eigene Erklärung lautet: [Erklärung]. Offen ist: [Frage].
[Dialog]
Stelle jeweils eine fachliche Frage und warte auf meine Antwort. Prüfe meinen Denkweg. Gib bei Schwierigkeiten zuerst einen Hinweis und erst bei Bedarf ein Teilbeispiel. Lass mich Entscheidungen selbst begründen. Prüfe mein Verständnis später mit einem veränderten Fall, ohne dessen Lösung vorwegzunehmen.
[Prüfung]
Lass mich Aussagen mit Unterrichtsunterlagen, offiziellen Quellen, Tests oder Logs unabhängig prüfen. Ein weiteres KI-Modell allein genügt nicht als Beleg.
[Abschluss]
Fordere mich auf, den Chat zu schliessen und den Zusammenhang selbstständig zu erklären oder anzuwenden. Frage danach, was gelang und was ich weiter üben muss. Schreibe keine fertige Reflexion.
```

## Technologieentscheid Review

```prompt
Reviewe unsere Technologieentscheidung für M324. Kontext: [Projekt], [Programmiersprache], [Datenbank], [Git-Plattform], [Teamgrösse]. Prüfe Testbarkeit, CI/CD-Eignung, Betrieb, Sicherheit und Team-Fit. Gib maximal fünf Risiken und konkrete Prüffragen. Entscheide nicht für uns.
```

## User-Story Und API Review

```prompt
Reviewe diese User Story und den geplanten API-Endpoint. Prüfe Akzeptanzkriterien, Happy Path, Sad Paths, Datenvalidierung, Fehlerfälle und Testbarkeit. Gib mir Testideen, aber keine fertige Implementierung.
```

## Unit-Test Review

```prompt
Reviewe diese Unit Tests für M324. Prüfe, ob Happy Paths, Sad Paths, Randfälle, Isolation und Lesbarkeit abgedeckt sind. Markiere Lücken und schlage konkrete zusätzliche Testfälle vor. Ich muss alle Vorschläge selbst implementieren und ausführen.
```

## Code Review

```prompt
Reviewe diesen Code im Kontext von M324. Prüfe Logik, Lesbarkeit, Fehlerbehandlung, Testbarkeit, einfache Architektur und Sicherheitsrisiken. Gib maximal fünf Hinweise. Erkläre, wie ich jeden Hinweis mit Tests oder manuellen Checks prüfen kann.
```

## CI Pipeline Review

```prompt
Reviewe diese CI-Konfiguration. Prüfe Build-Schritte, Teststufen, Branch-Trigger, Artefakte, Caching, Fehlerbehandlung und Nachvollziehbarkeit. Gib mir Prüfschritte und erwarte Pipeline-Ausgaben, mit denen ich die Korrektheit belegen kann.
```

## CD Und Deployment Review

```prompt
Reviewe unser Deployment-Konzept. Prüfe Umgebungen, Konfiguration, Secrets, Rollout, Rollback, Skalierbarkeit, Ausfallsicherheit und Nachweisbarkeit. Vergleiche Varianten, aber gib keine pauschale Empfehlung ohne Bezug zu unserer Umgebung.
```

## Monitoring Und Kennzahlen

```prompt
Hilf mir, sinnvolle Monitoring- und DevOps-Kennzahlen für unser M324-Projekt zu definieren. Kontext: [Architektur], [Deployment], [Teamprozess]. Unterscheide technische Metriken, Prozessmetriken und fachliche Kennzahlen. Gib zu jeder Kennzahl an, wie wir sie erheben und prüfen können.
```

## Reflexion

```prompt
Hilf mir, meine KI-Nutzung für [Auftrag] zu reflektieren. Stelle mir Fragen zu: Was habe ich zuerst selbst geplant? Wo war dein Vorschlag falsch oder unvollständig? Welche Tests, Logs oder Pipeline-Ausgaben habe ich geprüft? Welche Entscheidung habe ich selbst getroffen? Formuliere keine fertige Reflexion, sondern führe mich mit Fragen.
```
