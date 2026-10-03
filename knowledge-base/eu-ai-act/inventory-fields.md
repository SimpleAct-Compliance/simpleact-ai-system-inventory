# Die Felder

Jedes Feld hier hat einen Grund. Felder ohne Grund werden nicht gepflegt, und ein Register mit vierzig Feldern, von denen zwölf gefüllt sind, ist schlechter als eines mit achtzehn, die stimmen.

Zu jedem Feld: wofür es gebraucht wird, und der typische Fehler.

---

## Identität

| Feld | Wofür | Typischer Fehler |
|---|---|---|
| Kennung | Verweise aus anderen Registern | fehlt, dann wird über Namen verwiesen, und der ändert sich |
| **Einsatzzweck** | Einheit der Einstufung | der Produktname steht drin statt der Tätigkeit |
| Werkzeug / Produkt | Zuordnung zum Vertrag | |
| Fachbereich | Zuständigkeit | „unternehmensweit" — dann ist niemand zuständig |
| Status | ob es läuft | „Pilot" als Schutzraum verwendet |
| In Betrieb seit | Zeitbezug in Prüfungen | |

**Zum Einsatzzweck:** Die Probe ist ein Satz mit einem Verb. „Sprachmodell" ist keiner. „Fasst eingehende Supportanfragen zusammen und schlägt eine Kategorie vor" ist einer — und daran ist erkennbar, dass die Ausgabe eine Vorsortierung beeinflusst.

## Anbieter und Modell

| Feld | Wofür | Typischer Fehler |
|---|---|---|
| Anbieter | Vertrag, AVV, Rolle | |
| Sitz des Anbieters | Drittlandfragen | |
| **Modell und Version** | Erkennen des stillen Modellwechsels | leer, weil niemand gefragt hat |
| zugrunde liegendes GPAI-Modell | Dokumentationskette | |
| Verarbeitungsort | Art. 44 ff. DSGVO | „Cloud" |
| Unterauftragsverarbeiter | Art. 28 Abs. 2 DSGVO | |
| Vertragsgrundlage (AVV, SCC) | Nachweis | |
| Tarif | Zusagen unterscheiden sich pro Tarif | |

**Zu Modell und Version:** Das wichtigste und am häufigsten leere Feld. Ohne es lässt sich nicht feststellen, dass der Anbieter das Modell getauscht hat — und damit beruht die Einstufung auf etwas, das es nicht mehr gibt. Wenn der Anbieter die Version nicht herausgibt, gehört **das** ins Feld, mit Datum der Anfrage.

