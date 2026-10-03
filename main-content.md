# KI-Inventar — Volltext

Dieses Dokument fasst das Repository in einem Stück zusammen. Die Einzeldokumente gehen jeweils tiefer.

## Warum das Inventar zuerst kommt

Die Reihenfolge ist Inventar, Einstufung, Pflichten, Nachweise, Überwachung. Jeder Schritt kann nur bearbeiten, was der vorige geliefert hat: Eine Einstufung bewertet, was bekannt ist; ein Nachweis belegt, was eingestuft wurde.

Ein Haus mit fünf von acht Systemen im Register hat deshalb keine zu 62 % erfüllte Compliance. Es hat drei Systeme, über die niemand etwas sagen kann.

Die Verschiebung von Anhang III durch den Digital Omnibus (Verordnung (EU) 2026/1744) auf den 2.12.2027 betrifft den **Pflichtenkatalog** für Hochrisikosysteme — nicht das Inventar. Das Inventar ist die Voraussetzung dafür, überhaupt zu wissen, ob man betroffen ist. Und **Art. 50 Transparenz gilt seit 2.8.2026**: Wer einen Chatbot betreibt, hat eine Kennzeichnungspflicht und kann sie nur erfüllen, wenn er weiß, welche Chatbots es gibt.

## Das eigentliche Problem

Der kleinere Teil der KI in einem Unternehmen wurde als KI-Projekt beschafft. Der größere steckt in eingekaufter Software, hängt an einer Schnittstelle oder ist eine Funktion, die ein Anbieter im letzten Release ergänzt hat.

Eine Rundmail bringt deshalb die bekannten Fälle und nicht das Inventar. Sie findet nicht die Werkzeuge, die niemand für KI hält; nicht die, von denen Leute annehmen, sie seien schon bekannt; nicht die, bei denen eine Antwort Ärger bedeuten könnte; und nicht die eingebetteten Funktionen, von denen die Nutzenden selbst nichts wissen.

## Die fünf Quellen

**Beschaffung und Kreditorenliste** findet eingekaufte Werkzeuge mit Vertrag, nicht die kostenlosen. **Auslagenerstattung** findet die Einzelabos, die an der Beschaffung vorbeigehen. Der **Anmeldedienst** findet, was über die zentrale Anmeldung läuft, und ist blind für Dienste mit eigener Anmeldung — was selbst ein Hinweis ist. **Aggregierte Netzprotokolle** finden Dienste ohne Vertrag und ohne Anmeldung. **Release-Notes bestehender Software** finden nachträglich ergänzte KI-Funktionen, aber nur, wenn jemand sie liest.

Zu den Netzprotokollen gehört eine Grenze: aggregiert auswerten, nicht personenbezogen. Gefragt ist, welche Dienste genutzt werden, nicht wer was nutzt. Die personenbezogene Auswertung wäre eine Verhaltenskontrolle mit eigenen Rechtsfragen, und sie zerstört die Mitarbeit, auf die das Inventar angewiesen ist.

**Was in einer Prüfung zählt, ist nicht die Behauptung der Vollständigkeit, sondern der Nachweis der Suche.** Deshalb gehört zu jedem Register ein Suchprotokoll: welche Quelle, wann, durch wen, mit welchem Ergebnis. Eine Zeile mit „keine neuen Einträge" ist dort wertvoll.

## Ein Eintrag je Einsatzzweck

Nicht je Werkzeug. Ein Sprachmodell, das in drei Fachbereichen für drei Zwecke läuft, braucht drei Einträge: Einstufung, Betroffene und Aufsicht unterscheiden sich. Ein gemeinsamer Eintrag zwingt zur Einstufung nach dem riskantesten Zweck — dann gelten für alle drei Pflichten, die nur für einen nötig wären.

Die Probe für einen brauchbaren Einsatzzweck ist ein Satz mit einem Verb. „Sprachmodell" ist keiner. „Fasst eingehende Supportanfragen zusammen und schlägt eine Kategorie vor" ist einer — und daran ist erkennbar, dass die Ausgabe eine Vorsortierung beeinflusst.

## Die drei Felder, die am häufigsten fehlen

**Modell und Version.** Ohne diese Angabe lässt sich ein stiller Modellwechsel nicht feststellen, und die Einstufung beruht auf etwas, das es nicht mehr gibt. Gibt der Anbieter die Version nicht heraus, gehört das ins Feld, mit Datum der Anfrage.

