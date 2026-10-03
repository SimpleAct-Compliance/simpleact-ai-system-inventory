# KI-Inventar

**Was nicht im Register steht, wird nicht eingestuft, nicht dokumentiert und nicht überwacht.** Das Inventar ist der erste Schritt und der, der am längsten dauert — nicht wegen der Felder, sondern wegen der Suche.

*The AI register: what belongs in it, how to find the systems nobody registered, and why completeness has to be evidenced rather than claimed.*

---

## Das eigentliche Problem

Der kleinere Teil der KI in einem Unternehmen wurde als KI-Projekt beschafft. Der größere steckt in eingekaufter Software, hängt an einer Schnittstelle oder ist eine Funktion, die ein Anbieter im letzten Release ergänzt hat.

Wer eine Rundmail schreibt — „welche KI-Tools nutzt ihr?" — bekommt die bekannten Fälle zurück. Das ist kein Inventar, sondern eine Liste dessen, woran sich Leute erinnern.

## Fünf Quellen, und was nur die jeweilige findet

| Quelle | Findet | Findet nicht |
|---|---|---|
| **Beschaffung und Kreditorenliste** | eingekaufte Werkzeuge mit Vertrag | kostenlose Dienste, Einzelabos |
| **Auslagenerstattung** | Einzelabos, die an der Beschaffung vorbeigehen | Dienste ohne Rechnung |
| **Anmeldedienst (SSO)** | was über die zentrale Anmeldung läuft | Dienste mit eigener Anmeldung |
| **Netzprotokolle, aggregiert** | Dienste ohne Vertrag und ohne Anmeldung | Nutzung auf privaten Geräten |
| **Release-Notes bestehender Software** | nachträglich ergänzte KI-Funktionen | nichts, aber nur wenn jemand liest |

Die rechte Spalte ist der Grund, warum eine Quelle nicht genügt. Und die letzte Zeile ist der häufigste Fall: Ein CRM bekommt eine Zusammenfassungsfunktion, ein Bewerbungstool eine Vorsortierung. Es gibt kein Projekt, keine Beschaffung, keinen Antrag — und ab diesem Release verarbeitet ein KI-System personenbezogene Daten.

**Was in einer Prüfung zählt, ist nicht die Behauptung der Vollständigkeit, sondern der Nachweis der Suche.** Festhalten: welche Quellen, wann, mit welchem Ergebnis. Siehe [Wie man findet, was niemand gemeldet hat](./knowledge-base/eu-ai-act/provider-and-model-registers.md).

## Ein Eintrag je Einsatzzweck

Nicht je Werkzeug. Ein Sprachmodell, das in drei Fachbereichen für drei Zwecke läuft, braucht drei Einträge: Die Einstufung, die Betroffenen und die Aufsicht unterscheiden sich.

Die Versuchung, es anders zu machen, ist groß — ein Eintrag ist weniger Arbeit. Der Preis fällt später an: Eine Einstufung über drei Zwecke muss sich an der riskantesten orientieren, und dann gelten für alle drei Pflichten, die nur für einen nötig wären.

## Die drei Felder, die am häufigsten fehlen

| Feld | Warum es fehlt | Was ohne es nicht geht |
|---|---|---|
| **Modell und Version** | niemand fragt den Anbieter | ein stiller Modellwechsel ist nicht feststellbar |
| **Wer prüft die Ausgabe, in welcher Zeit** | „Aufsicht: ja" fühlt sich wie eine Antwort an | Art. 14 ist nicht belegbar |
| **Berührt die Ausgabe einen Anhang-III-Bereich** | klingt nach Jura, nicht nach Inventar | der Rollenwechsel nach Art. 25 bleibt unbemerkt |

Alle drei stehen in der [Feldliste](./knowledge-base/eu-ai-act/inventory-fields.md) mit Begründung.

## Inhalt

| Dokument | Inhalt |
|---|---|
| [Warum das Inventar zuerst kommt](./knowledge-base/eu-ai-act/overview.md) | Reihenfolge, Fristen, was die Verschiebung nicht verschiebt |
| [Was ein System ist](./knowledge-base/eu-ai-act/definitions.md) | wann etwas einen Eintrag braucht, und wann nicht |
| [Wessen System ist es](./knowledge-base/eu-ai-act/scope-and-actors.md) | Anbieter, Betreiber, und der unbemerkte Rollenwechsel |
| [Was die Einstufung vom Inventar braucht](./knowledge-base/eu-ai-act/risk-logic.md) | welche Felder die Einstufung speisen |
| [Die Felder](./knowledge-base/eu-ai-act/inventory-fields.md) | jedes Feld mit Begründung und typischem Fehler |
| [Anbieter und Modelle finden](./knowledge-base/eu-ai-act/provider-and-model-registers.md) | die Suche, eingebettete KI, aggregierte Netzprotokolle |
| [Register und Zuständigkeit](./knowledge-base/eu-ai-act/inventory-and-governance.md) | wer pflegt, wer prüft, woran man Verfall merkt |

### Vorlagen

| Vorlage | Zweck |
|---|---|
| [Inventareintrag](./templates/ai-system-inventory-template.md) | ein Eintrag je System und Einsatzzweck |
| [Felderklärung](./templates/inventory-field-dictionary.md) | was in jedes Feld gehört, zum Weitergeben |
| [Beispielregister](./templates/example-ai-system-register.md) | sechs ausgefüllte Einträge, auch unangenehme |
| [Zuständigkeitsmodell](./templates/ownership-model.md) | drei Rollen je Eintrag, mit Abgrenzung |
| [Prüfablauf](./templates/review-workflow.md) | wie ein Eintrag aktuell bleibt |

Maschinenlesbar: [framework/simpleact-framework.json](./framework/simpleact-framework.json) · [llms.txt](./llms.txt)

## Davor und danach

- gleichzeitig: [Anbieterregister](https://github.com/SimpleAct-Compliance/simpleact-model-vendor-register) — wer liefert das Modell, mit welchen Zusagen
- danach: [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu) — welche Klasse je Einsatzzweck
- übergreifend: [Governance-Rahmenwerk](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework)
- Anbindung: [Integrationen](https://github.com/SimpleAct-Compliance/simpleact-integrations-apis) — damit Register sich füllen statt gepflegt zu werden

## In Software umsetzen

[SimpleAct](https://simpleact.de) führt das KI-Register verknüpft mit Einstufung, Verarbeitungsverzeichnis und Anbieterverwaltung: **[KI-Register](https://simpleact.de/ki-register)**

## Stand und Lizenz

Zuletzt aktualisiert: 2026-10-03 · MIT — frei nutzbar, auch kommerziell. Keine Rechtsberatung.