**Zum Tarif:** Trainingsnutzung, Verarbeitungsort und Unterauftragsverarbeiter unterscheiden sich häufig je Tarif desselben Anbieters. Ein Eintrag ohne Tarif ist in diesen drei Punkten nicht belastbar. Tarifgenaue Angaben: [actcomp.de](https://actcomp.de)

## Daten

| Feld | Wofür | Typischer Fehler |
|---|---|---|
| Datenarten | Verarbeitungsverzeichnis | zu grob: „Kundendaten" |
| personenbezogen? | ob die DSGVO läuft | |
| besondere Kategorien (Art. 9 DSGVO)? | kann Art. 5 oder Anhang III auslösen | übersehen bei Freitexteingaben |
| biometrische Daten? | Art. 5 und Anhang III | |
| Eingaben zum Training genutzt? | Rechtsgrundlage, Vertraulichkeit | „nein" ohne Fundstelle |
| Aufbewahrung beim Anbieter | Löschkonzept | |
| Verweis ins Verarbeitungsverzeichnis | Doppelpflege vermeiden | |

**Zu besonderen Kategorien:** Der unterschätzte Fall sind Freitextfelder. Ein Supportformular, in das Kunden schreiben, was sie haben, enthält Gesundheitsdaten — unabhängig davon, ob das vorgesehen war.

**Zur Trainingsfrage:** „Unbekannt" ist eine ehrliche und häufige Antwort. Sie gehört mit der Stelle belegt, an der der Anbieter sich nicht äußert. Ein „nein" ohne Fundstelle ist in einer Prüfung wertlos.

## Betroffene und Wirkung

| Feld | Wofür | Typischer Fehler |
|---|---|---|
| Betroffenenkreis | Einstufung, DSFA | nur „Kunden" |
| Was die Ausgabe auslöst | Einstufung | „Information" — aber sie wird übernommen |
| berührt Beschäftigung, Bildung, Kreditwürdigkeit, Strafverfolgung, Migration, Justiz, wesentliche Dienstleistungen oder kritische Infrastruktur? | **Anhang III und Art. 25** | fehlt ganz |

**Zur letzten Zeile:** Das ist die Frage, die den Rollenwechsel nach Art. 25 sichtbar macht. Sie gehört ins Aufnahmeformular, nicht ins Jahresaudit, weil der Fachbereich sie beantworten kann und der Jurist sie nicht stellen kann, wenn er nichts von dem System weiß.

**Zur Wirkungsfrage:** Nützlich ist nicht, was das System tut, sondern was danach passiert. „Schlägt eine Kategorie vor" und „setzt die Kategorie" sind zwei verschiedene Risiken. Und wenn der Vorschlag in 98 % der Fälle übernommen wird, ist der Unterschied praktisch keiner.

## Rolle und Einstufung

| Feld | Wofür | Typischer Fehler |
|---|---|---|
| eigene Rolle | Pflichtenkatalog | ungeprüft „Betreiber" |
| Art. 25 geprüft? | Rollenwechsel | |
| rechtliche Klasse | Pflichten | |
| Rechtsgrundlage der Klasse | Nachprüfbarkeit | „minimal" ohne Artikel |
| **interne Risikoeinschätzung** | Priorisierung | mit der Klasse vermengt |
| Verweis auf den Einstufungsbogen | | |

Die beiden Risikofelder bleiben getrennt. Ein System kann rechtlich minimal und betrieblich riskant sein.

## Aufsicht und Kompetenz

| Feld | Wofür | Typischer Fehler |
|---|---|---|
| wer prüft die Ausgabe (Name) | Art. 14 | „der Fachbereich" |
| mit welcher Befugnis | Art. 14 | |
| in welcher Zeit | Art. 14 | |
| **geänderte Ausgaben im letzten Monat** | zeigt, ob Aufsicht stattfindet | nicht erhoben |
| Schulungsstand (Art. 4) | | allgemeine KI-Schulung statt systembezogen |

Die vierte Zeile ist die unbequemste und die aussagekräftigste Zahl im ganzen Register. Fällt sie gegen Null, ist die Aufsicht formal geworden, ohne dass jemand das entschieden hätte.

## Zuständigkeit

| Feld | Wofür |
|---|---|
| Eigentümer (Name) | hält den Eintrag aktuell |
| Prüfer (Name) | sieht nach, ob er stimmt |
| Freigebender (Name) | entscheidet über Inbetriebnahme |

Prüfer und Eigentümer dürfen nicht dieselbe Person sein. Siehe [Zuständigkeitsmodell](../../templates/ownership-model.md).

## Fortschreibung

| Feld | Wofür |
|---|---|
| Auslöser für eine Neubewertung | Rückkopplung |
| Testsatz eingerichtet, Turnus | stiller Modellwechsel |
| Änderungsverlauf geht an | |
| Wiedervorlage | |
| letzte Prüfung: Datum, Ergebnis, **bekannt geworden durch** | zeigt, ob ein Verfahren existiert |

## Herkunft des Eintrags

| Feld | Wofür |
|---|---|
| gefunden über | Nachweis der Suche |
| aufgenommen am, durch | |

Das Feld **gefunden über** erscheint überflüssig und ist es nicht: Die Summe dieser Angaben über alle Einträge ist der Nachweis, dass mehr als eine Quelle durchsucht wurde.

## Was „nicht bewertet" taugt

Ein ausdrücklich offener Punkt mit Person und Termin ist ein **gültiges Ergebnis** und besser als ein leeres Feld. Er zeigt, dass die Lücke bekannt ist. Ein leeres Feld zeigt dasselbe Nichtwissen ohne den Beleg, dass jemand es gemerkt hat.

## Weiter

[Felderklärung zum Weitergeben](../../templates/inventory-field-dictionary.md) · [Beispielregister](../../templates/example-ai-system-register.md)
