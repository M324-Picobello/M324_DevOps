## DevOps-Kultur: CALMS und The Three Ways

### 1. Verständnis CALMS

#### 1. Culture
Dies betrifft nicht nur das Entwicklungsteam, sondern auch das Unternehmen selbst. Teams, die gut miteinander kommunizieren und zusammenarbeiten, um ein festgelegtes Ziel zu erreichen. Zur Kultur gehört auch, wie Technologie eingesetzt wird, um die Vorgaben der anderen Bereiche zu erfüllen.

**In der Fallstudie:** Die Kultur bei TechNova Solutions wies erhebliche Mängel auf: Teams und Prozesse waren voneinander isoliert, was zu Konflikten und Spannungen zwischen den Entwicklungs- und Betriebsteams führte. Dank der DevOps-Transformation sowie der durchgeführten Workshops und Teambuilding-Aktivitäten herrscht im Unternehmen nun eine weitaus gesündere Kultur für die Produktentwicklung, wodurch auch die Kundenzufriedenheit gestiegen ist.

#### 2. Automation
Menschen sind fehleranfällig, daher ist die Reduzierung des manuellen Arbeitsaufwands für ein produktives Arbeitsumfeld von entscheidender Bedeutung. Dies erfordert gründliche Tests, um sicherzustellen, dass die Automatisierung korrekt funktioniert.

**In der Fallstudie:** Zu viele Prozesse wurden manuell durchgeführt, was zu langen Wartezeiten bei der Bereitstellung und der Behebung von Fehlern führte. Durch die Einführung einer geeigneten CI/CD-Pipeline und strenger automatisierter Tests konnten Funktionen und Fehlerbehebungen schneller geprüft und bereitgestellt werden, wodurch sich die Deployment-Interval von halbjährlich auf wöchentlich verkürzten.

#### 3. Lean
Dieses Prinzip bedeutet, dass die Software zuverlässig ist und eine kontinuierliche Verbesserung sowie die Ausrichtung auf langfristige Ziele ermöglicht. Die Pipeline ist robust genug, um herauszufinden, was im System funktioniert und was nicht.

**In der Fallstudie:** Die Testverfahren waren unzureichend und viele Prozesse waren überlastet, was die Zuverlässigkeit und die Möglichkeiten zur Verbesserung der Software beeinträchtigte und somit zu einer mangelnden Schlankheit des Systems führte. Nach der DevOps-Transformation, die mit einer konsequenten Verbesserung der Testverfahren, der Automatisierung und des Informationsaustauschs sowie vor allem mit kontinuierlicher Verbesserung einherging, wurde die "Lean"-heit des Systems erheblich gesteigert.

#### 4. Measurement
Mithilfe von Metriken, Aufzeichnungen, Tracing und Tests sollte es möglich sein, die verschiedenen Aspekte der Software zu messen, beispielsweise was wie vorgesehen funktioniert und was verbessert oder behoben werden muss. Ein gut konzipiertes System zur Ermittlung dieser Messwerte macht das System „Lean“.

**In der Fallstudie:** Auch wenn dies zunächst nicht erwähnt wurde, ist klar, dass im Zuge der Umstrukturierung auch eine ordnungsgemässe Erfassung verschiedener Metriken, Aufzeichnungen und Trace-Daten eingeführt wurde. Dies ermöglicht es sowohl dem Entwicklungsteam als auch dem Betriebsteam, Probleme schneller zu erkennen und zu beheben sowie die Häufigkeit von Bereitstellungen, die Durchlaufzeit und die MTTR (Mean Time to Repair) zu messen.

#### 5 Sharing
In diesem Bereich geht es um den Wissensaustausch innerhalb des Teams, sowohl über Erfahrungen als auch über begangene und behobene Fehler. Eine gesunde Kultur beinhaltet dieses Verhalten.  

