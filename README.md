# Präambel
1. HerrLoesch hat immer recht.
2. Jedwedes Geld, das mit diesem Dokument verdient wird, steht nur HerrLoesch zu und muss nicht geteilt werden.
3. Jeder kann sich beteiligen in dem er Pull Requests stellt.
4. Aufgrund von 1. darf HerrLoesch PRs ohne Nennung von Gründen ablehnen.
5. Sollte jemand anderes als HerrLoesch diese Präambel bearbeiten, kann er oder sie sich den PR gleich sparen...
6. Wer dieses Dokument ernst nimmt, ist selbst schuld da es sich um eine ironische Aufarbeitung gängiger Fehlpraktiken in unserer Industrie handelt. Es bezieht sich demnach nicht auf konkrete Arbeitsverhältnisse oder Auftraggeber der Contributer.

Vielen Dank an Tobias D. für die Idee, auch wenn er seinen Namen hier nicht in voller Gänze lesen möchte.

# Zertifizierung
## Reifegrade
* Fragile Practitioner
* Fragile Professional 
* Fragile Expert


# Fragiles Manifest
## Prinzipien
Folgende Prinzipien stellen die Grundlagen jeder fragilen Softwareentwicklung dar. Sie sind nach Wichtigkeit geordnet und es ist davon auszugehen, dass die Punkte auf der rechten Seite nahezu unwichtig und die Punkte auf der linken Seite in höchstem Maße bedeutend sind.

* Kurzfristiger Profit ist besser als funktionierende Software und jedwede Dokumentation.
* Eine konstant steigende Menge an Features ist besser als Wartbarkeit.
* Reagieren auf Veränderung ist besser als jede Form von Plänen.
* Selbstbestimmtes Handeln ist besser als die Kommunikation mit anderen Personen.
* Möglicherweise falsche Anforderungen umzusetzen ist besser als überhaupt keine Anforderungen zu haben.


## Regeln
Während Prinzipien eher ein Gefühl vermitteln sollen, sind Regeln in jedem Fall einzuhalten und Verletzungen mit voller Härte zu begegnen.

* Entwickler und Fachexperten dürfen nur in Ausnahmefällen zusammenarbeiten. Dabei sind die offiziellen Kommunikationswege einzuhalten, um keine falschen Hoffnungen zu wecken.
* In Diskussionen sind Sätze immer mit "Ja aber," einzuleiten insofern sie ein Argument des Feindes betreffen.
* Jedes Pattern darf maximal einmal verwendet werden, außer es wird 1:1 kopiert.
* Metainformationen die Rückschlüsse auf die Leistungsfähigkeit einzelner Teammitglieder zulassen, verstoßen gegen deren Persönlichkeitsrechte und dürfen somit nicht erfasst werden. Dazu gehören alle Kennzahlen wie "bearbeite Aufgaben" oder "abgeschlossene Tätigkeiten".
* Planungen erfolgen immer auf Basis verfügbarer Arbeitsstunden, da nur so der tatsächlich mögliche Leistungsumfang korrekt erfasst werden kann.
* Man muss den Untergebenen vertrauen. Aus diesem Grund werden Schätzungen als Ist-Werte behandelt. Ausgenommen sie erscheinen zu hoch, dann können die erfahreneren Vorgesetzten notwendige Aufwände entsprechend korrigieren.
* Mitbestimmungsrechte ergeben sich auf Basis der Länge der Firmenzugehörigkeit und Loyalität gegenüber den Vorgesetzten.

## Rollen
### Fragile Process Committee
Das Fragile Process Committee ist eine lose Sammlung weisungsbefugter Personen. Es passt den Entwicklungsprozess an die kurzfristigen Ziele einzelner Mitglieder ggf. aber auch des Unternehmens an. Das Committee tagt je nach Bedarf, kann Änderungen aber auch in Form eines E-Mailthreads bekanntgeben.

### SCUM Master
Der SCUM Master ist die Exekutive des Fragile Process Committees und sorgt mit harter Hand für die Einhaltung des aktuell gültigen Prozesses. Wechselnd stellt er durch Micromanagement und Abwesenheit die Möglichkeit des eigenverantwortlichen Handelns der Untergebenen sowie deren gleichbleibend hohe Leistungsfähigkeit sicher.

