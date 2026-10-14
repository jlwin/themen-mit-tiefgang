# Themen mit Tiefgang

Ein deutschsprachiger Skill für fundierte Analysen und klare Kommunikation. Er ordnet aktuelle Nachrichten ein, entwickelt begründete Positionen und untersucht Geschäftsmodelle von Unternehmen, Produkten und Dienstleistungen. Er verbindet Marktumfeld, finanzielle Kennzahlen, strategische Abhängigkeiten und historischen Kontext mit eigenständigen Thesen, verständlichen Vergleichen und präziser Sprache.

Die Tiefe richtet sich nach dem Auftrag: von einer kurzen Antwort im Chat bis zu einem Social-Media-Beitrag, Podcast-Skript, Blogartikel oder einer Keynote. Fakten, Berechnungen, Interpretationen und Szenarien werden unterschieden. Quellen und fehlende Daten bleiben nachvollziehbar. Eine persönliche Haltung wird nur aus tatsächlichen Angaben entwickelt oder als Vorschlag kenntlich gemacht.

## Nutzung in Claude

Für den direkten Skill-Upload in Claude wird nur der Ordner `skills/themen-mit-tiefgang/` als ZIP mit dem übergeordneten Ordner `themen-mit-tiefgang/` gepackt. In Claude: Customize → Skills → + → Create skill → Upload a skill. Anschließend den Skill aktivieren. Das gesamte Repository-ZIP ist für diesen Upload nicht geeignet.

## Claude Code

Installation aus dem öffentlichen GitHub-Repository:

```text
/plugin marketplace add jlwin/themen-mit-tiefgang
/plugin install themen-mit-tiefgang@themen-mit-tiefgang-marketplace
```

Zum lokalen Laden ohne Installation:

```sh
claude --plugin-dir .
```

## Beispielanfragen

- Ordne diese Nachricht ein: Was ist neu, wer profitiert und welche Abhängigkeiten entstehen?
- Analysiere das Geschäftsmodell dieses Produkts: Wertstiftung, Erlöse, Kosten, Wettbewerb und strategische Risiken.
- Bereite diese Analyse als LinkedIn-Beitrag mit einer klaren These und nachvollziehbaren Belegen auf.

## Quellenzugang und Daten

Dieses Plugin enthält ausschließlich Anweisungen und Referenzmaterial. Es benötigt keine zusätzlichen Softwarepakete und stellt keinen MCP-Server bereit. Recherche nutzt nur die Werkzeuge und Quellen, die im jeweiligen Claude-Kontext verfügbar sind. Aktuelle Analysen benötigen aktuellen Quellenzugang oder vom Nutzer bereitgestellte Belege. Das Plugin betreibt keinen eigenen Datenspeicher und keinen externen Dienst. Die Verarbeitung des Chats und aufgerufener Werkzeuge richtet sich nach den Einstellungen und Bedingungen des jeweiligen Hosts und der verwendeten Dienste.

## Lizenz

Die bereitgestellten Skill-Dateien und die Dokumentation stehen unter [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Kommerzielle Nutzung, Weitergabe und Bearbeitung sind erlaubt. Erforderlich sind angemessene Namensnennung, ein Link zur Lizenz und die Kennzeichnung von Änderungen.

Namensnennung: **Themen mit Tiefgang — Jean-Luc Winkler — CC BY 4.0**. Quelle: https://github.com/jlwin/themen-mit-tiefgang. Bei Weitergabe die Quelladresse beibehalten. Verlinkte externe Quellen behalten ihre eigenen Rechte. Siehe [LICENSE](LICENSE).

Herausgeber: Jean-Luc Winkler.
