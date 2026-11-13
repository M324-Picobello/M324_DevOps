Extracted from https://gitlab.com/ch-tbz-it/Stud/m324/-/blob/main/LernenMitKI/KI-Nutzungsrahmen_M324.md?ref_type=heads

![TBZ Logo](../x_gitres/tbz_logo.png)

[TOC]

# KI-Nutzungsrahmen M324

Dieser Nutzungsrahmen gilt für alle Theorie-, Praxis- und Dokumentationsaufträge im Modul 324. KI wird als Lernhilfe eingesetzt, nicht als Ersatz für Ihre eigene Handlungskompetenz. Die fachliche Verantwortung für Code, Tests, Pipelines, Deployments, Prozesse und Dokumentation bleibt immer bei Ihnen.

## Gemeinsame Grundlage

Die allgemeine Referenz ist [KI-Kompetenz](https://gitlab.com/ch-tbz-it/Stud/allgemein/ki-kompetenz). Das dort beschriebene [Vierphasenmodell für Lehrpersonen](https://gitlab.com/ch-tbz-it/Stud/allgemein/ki-kompetenz/-/blob/main/KI-Kompetenz_f%C3%BCr_LP.md#das-4-phasenmodell-ki-sandwich) wird hier auf M324 übertragen. Grundwissen, kritisches Prüfen, Datenschutz und verantwortlicher Einsatz gelten auch im DevOps-Projekt.

KI-Nutzung ist erlaubt, aber nicht verpflichtend. Bewertet wird keine Anzahl von Prompts. Ohne KI genügt die entsprechende Angabe; die fachlichen Erwartungen gelten für alle. Das freiwillige Lernjournal D5 ist keine Voraussetzung für verpflichtende Nachweise.

## Roter Faden

![M324 Roter Faden für KI-Nutzung](ki-roter-faden-m324.svg)

| Phase | Einsatz im Modul | KI-Status | Nachweis |
| --- | --- | --- | --- |
| 1. Grundlagen aufbauen | DevOps-Begriffe, CALMS, Three Ways, CI/CD und Branching anhand der Unterlagen erarbeiten | Stark eingeschränkt; Kernbegriffe zunächst ohne KI | Erste eigene Erklärung und Quellenbezug |
| 2. Festigen | Fragen beantworten, Beispiele untersuchen, Fehler korrigieren und üben | Tutor, Coach und Sparringpartner mit abgestuften Hinweisen | Eigene Antworten und kurze Selbstprüfung ohne KI |
| 3. Anwenden | Planen, Varianten beurteilen, Code, Tests, CI/CD und Betriebsvalidierung umsetzen | Berater, Reviewer und Debugging-Hilfe | Begründete Entscheidungen, Tests, Logs und Pipeline-Ausgaben |
| 4. Nachweisen | Team-Fachgespräch mit Lehrperson, Walkthrough und Transfer | Keine KI während des Nachweises | Individuell erklären, begründen, vorhersagen und prüfen |

Diese Phasen wiederholen sich bei jedem neuen Kernthema. T-Aufträge umfassen Grundlagen und Festigung; P-Aufträge ermöglichen Anwendung und Transfer. Die schriftliche Abgabe kann in den erlaubten Arbeitsphasen mit KI-Unterstützung entstehen. Der Verständnisnachweis erfolgt im [Team-Fachgespräch](../Projekt/Team-Fachgespraeche.md) ohne KI.


## Erlaubt

- KI als Tutor nutzen, um DevOps-Konzepte, Fehlermeldungen, Testarten, Pipeline-Schritte oder Deployment-Strategien besser zu verstehen.
- KI für Variantenvergleiche einsetzen, z.B. GitLab vs. GitHub Actions, Docker Compose vs. Kubernetes, Blue/Green vs. Canary.
- KI für Review-Fragen, Debugging-Hypothesen, Testideen, Edge Cases und Monitoring-Metriken einsetzen.
- KI-generierte Vorschläge mit Unit Tests, Integrationstests, CI/CD-Logs, lokalen Befehlen, Screenshots oder offiziellen Quellen prüfen.
- KI zur Reflexion verwenden: Was war hilfreich, was war falsch, was wurde verworfen, was wurde selbst entschieden?
- KI für sprachliche Verbesserung eigener Dokumentation verwenden, wenn Inhalt, Entscheidung und Verantwortung bei Ihnen bleiben.

## Nicht Erlaubt

- Aufgabenstellung kopieren und eine vollständige Abgabe unverstanden durch KI erstellen lassen.
- Code, Tests, Pipeline-Konfigurationen, Deployment-Skripte oder Erklärtexte übernehmen, die im Code-Walkthrough nicht erklärt werden können.
- KI-generierte Screenshots, Logs, Testergebnisse, Pipeline-Ausgaben oder Quellen vortäuschen.
- Passwörter, Tokens, private Keys, Kundendaten, Personendaten oder nicht freigegebene Betriebsinformationen in KI-Tools eingeben.
- KI während der hier beschriebenen Fachgespräche oder Lernchecks zum Kompetenznachweis verwenden.

## M324-Arbeitszyklus

Jeder Projektauftrag folgt bei KI-Nutzung dem gleichen Zyklus. Der Zyklus macht sichtbar, dass KI nicht am Anfang die fertige Lösung liefert, sondern zwischen eigenem Denken, gezielter Frage, Umsetzung, Prüfung und Reflexion eingebettet ist.

![M324 KI-Arbeitszyklus](ki-arbeitszyklus-m324.svg)

1. **Think:** Zuerst ohne KI klären, was Ziel, Kontext, Risiko und nächster Schritt sind.
2. **Prompt:** KI mit Modulkontext, eigenem Zwischenstand, konkreter Frage und klaren Grenzen nutzen.
3. **Do:** Vorschlag selbst umsetzen, anpassen oder bewusst verwerfen.
4. **Check:** Ergebnis mit Tests, Logs, Pipeline-Ausgaben, Review, Screenshots oder offiziellen Quellen prüfen.
5. **Reflect:** KI-Nutzung, Fehler, eigene Entscheidungen und Lernerkenntnisse kurz dokumentieren. Schliessen Sie den Chat und erklären Sie einen Zusammenhang oder bearbeiten Sie einen veränderten Fall ohne KI. Nutzen Sie erkannte Lücken für die nächste Übung.

Nachweise zum Arbeitszyklus gehören in die Projektdokumentation, das Lernjournal oder den KI-Nachweis. Dazu gehören insbesondere eigener Startplan, Promptauszug, geprüfter KI-Hinweis, Test-/Log-/Pipeline-Nachweis und eigene Schlussfolgerung.

## KI-Nachweis

Jede zentrale Abgabe enthält bei KI-Nutzung einen kurzen Nachweis zu einem ausgewählten, aussagekräftigen Einsatz mit Prüfbeleg. Vollständige Chatprotokolle sind nicht erforderlich. Der KI-Nachweis ist Teil der Projektdokumentation oder des Lernjournals und kein separates Zusatzprodukt.

```text
## KI-Nachweis

KI-Tool:
Zweck der Nutzung:
Eigener Startplan ohne KI:
Promptauszug oder Kurzfassung:
Wichtigste KI-Antwort:
Übernommene Vorschläge:
Angepasste oder verworfene Vorschläge:
Validierung durch Tests, Logs, Pipeline, Review oder Quellen:
Eigene Entscheidung / Eigenleistung:
```

Wenn keine KI verwendet wurde, wird dies ebenfalls notiert.

## Bewertungslogik

KI-Nutzung verbessert eine Bewertung nicht automatisch. Bewertet wird, ob die fachliche Leistung stimmt und ob der KI-Einsatz kontrolliert, transparent und lernförderlich war.

| Kriterium | Erwartung |
| --- | --- |
| Fachlichkeit | Code, Tests, Pipeline, Deployment oder Prozess funktionieren und sind fachlich korrekt. |
| Verständnis | Befehle, Dateien, Architektur, Prozesse und Entscheidungen können erklärt werden. |
| Validierung | KI-Vorschläge wurden mit Tests, Logs, Pipeline-Ausgaben, Review oder Quellen geprüft. |
| Transparenz | KI-Nutzung ist nachvollziehbar dokumentiert. |
| Eigenleistung | Eigener Anteil ist sichtbar und kann in einer Abnahme verteidigt werden. |

## Masterprompt Für M324

```prompt
[Rolle]
Du bist mein KI-Tutor im Study-Modus für das Modul 324 "DevOps-Prozesse mit Tools unterstützen".

[Kontext]
Ich arbeite an einem DevOps-Projekt mit User Stories, Git-Repository, Kanban, Branching-Strategie, Unit Tests, CI, CD, Deployment, Monitoring und kontinuierlicher Verbesserung.

[Regeln]
Gib mir keine fertige Lösung für meinen Auftrag. Stelle jeweils eine Frage und warte auf meine Antwort. Gib bei Schwierigkeiten zuerst einen Hinweis, danach bei Bedarf ein Teilbeispiel. Lass mich Entscheidungen begründen und Ergebnisse mit Tests, Logs, Pipeline-Ausgaben, Reviews oder offiziellen Quellen prüfen. Ein zweites KI-Modell allein ist kein Beleg. Fordere mich abschliessend auf, den Chat zu schliessen und einen veränderten Fall selbstständig zu bearbeiten.

[Arbeitsweise]
Führe einen Dialog: Kläre mein Lernziel und meinen Zwischenstand. Stelle dann eine einzelne Verständnisfrage und warte auf meine Antwort. Gib gezieltes Feedback und abgestufte Hilfen. Lass mich einen Prüfschritt selbst wählen und ausführen. Schlage erst nach dem Üben einen kurzen Eintrag zu Erkenntnis, Prüfbeleg und nächstem Lernschritt vor.

[Sprache]
Deutsch Schweiz, fachlich korrekt, knapp und praxisnah.
```

## Beispiel: Masterprompt Für P3 Continuous Integration

```prompt
[Rolle]
Du bist mein KI-Tutor im Study-Modus für das Modul 324 "DevOps-Prozesse mit Tools unterstützen".

[Kontext]
Ich arbeite an P3 Continuous Integration. Unser Team entwickelt ein Web API mit drei User Stories. Wir verwenden GitLab, eine Branching-Strategie mit main, develop und feature-Branches sowie Unit Tests aus P2. Ich habe bereits eine erste .gitlab-ci.yml erstellt, bin aber unsicher, ob Jobs, Stages und Branch-Trigger sinnvoll aufgebaut sind.

[Mein aktueller Stand]
Die Pipeline hat aktuell eine build-Stage und eine test-Stage. Die Unit Tests laufen lokal, aber in GitLab schlagen sie teilweise fehl. Ich möchte verstehen, wie ich die Pipeline stabiler mache und wie ich die Varianten sauber dokumentiere.

[Regeln]
Gib mir keine fertige Lösung für meinen Auftrag. Stelle jeweils eine Frage und warte auf meine Antwort. Gib bei Schwierigkeiten zuerst einen Hinweis, danach bei Bedarf ein Teilbeispiel. Lass mich Entscheidungen begründen und Ergebnisse mit Tests, Logs, Pipeline-Ausgaben, Reviews oder offiziellen Quellen prüfen. Ein zweites KI-Modell allein ist kein Beleg. Fordere mich abschliessend auf, den Chat zu schliessen und einen veränderten Fall selbstständig zu bearbeiten.

[Arbeitsauftrag]
1. Stelle mir nacheinander drei Rückfragen zu Repository, Testausführung und Branching-Strategie. Warte jeweils auf meine Antwort.
2. Erkläre kurz, worauf ich bei Stages, Jobs, Artefakten und Branch-Triggern achten soll.
3. Gib mir konkrete Prüfschritte für die Pipeline-Logs.
4. Schlage mir vor, wie ich zwei CI-Varianten vergleichen kann.
5. Sage mir, was ich im KI-Nachweis dokumentieren soll.

[Sprache]
Deutsch Schweiz, fachlich korrekt, knapp und praxisnah.
```

So verwenden Sie das Ergebnis:

1. Führen Sie die vorgeschlagenen Prüfschritte in Ihrer eigenen Pipeline aus.
2. Vergleichen Sie die KI-Hinweise mit den effektiven Pipeline-Logs.
3. Übernehmen Sie nur Vorschläge, die Sie technisch prüfen können.
4. Dokumentieren Sie Prompt, KI-Hinweis, Anpassung, Pipeline-Resultat und eigene Entscheidung im KI-Nachweis.
