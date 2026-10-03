# Was die Einstufung vom Inventar braucht

Dieses Repository stuft nicht ein. Es liefert die Angaben, auf denen eine Einstufung aufbaut — und es ist nützlich zu wissen, welche das sind, weil sonst Felder gepflegt werden, die niemand braucht, während die gebrauchten leer bleiben.

Die Einstufung selbst: [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu)

## Welches Feld welchen Prüfschritt speist

| Prüfschritt | Braucht aus dem Inventar |
|---|---|
| 1 KI-System nach Art. 3 Nr. 1? | wie die Ausgabe entsteht, ob gelernt oder festgelegt |
| 2 Ausnahme? | Status (Pilot ist keine Ausnahme), Verwendungszusammenhang |
| 3 Verbotene Praktik nach Art. 5? | biometrische Daten, Emotionserkennung, Einsatzort Arbeitsplatz oder Bildung |
| 4 Hochrisiko Anhang I? | ob das System Teil eines Produkts mit Konformitätsbewertung ist |
| 4 Hochrisiko Anhang III? | **berührter Bereich**, Betroffenenkreis, was die Ausgabe auslöst |
| 4b Ausnahme Art. 6 Abs. 3? | Grad der menschlichen Aufsicht, ob profiliert wird |
| 5 Transparenz Art. 50? | direkter Kontakt mit Menschen, erzeugte Inhalte |

Daran ist ablesbar, welche Felder keine Fleißarbeit sind: **berührter Bereich**, **was die Ausgabe auslöst**, **Grad der Aufsicht**, **Datenarten**. Fehlt eines davon, kann die Einstufung nicht durchgeführt werden, sondern nur geschätzt.

## Drei Felder, die mehr entscheiden, als es aussieht

### Was die Ausgabe auslöst

Nicht, was das System tut — was danach passiert. Ein Vorschlag und eine Festlegung sind zwei Risiken. Wird der Vorschlag aber in 98 von 100 Fällen übernommen, ist der Unterschied praktisch keiner. Genau diese Zahl entscheidet darüber, ob die Ausnahme nach Art. 6 Abs. 3 trägt.

### Grad der menschlichen Aufsicht

Für die Ausnahme nach Art. 6 Abs. 3 ist entscheidend, ob das System eine menschliche Bewertung **ersetzt** oder nur vorbereitet. Dafür genügt ein Häkchen bei Aufsicht nicht. Gebraucht wird: wer, mit welcher Befugnis, in welcher Zeit — und wie oft tatsächlich widersprochen wurde.

### Wird profiliert

Die Rückausnahme: Wird Profiling natürlicher Personen vorgenommen, greift die Ausnahme nach Art. 6 Abs. 3 **nicht**, unabhängig von allen anderen Kriterien. Deshalb ein eigenes Feld und keine Unterfrage.

## Was das Inventar nicht entscheiden muss

Es muss nicht festlegen, ob ein System hochriskant ist. Es muss die Angaben liefern, mit denen das entscheidbar ist — und ein Feld haben, in dem **nicht bewertet** mit Person und Termin stehen darf.

Diese Trennung macht die Erstaufnahme überhaupt möglich. Ein Inventar, das erst vollständig ist, wenn alle Einstufungen vorliegen, wird nie vollständig. Achtzig Einträge, davon zwanzig eingestuft und sechzig als offen mit Verantwortlichem und Termin markiert, sind ein brauchbarer Zustand.

## Die zwei Risikofelder

| Feld | Beantwortet |
|---|---|
| rechtliche Klasse | welche Pflichten die Verordnung auslöst |
| interne Risikoeinschätzung | wie dringend es uns ist |

Getrennt halten. Ein Werkzeug, das Angebotstexte erzeugt, berührt keine Pflicht der Verordnung und kostet bei Halluzinationen Geld — rechtlich minimal, betrieblich mittel. In einer Spalte vermengt, entsteht Überregulierung oder eine Lücke.

## Die Pflicht ohne Klasse

**Art. 4 KI-Kompetenz**, anwendbar seit 2.2.2025. Sie hängt an keiner Risikoklasse, und das Inventar ist der einzige Ort, an dem sie zuweisbar wird: Nur dort steht, wer welches System bedient.

## Weiter

[Die Felder](./inventory-fields.md) · [Register und Zuständigkeit](./inventory-and-governance.md)