**In der Fallstudie:** Die mangelnde Kommunikation zwischen den Entwicklungs- und Betriebsteams sowie die Isolation der Prozesse führten dazu, dass Fehler und Features nicht rechtzeitig behoben werden konnten, was zu Konflikten und Spannungen zwischen den Teams führte. Die einführung von eine interne Wiki für Wissenaustausch, interne Lernformate und Erfahrungsberichte haben massgeblich zur Lösung dieses Problems beigetragen.


### 2. Verständnis The Three Ways

#### 1. Systems Thinking (Flow)
Man betrachtet den ganzen Weg von der Idee bis zum Kunden als ein System, nicht nur den eigenen Teil. Ziel ist ein schneller, reibungsloser Fluss von Dev zu Ops: kleine Änderungen, sichtbare Arbeit, wenig Übergaben und Automatisierung statt manueller Schritte.

**In der Fallstudie:** TechNova hatte Silos (Entwicklung, Test, Betrieb isoliert) und manuelle Tests/Deployments, deshalb dauerten Releases sechs Monate. Mit der CI/CD-Pipeline und Kanban-Boards wurde der Flow sichtbar und automatisiert. Releases kommen jetzt wöchentlich statt halbjährlich.

#### 2. Amplify Feedback Loops (Feedback)
Rückmeldungen sollen schnell vom Betrieb und vom Kunden zurück zur Entwicklung fliessen. Automatisierte Tests, häufige Deployments und Reviews zeigen Fehler früh, solange sie noch günstig zu beheben sind.

**In der Fallstudie:** Kundenfeedback wurde früher zu langsam umgesetzt. Durch automatisierte Tests in der Pipeline, wöchentliche Releases und Metriken (Deployment-Frequenz, Lead Time, MTTR) bekommt TechNova jetzt schnell Feedback. Die Kundenzufriedenheit ist gestiegen.

#### 3. Continual Learning and Experimentation (Lernkultur)
Fehler sind Chancen zum Lernen, nicht Anlass für Schuldzuweisungen. Wissen wird offen geteilt, und Experimente sind erlaubt und werden von der Führung unterstützt.

**In der Fallstudie:** Früher führten Fehler oft zu Schuldzuweisungen. Mit Workshops, Teambuilding, einem Wiki, internen Lernformaten und Erfahrungsberichten hat TechNova eine offene Lern- und Fehlerkultur aufgebaut.


### 3. Vergleich CALMS und The Three Ways

| Gemeinsame Idee                                 | CALMS-Bezug                                                             | Bezug zu The Three Ways                                                                                       | Beispiel aus der Fallstudie                                                                               | Eigene Einschätzung                                                                                                              |
| ----------------------------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Silos abbauen, gemeinsames Ziel**             | **Culture:** Dev und Ops arbeiten zusammen statt gegeneinander          | **1. Weg:** Das ganze System von Dev bis Kunde verstehen, keine Insellösungen                                 | Entwicklung, Test und Betrieb arbeiteten isoliert. Workshops und Teambuilding brachten die Teams zusammen | Das ist die Basis. Ohne Zusammenarbeit bringt auch die beste Pipeline wenig, weil Probleme zwischen den Teams hängen bleiben     |
| **Manuelle Arbeit ersetzen, schneller liefern** | **Automation:** Tests, Build, Deployment und Monitoring automatisieren  | **1. Weg:** Flow beschleunigen, Wartezeiten senken. **2. Weg:** Automatisierte Tests geben schnelles Feedback | Manuelle, fehleranfällige Tests und Deployments wurden durch eine CI/CD-Pipeline ersetzt                  | Der sichtbarste Hebel, aber gefährlich, wenn man ihn allein betrachtet: Wer nur automatisiert, automatisiert auch die Fehler mit |
| **Verschwendung vermeiden, kleine Schritte**    | **Lean:** Alles ohne Mehrwert entfernen, kontinuierlich verbessern      | **1. Weg:** Kleine Änderungen, Arbeit sichtbar machen, WIP-Limits, unnötige Übergaben streichen               | Kanban-Boards machen die Arbeit sichtbar. Releases kommen wöchentlich statt halbjährlich                  | Wird oft unterschätzt (bei CALMS sogar «optional»), ist aber der Grund, warum kleine Releases überhaupt möglich sind             |
| **Entscheiden auf Basis von Daten/Feedback**    | **Measurement:** Metriken wie Lead Time auswerten                       | **2. Weg:** Feedback aus Betrieb und von Kunden schnell zur Entwicklung zurückführen                          | Metriken: Deployment-Frequenz, Lead Time, MTTR. Kundenfeedback wird schneller umgesetzt                   | Ohne Messung wäre der Erfolg nur ein Gefühl. Erst die Zahlen zeigen, ob sich wirklich etwas verbessert hat                       |
| **Aus Fehlern lernen, Wissen teilen**           | **Sharing** (+ Culture): Fehler und Lernerfahrungen offen dokumentieren | **3. Weg:** Kontinuierliches Lernen, Experimente, kein Fingerpointing                                         | Früher gab es Schuldzuweisungen. Heute gibt es ein Wiki, interne Lernformate und Erfahrungsberichte       | Langfristig am wichtigsten, aber am schwierigsten. Es braucht Zeit und Rückhalt vom Management                                   |

