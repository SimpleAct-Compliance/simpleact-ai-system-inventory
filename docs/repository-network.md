# Das Netz der Repositories

Dieses Repository deckt den **Inventarschritt** ab. Es setzt nichts voraus und liefert die Grundlage für alles Weitere.

## Der Weg

```
  [Inventar]  ->  Einstufung  ->  Pflichten  ->  Nachweise  ->  Betrieb
       |
       +-- gleichzeitig: Anbieterregister
```

| Richtung | Repository | Beantwortet |
|---|---|---|
| gleichzeitig | [Anbieterregister](https://github.com/SimpleAct-Compliance/simpleact-model-vendor-register) | Wer liefert das Modell, mit welchen Zusagen? |
| danach | [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu) | Welche Klasse je Einsatzzweck? |
| danach | [Prüfliste AI Act](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist) | Welche Pflichten folgen je Klasse? |
| danach | [Dokumentationsvorlage](https://github.com/SimpleAct-Compliance/simpleact-ai-act-documentation-template) | Was gehört in die technische Dokumentation? |
| danach | [Vorfallmanagement](https://github.com/SimpleAct-Compliance/simpleact-incident-management) | Art. 72 und 73: erkennen, bewerten, melden |

Das Anbieterregister steht neben dem Inventar, nicht danach: Beide entstehen aus derselben Suche. Wer die Kreditorenliste für das Inventar durchsieht, hat die Anbieterliste in der Hand.

## Übergreifend

| Repository | Wofür |
|---|---|
| [Governance-Rahmenwerk](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework) | wie alle Teile zusammenhängen |
| [Governance-Playbook](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-playbook) | wer entscheidet, wer prüft, wer eskaliert |
| [Audit-Vorbereitung](https://github.com/SimpleAct-Compliance/simpleact-ai-audit-readiness) | was eine Prüfung verlangt |
| [Integrationen](https://github.com/SimpleAct-Compliance/simpleact-integrations-apis) | Register, die sich aus vorhandenen Systemen füllen |
| [KI-Kompetenz](https://github.com/SimpleAct-Compliance/elearning) | Art. 4, anwendbar seit 2.2.2025 |
| [AI Act für SaaS](https://github.com/SimpleAct-Compliance/simpleact-ai-act-for-saas) | wann aus einem Betreiber ein Anbieter wird |

Das Repository zu den Integrationen ist für ein Inventar das wichtigste der Liste: Jeder Verweis, der automatisch entsteht, ist ein Verweis, der nicht veraltet.

## Datenschutzseite

| Repository | Für |
|---|---|
| [DSGVO-Grundlagen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-compliance-workspace) | Verarbeitungsverzeichnis, Rechtsgrundlage, Betroffenenrechte |
| [DSFA und FRIA](https://github.com/SimpleAct-Compliance/simpleact-dpia-dsfa-workflow) | Art. 35 DSGVO und Art. 27 AI Act |
| [Datenschutzverletzungen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-data-breach-management) | Art. 33 und 34 |

Verarbeitet ein System personenbezogene Daten, braucht es **zwei** Einträge: einen im KI-Inventar und einen im Verarbeitungsverzeichnis. Sie sollten sich gegenseitig verweisen statt doppelt geführt zu werden — Doppelpflege ist der häufigste Grund, aus dem Register veralten.

## Tarifgenaue Anbieterangaben

Was einzelne KI-Werkzeuge **tatsächlich** pro Tarif zusagen — Auftragsverarbeitung, Trainingsnutzung, Verarbeitungsort, Unterauftragsverarbeiter — führt SimpleAct als öffentliches Register mit Quelle und Prüfdatum je Angabe: **[actcomp.de](https://actcomp.de)**

Das ist für das Feld „Tarif" im Inventareintrag die praktische Abkürzung.
