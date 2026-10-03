# Anbieter und Modelle finden

Dieses Kapitel ist die Suche selbst: wie man die Systeme findet, die niemand gemeldet hat, und wie man das belegt.

## Warum eine Umfrage nicht genügt

Eine Rundmail bringt die bekannten Fälle. Sie bringt nicht:

- Werkzeuge, von denen Leute annehmen, sie seien keine KI (Rechtschreibhilfe, Übersetzung, Zusammenfassung)
- Werkzeuge, von denen Leute annehmen, sie seien schon bekannt
- Werkzeuge, bei denen Leute vermuten, die Antwort könnte Ärger bedeuten
- eingebettete Funktionen, von denen die Nutzenden nichts wissen

Die ersten drei Punkte sind kein Verschulden, sondern erwartbares Verhalten. Die Suche muss ohne Mitwirkung funktionieren.

## Die fünf Quellen im Einzelnen

### 1 Beschaffung und Kreditorenliste

Alle Lieferanten der letzten 24 Monate durchsehen. Die Suche nach Begriffen wie „AI", „KI", „Intelligence", „Copilot", „Assistant", „GPT" findet einen Teil; der Rest sind Softwareanbieter, deren Produkt heute KI-Funktionen hat, auch wenn der Name nichts sagt.

**Belegen:** Stand der Liste, Zeitraum, wer durchgesehen hat.

### 2 Auslagenerstattung

Hier liegen die Einzelabos: zwanzig Euro im Monat, von einer Fachkraft selbst bezahlt und eingereicht. Beschaffungsprozesse sehen diese Ausgaben nicht.

**Belegen:** Zeitraum, Suchbegriffe, Treffer.

### 3 Anmeldedienst (SSO)

Die Liste der angebundenen Anwendungen. Sie ist vollständig für alles, was über die zentrale Anmeldung läuft, und blind für alles andere — was gleichzeitig ein Hinweis ist: Dienste mit eigener Anmeldung sind die, bei denen niemand die Vertragsbedingungen gelesen hat.

### 4 Netzprotokolle, aggregiert

Welche Dienste aus dem Unternehmensnetz erreicht werden. Das ist die einzige Quelle, die Dienste ohne Vertrag und ohne Anmeldung findet.

**Wichtig und nicht verhandelbar:** aggregiert auswerten, nicht personenbezogen. Gefragt ist „welche Dienste werden genutzt", nicht „wer nutzt was". Die personenbezogene Auswertung wäre eine Verhaltenskontrolle mit eigenen Rechtsfragen — Beteiligung des Betriebsrats, Rechtsgrundlage, Zweckbindung — und sie zerstört die Mitarbeit, auf die das Inventar angewiesen ist. Wer einmal so sucht, bekommt beim nächsten Mal keine Meldungen mehr.

**Belegen:** Zeitraum, Auswertungsebene, dass nicht personenbezogen ausgewertet wurde.

### 5 Release-Notes bestehender Software

Die mühsamste Quelle und die mit dem höchsten Ertrag. Für jede eingesetzte Standardsoftware: Was ist in den letzten zwölf Monaten an KI-Funktionen dazugekommen?

**Dauerhaft lösen:** Änderungsverlauf der wichtigsten Anbieter abonnieren, und zwar an eine Stelle, die ihn liest. Ein Änderungsverlauf, den niemand liest, ist keine Maßnahme.

## Eingebettete KI: die Fragen, die funktionieren

Beim Anbieter nachfragen ist zulässig und sinnvoll. Drei Fragen genügen:

1. Welche Funktionen des Produkts verwenden KI oder maschinelles Lernen?
2. Welches Modell liegt zugrunde, von wem, in welcher Version?
3. Werden unsere Eingaben zum Training verwendet — und wo steht das?

Die dritte Frage mit dem Nachsatz. Eine Zusage ohne Fundstelle ist in einer Prüfung keine Zusage.

Ausführlich: [Anbieterregister](https://github.com/SimpleAct-Compliance/simpleact-model-vendor-register)

## Der stille Modellwechsel

Ein Anbieter tauscht das zugrunde liegende Modell. Die Schnittstelle bleibt identisch, die Rechnung auch, das Verhalten nicht. Niemand erfährt davon.

Drei Wege, es zu bemerken:

| Weg | Braucht Mitwirkung des Anbieters |
|---|---|
| Versionsangabe in der Antwort | ja |
| Änderungsverlauf abonnieren | ja |
| **fester Testsatz** | **nein** |

Der Testsatz ist deshalb der tragende: zwanzig Eingaben mit erwarteten Ausgaben, monatlich durchlaufen, Abweichungen protokolliert. Billig, unspektakulär, und die einzige Vorkehrung, die auch bei einem schweigenden Anbieter funktioniert.

## Wie oft suchen

Die Erstaufnahme ist ein Projekt. Danach:

| Maßnahme | Turnus |
|---|---|
| Kreditorenliste und Auslagen durchsehen | halbjährlich |
| SSO-Anwendungsliste | vierteljährlich |
| Netzprotokolle, aggregiert | halbjährlich |
| Release-Notes der wichtigsten Anbieter | laufend, abonniert |
| Testsätze | monatlich |

## Was den Nachweis bildet

Nicht die Zahl der Einträge. Ein Suchprotokoll:

| Datum | Quelle | Zeitraum | Durch | Neue Einträge | Bemerkung |
|---|---|---|---|---|---|
| | | | | | |

Darin ist eine Zeile mit „keine neuen Einträge" wertvoll: Sie belegt, dass gesucht wurde. Ein Register ohne Suchprotokoll behauptet Vollständigkeit; eines mit Suchprotokoll belegt sie.

## Weiter

[Die Felder](./inventory-fields.md) · [Prüfablauf](../../templates/review-workflow.md)