**Wer prüft die Ausgabe, mit welcher Befugnis, in welcher Zeit.** Ein Häkchen bei Aufsicht belegt Art. 14 nicht. Dazu gehört die unbequemste Zahl des Registers: Wie viele Ausgaben wurden im letzten Monat tatsächlich geändert oder verworfen? Fällt sie gegen Null, ist die Aufsicht formal geworden, ohne dass jemand das entschieden hätte.

**Berührt die Ausgabe Beschäftigung, Bildung, Kreditwürdigkeit, Strafverfolgung, Migration, Justiz, wesentliche Dienstleistungen oder kritische Infrastruktur?** Diese Frage macht den Rollenwechsel nach Art. 25 sichtbar. Der Fachbereich kann sie beantworten; ein Jurist kann sie nicht stellen, wenn er von dem System nichts weiß. Deshalb gehört sie ins Aufnahmeformular und nicht ins Jahresaudit.

## Der Rollenwechsel

Ein Betreiber wird nach Art. 25 zum Anbieter, wenn er seinen Namen auf ein Hochrisikosystem setzt, es wesentlich ändert, seine Zweckbestimmung ändert — oder ein nicht als Hochrisiko bestimmtes System für einen Hochrisikozweck einsetzt.

Die ersten drei Fälle haben einen Anlass, an dem jemand innehalten könnte. Der vierte hat keinen: kein Vertrag, keine Codeänderung. Es genügt, ein allgemeines Werkzeug in einem Anhang-III-Bereich einzusetzen — ein Sprachmodell, das Bewerbungen vorsortiert; ein Textwerkzeug, das Kündigungsentwürfe schreibt.

## Zuständigkeit

Drei Rollen je Eintrag, mit Namen: Eigentümer, Prüfer, Freigebender. Der Eigentümer sitzt im **Fachbereich**, nicht in der Compliance — eine zentrale Stelle, die achtzig Einträge pflegt, kann bei keinem sagen, ob er noch stimmt. Eigentümer und Prüfer dürfen nicht dieselbe Person sein; alles andere lässt sich in kleinen Organisationen zusammenlegen.

Eine nützliche Auswertung, die selten gemacht wird: die Zuständigkeitstabelle nach Häufigkeit sortieren. Wer achtzehnmal als Eigentümer steht, ist überlastet, und das fällt sonst erst bei der Kündigung auf.

## Warum ein Verbot nicht hilft

Schatten-KI entsteht selten aus Trotz. Jemand hatte eine Aufgabe, ein Werkzeug half, und es gab keinen erkennbaren Weg, das anzumelden. Ein Verbot verlagert die Nutzung auf private Geräte, wo sie unsichtbar wird und das Unternehmen weder Vertrag noch Kontrolle hat. Wirksamer ist ein Aufnahmeweg mit weniger Aufwand als der Umweg — acht Felder, nicht vierzig.

## Was nicht gelöscht wird

Nichts. Abgeschaltete Systeme behalten ihren Eintrag mit Status und Datum; geänderte Einstufungen ersetzen die alten nicht. In einer Prüfung wird gefragt, was zu einem bestimmten Zeitpunkt lief.

## Weg durch das Repository

1. [Warum das Inventar zuerst kommt](./knowledge-base/eu-ai-act/overview.md)
2. [Was einen Eintrag braucht](./knowledge-base/eu-ai-act/definitions.md)
3. [Anbieter und Modelle finden](./knowledge-base/eu-ai-act/provider-and-model-registers.md) — die Suche
4. [Die Felder](./knowledge-base/eu-ai-act/inventory-fields.md)
5. [Zuständigkeitsmodell](./templates/ownership-model.md) entscheiden
6. [Beispielregister](./templates/example-ai-system-register.md) ansehen
7. [Felderklärung](./templates/inventory-field-dictionary.md) an die Fachbereiche geben
8. [Inventareintrag](./templates/ai-system-inventory-template.md) füllen
9. [Prüfablauf](./templates/review-workflow.md) einrichten — **vor** dem Ende der Erstaufnahme
10. [Prüfliste](./checklist.md) anwenden

---

Keine Rechtsberatung. Stand: Oktober 2026.
