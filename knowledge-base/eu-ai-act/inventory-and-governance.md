# Register und Zuständigkeit

Register veralten nicht, weil sie schlecht entworfen sind, sondern weil niemand namentlich dafür zuständig ist.

## Drei Rollen je Eintrag

| Rolle | Aufgabe | Darf nicht |
|---|---|---|
| **Eigentümer** | hält den Eintrag aktuell, kennt den Einsatzzweck | die eigene Arbeit freigeben |
| **Prüfer** | sieht nach, ob der Eintrag noch stimmt | mit dem Eigentümer identisch sein |
| **Freigebender** | entscheidet über Inbetriebnahme | nur unterschreiben, ohne nachzusehen |

Der Eigentümer sitzt im **Fachbereich**, nicht in der Compliance. Daran scheitern die meisten Register: Eine zentrale Stelle, die achtzig Einträge pflegt, kann bei keinem sagen, ob er noch stimmt. Der Fachbereich merkt, dass sich der Einsatzzweck verschoben hat — er braucht nur einen Weg, das zu melden.

Ausführlich: [Zuständigkeitsmodell](../../templates/ownership-model.md)

## Woran man Verfall merkt, bevor er auffällt

Drei Größen, alle erhebbar:

| Größe | Was ein schlechter Wert bedeutet |
|---|---|
| Anteil der Einträge mit **Eigentümer namentlich** | jeder fehlende Name ist eine Lücke mit Adresse |
| Wie Auslöser **bekannt geworden** sind | steht dort nur Zufall, fehlt ein Verfahren |
| Zahl der im letzten Monat **geänderten Ausgaben** | fällt sie gegen Null, ist die Aufsicht formal |

Die Zahl der Einträge sagt dagegen nichts. Ein Register kann wachsen und gleichzeitig verfallen.

## Die Verweise, die ein Eintrag tragen muss

Ein Register, das nur auf sich selbst verweist, erzeugt Doppelarbeit — und Doppelarbeit ist der häufigste Grund, aus dem Register veralten.

| Verweis | Wofür |
|---|---|
| **Verarbeitungsverzeichnis** (Art. 30 DSGVO) | sofern personenbezogene Daten verarbeitet werden |
| **DSFA** (Art. 35 DSGVO) | ob eine erforderlich ist, und wo sie liegt |
| **Grundrechte-Folgenabschätzung** (Art. 27 AI Act) | bei Hochrisiko in bestimmten Konstellationen |
| **Anbieterregister** | Modell, Version, Zusagen, AVV |
| **Einstufungsbogen** | Klasse mit Begründung |
| **Vorfallverfahren** | wohin eine Fehlfunktion gemeldet wird |
| **Schulungsstand** | Art. 4 |

Je mehr dieser Verweise automatisch entstehen, desto langsamer veraltet das Register. Dazu: [Integrationen](https://github.com/SimpleAct-Compliance/simpleact-integrations-apis)

## Der Aufnahmeweg entscheidet über die Vollständigkeit

Ein Formular mit acht Feldern wird ausgefüllt. Eines mit vierzig wird umgangen — und dann entsteht genau das, was das Inventar verhindern soll.

Praktischer Zuschnitt: Bei der Aufnahme nur, was der Fachbereich **ohne Nachfrage** weiß.

1. Was soll das System tun? (ein Satz mit Verb)
2. Welches Werkzeug, welcher Anbieter?
3. Welche Daten gehen hinein?
4. Wen betrifft die Ausgabe?
5. Was passiert mit der Ausgabe?
6. Berührt sie Beschäftigung, Bildung, Kreditwürdigkeit, Strafverfolgung, Migration, Justiz, wesentliche Dienstleistungen oder kritische Infrastruktur?
7. Wer prüft die Ausgabe?
8. Wer ist Eigentümer?

Alles Weitere — Modellversion, Unterauftragsverarbeiter, Rechtsgrundlage — wird danach ergänzt, von Leuten, die es beschaffen können. Wer das in die Aufnahme legt, bekommt keine Aufnahme.

## Warum ein Verbot nicht hilft

Schatten-KI entsteht selten aus Trotz. Jemand hatte eine Aufgabe, ein Werkzeug half, und es gab keinen erkennbaren Weg, das anzumelden. Ein Verbot verlagert die Nutzung auf private Geräte, wo sie unsichtbar wird — und wo das Unternehmen weder Vertrag noch Kontrolle hat.

Wirksamer: ein Aufnahmeweg mit weniger Aufwand als der Umweg, und eine Liste freigegebener Werkzeuge, die tatsächlich etwas taugt.

## Abgeschaltete Systeme bleiben

Ein Eintrag wird nicht gelöscht, wenn das System abgeschaltet wird — er bekommt den Status abgeschaltet mit Datum. In einer Prüfung wird gefragt, was zu einem bestimmten Zeitpunkt lief; ein gelöschter Eintrag macht diese Frage unbeantwortbar.

Dasselbe gilt für geänderte Einstufungen: Die neue ersetzt die alte nicht.

## Weiter

[Prüfablauf](../../templates/review-workflow.md) · [Zuständigkeitsmodell](../../templates/ownership-model.md) · [Governance-Playbook](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-playbook)