#### Unterschiede
- **CALMS** ist eine Art **Checkliste**: Welche fünf Bereiche müssen bei einer DevOps-Transformation gemeinsam wachsen? Messen (Measurement) ist darin ein eigener Bereich.
- **The Three Ways** beschreiben die **Richtung**, in der die Arbeit fliesst: vorwärts zum Kunden (Flow), zurück zur Entwicklung (Feedback) und als laufende Verbesserung (Lernen).
- CALMS nennt Automatisierung ausdrücklich. Bei den Three Ways ist sie nur ein Mittel für Flow und Feedback.

### 4. Bewertung Der Transformation

Kultur und Automation

Die grösste Veränderung betraf die Kultur. Indem die notwendigen Werkzeuge bereitgestellt und beiden Teams vermittelt haben, wie sie im Rahmen von DevOps zusammenarbeiten, sind sie nun in der Lage, Probleme schneller zu lösen, Lösungen anzubieten und zu diskutieren, anstatt sich gegenseitig die Schuld zu geben, und haben einen klareren Blick auf die zu erreichenden Ziele. Auch das „Sharing“ Bereich spielt eine entscheidende Rolle für die Unternehmenskultur, da ein Informationsaustausch notwendig ist, damit diese gedeihen kann. Dies zeigt sich deutlich nach der Einführung von Workshops, Teambuilding-Aktivitäten und internen Wikis daran, wie sich die Zusammenarbeit zwischen den Teams verbessert hat und die Kundenzufriedenheit gestiegen ist.

Eine weitere wichtige Veränderung war die konsequente Automatisierung, da zuvor viele Prozesse manuell durchgeführt wurden, was zu langen Deployment-zyklen sowie fehleranfälligen Tests und Deployments führte und somit weiteren Zeitverlust verursachte. Zeit ist einer der drei wichtigsten Faktoren bei der Arbeit an einem Projekt, daher handelte es sich hierbei um ein grosses Problem, das gelöst werden musste. Durch die Einführung einer CI/CD-Pipeline und eines Kanban-Boards zur Organisation von Issues konnte die Bereitstellungszeit von zweimal jährlich auf wöchentlich verkürzt werden – eine enorme Verbesserung, die schnellere Reaktionszeiten bei der Fehlerbehebung und eine konsistentere Einführung neuer Funktionen ermöglicht.


### 5. Transfer: Zahlungsverarbeitung zwischen Acquirer, Händler und Banken