### Product Owner
Jeder der am Produkt beteiligt ist gilt als Product Owner und kann eigenständig zur Verbesserung der Software beitragen. Hierzu kann er entweder andere Product Owner direkt anweisen oder er nehmen die notwendigen Änderungen gleich an Ort und Stelle vor, falls er denn über die notwendigen Möglichkeiten verfügt.

### Early Adopter
Early Adopter sind die Grundpfeiler der Qualitätssicherung in der fragilen Softwareentwicklung, denn nur sie können einschätzen wie der Arbeitsprozess an die neuen Fähigkeiten der Software angepasst werden muss. Sollten Fehler auftreten, die ein Arbeiten mit der Applikation unmöglichen machen, so ist es die Pflicht des Early Adopters andere Product Owner auf jenen Umstand hinzuweisen. Dies geschieht möglichst zeitnah per Telefon und mit der notwendigen Schärfe in der Wortwahl, um ein zügiges Beheben der Problemstellen voran zu treiben. In wie fern ein Fehlverhalten der Software tatsächlich arbeitsbehindern ist, liegt dabei völlig im Ermessen des Early Adopters und bedarf keiner näheren Erläuterung insofern jener die damit verbundene Eskalation gewonnen hat.

Hinweis: Die Rolle des Early Adopters macht die fragile Softwareentwicklung so produktiv, da sie es ermöglicht das gesamte zeitliche Budget für die Umsetzung neuer Features zu nutzen.

## Events
### Eskalation
Sofern bei strittigen Punkten keine Einigung erzielt wurde, kommt es zu einer Eskalation.
* Eskalationen werden nicht geplant, sondern folgen dem aleatorischen Prinzip.
* Es müssen nicht alle Entscheider anwesend sein, was Optionen für nachträglichen Änderungen offenlässt.
* Die Eskalation gewinnt, wer den Entscheider in der höchsten Ebene von den eigenen Argumenten überzeugen kann.
* Die Weitergabe der wichtigsten Aspekte geschieht rein mündlich und auf informelle Art und Weise.

### Lessons Learned
Es wird nach jedem Projekt ein Lessons Learned durchgeführt.
* Verfehlungen sind namentlich zu adressieren damit die jeweilige Person und alle Beteiligten aus diesen Fehlern lernen können.
* Jeder, der in irgendeiner Form am Projekt beteiligt ist oder war, sollte anwesend sein, um sich einen Überblick über die Verfehlungen alle Projektbeteiligten machen zu können.
* Die Weitergabe der wichtigsten Aspekte geschieht rein mündlich und auf informelle Art und Weise.



## Artefakte
### Wiki
...

### E-Mail Thread
Unter voller Ausnutzung von Funktionen wie CC und BCC, sorgt der E-Mail Thread für einen einheitlichen Broadcast von Informationen an jeden den es interessieren könnte. Hierzu sind folgende Verhaltensregeln einzuhalten:
* Um einen Fork des Threads zu vermeiden muss immer in einheitlichen Zeitabstand und niemals parallel geantwortet werden.
* Antworten sind grundsätzlich an alle Personen im E-Mailverteiler zu richten.
* Beschreibungen sind möglichst farblich einheitlich und direkt unterhalb der Ursprungsaussage einzubringen.

## Praxistipps
* Produktivumgebung und Testumgebung sind nach Möglichkeit ein und dasselbe, um den Aufwand bei der Erstellung von Tests zu verringern. Wenn sie aus irgendeinem Grund doch getrennt sind, ist die Produktivumgebung aktueller zu halten als die Testumgebung um Anpassungen an den Tests zu vermeiden.
* Sollten Personen an mehreren Projekten beteiligt sein ergibt sich ihre mögliche Auslastung je Projekt aus "Verfügbare Stunden" / "Anzahl der Projekte" + "Motivationsbonus". Letzterer kann durch disziplinarische Maßnahmen nach einer erfolgten Verweigerung gesteigert werden.
