# Mitwirken

Dieses Repository beschreibt ein Verfahren, kein Produkt. Es lebt davon, dass Leute aus der Praxis widersprechen.

## Besonders willkommen

- **Fundorte, die hier fehlen** — eine Quelle, über die Sie Systeme gefunden haben, die keine der fünf gefunden hätte
- **Felder, die sich als überflüssig erwiesen haben** — und solche, die gefehlt haben, als es darauf ankam
- **Erfahrungen mit dem Aufnahmeweg** — ab welcher Feldzahl er umgangen wurde
- **Rückmeldungen aus Prüfungen** — wonach tatsächlich gefragt wurde
- **Korrekturen an Rechtsbezügen** — mit Fundstelle
- **Übersetzungen** einzelner Dokumente

Besonders interessant sind Fälle, in denen ein System erst im zweiten oder dritten Durchlauf aufgetaucht ist. Daran lernt man mehr als an den gefundenen.

## Weniger hilfreich

- Reine Umformulierungen ohne inhaltliche Änderung
- Weitere Felder ohne Begründung, wofür sie gebraucht werden. Ein Register mit vierzig Feldern, von denen zwölf gefüllt sind, ist schlechter als eines mit achtzehn, die stimmen
- Weitere Beispiele für klare Fälle — hilfreich sind die unklaren

## Was hier nicht wiederholt wird

Die Einstufung hat ein eigenes Repository, das Anbieterregister auch. Dieses verweist darauf, statt sie nachzuerzählen; das [Repository-Netz](./docs/repository-network.md) zeigt, wohin ein Beitrag gehört.

## Vorgehen

Kleine Korrekturen gern direkt als Pull Request. Bei größeren Änderungen vorher ein Issue.

`npm run validate` prüft, dass alle Pflichtpfade vorhanden und die JSON-Dateien lesbar sind. Die Prüfung läuft auch in CI.

## Rechtliches

Beiträge stehen unter der MIT-Lizenz dieses Repositories. Inhalte hier sind keine Rechtsberatung; wer eine Fundstelle ändert, gibt bitte die Quelle an.

Beispieldaten bitte erfinden. Die Einträge in [example-ai-system-register.md](./templates/example-ai-system-register.md) sind erfunden; echte Systeme, Anbietername plus Mangel, gehören nicht in ein öffentliches Repository.

## Kodierung

Alle Dateien sind UTF-8. Das klingt selbstverständlich, war es in diesem Repository aber eine Weile nicht — deutsche Umlaute erschienen auf GitHub als Ersatzzeichen. Wer unter Windows arbeitet, prüft das vor dem Commit.