#### Ausgangslage
Ein Schweizer Zahlungsdienstleister wickelt im Hintergrund den Geldfluss für mobile Zahlungen ab. Er leitet Autorisierungen zwischen Händlern, Acquirern und den Banken der Zahlenden weiter. Ausserdem übernimmt er **Clearing und Settlement**: Er berechnet, wer wem wie viel schuldet, und sorgt dafür, dass die Händler ihr Geld ausgezahlt bekommen. Daran beteiligt sind ein Team für die Echtzeit-Transaktionsverarbeitung, ein Team für Clearing and Settlement (Batch-Verarbeitung), ein Integrationsteam für die Anbindung neuer Acquirer und Händler, der Betrieb sowie Security and Compliance (PCI DSS, regulatorische Vorgaben).

#### Probleme
- Deployments sind nur in **festen Wartungsfenstern** erlaubt (z. B. einmal im Monat nachts am Wochenende), und vorher müssen ein Change Advisory Board und Compliance zustimmen. Darum werden viele Änderungen gesammelt und auf einmal ausgerollt. Geht etwas schief, ist der Rollback gross und riskant.
- Deployments und Konfigurationsänderungen (z. B. neue Gebührenregeln für einen Acquirer) werden teilweise **manuell nach Checkliste** gemacht.
- Fehler im Settlement fallen oft erst **am nächsten Tag oder noch später** auf: bei der Abstimmung (Reconciliation) mit den Banken oder wenn sich ein Händler meldet, weil eine Auszahlung fehlt oder falsch ist.
- Bei Störungen schieben sich Integrationsteam, Betrieb und Acquirer gegenseitig die Verantwortung zu. Die Ursache wird oft erst nach langer Suche durch Log-Dateien gefunden.

#### Am stärksten zu verbessern

**CALMS: Lean**
Das grösste Problem ist **Waste** im Prozess: Wartezeiten bis zum nächsten Wartungsfenster, mehrfache Übergaben und Freigaben, bei denen die Entscheider die technische Änderung kaum beurteilen können.
- *Massnahme:* Kleine Standard-Änderungen (z. B. Konfiguration einer neuen Händleranbindung) bekommen einen vorab genehmigten, automatisierten Weg. Compliance-Kontrollen (z. B. Vier-Augen-Prinzip, Audit-Log) werden direkt in die Pipeline eingebaut statt als manuelle Abnahme am Schluss. Mit **Blue-Green-Deployments** lassen sich Änderungen ohne Unterbruch einspielen, sodass man nicht mehr auf das Wartungsfenster angewiesen ist.

**Three Ways: Second Way (Feedback)**
Bei Geldflüssen muss jeder Fehler schnell auffallen, weil sonst Händler falsch ausbezahlt werden oder Geld «hängen bleibt». Heute ist das Feedback viel zu langsam: Es kommt über die tägliche Abstimmung oder über Beschwerden von Händlern.
- *Massnahme:* **Laufende Abstimmung** statt nur einmal am Tag im Batch: Autorisierte und abgerechnete Beträge werden fortlaufend verglichen. Gemeinsame Dashboards zeigen Kennzahlen wie die Autorisierungs-Erfolgsrate pro Acquirer, Antwortzeiten und offene Abweichungen, und Alarme gehen direkt an das zuständige Team. Dazu kommen automatisierte Tests mit realistischen Testtransaktionen (inkl. Sonderfällen wie Rückerstattungen, Teilzahlungen, Timeouts), bevor eine Änderung live geht.

#### Begründung
Automatisierung ist teilweise vorhanden, bringt aber wenig, solange Änderungen trotzdem wochenlang auf das nächste Wartungsfenster warten. **Lean** entfernt diese Wartezeit, und der **Second Way** sorgt dafür, dass Fehler in Minuten statt Tagen auffallen. Gerade im Zahlungsverkehr ist das entscheidend, weil Fehler direkt Geld und das Vertrauen von Händlern und Banken kosten. Beides hängt zusammen: Kleine, häufige Änderungen mit schnellem Feedback sind sicherer als ein grosses Release pro Monat. Wie bei TechNova würde das auch die Kultur verbessern, weil Fehler früher und klarer zuzuordnen sind und es weniger Schuldzuweisungen gibt.