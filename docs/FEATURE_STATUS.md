# Feature-Status & Produktgrenzen

**Stand: 23.11.2026.** Diese Übersicht trennt **Code beziehungsweise Konzeption in privaten Entwicklungszweigen** von einer **öffentlich installierbaren, überprüften Anwendung**. Sie ist kein Testprotokoll.

| Bereich | Aktueller Entwicklungsbezug | Öffentlich freigegeben? |
|:--|:--|:--|
| Lesender n8n-Import / JSON | Implementierungen im privaten Projekt | Nein |
| Workflow-Canvas / Node-Fokus / Sticky Notes | Privater Entwicklungsstand | Nein |
| Goldene Markenidentität | Originalassets synchronisiert | **Nur Marketingassets** |
| Workflow-Landkarte / Subflow-Navigation | Fortgeschrittener privater Zweig | Nein |
| Versionshistorie / Vergleich / optionaler Sync | Fortgeschrittener privater Zweig | Nein |
| HTML, SVG, PNG, Markdown, Mermaid, JSON | Exportmodule im privaten Code vorhanden | Keine öffentliche Paketabnahme |
| PDF / Einbettung / Sammelausgabe | Implementierungen in fortgeschrittenen Zweigen | Keine öffentliche Paketabnahme |
| Erweiterte Erklärungen / Privacy Review | Privater Entwicklungszweig | Keine öffentliche Paketabnahme |
| Windows Installation / Start / Upgrade | Installer-Code vorhanden, native E2E-Gates ausstehend | Kein Public-Build |
| macOS-Unterstützung | Experimentelle Entwicklungszweige | Kein Public-Release |
| Verkauf, Preise, Pro-Edition | Ideen/experimentelle private Komponenten | **HOLD – keine Produktankündigung** |

## Bedeutung der Zustände

- **Implementiert:** Dateien/Funktionsmodule existieren in einem Quellstand; damit ist noch nicht bewiesen, dass sie in einer geprüften Installation zuverlässig funktionieren.
- **Getestet:** Konkrete reproduzierbare Testnachweise sind dem tatsächlichen Build/Commit zugeordnet.
- **Öffentlich veröffentlicht:** Paket, Release Notes, Versionsnummer und Freigabe liegen auf der [GitHub-Releases-Seite](https://github.com/rootkid-code/showcase-studio-releases/releases).

**Derzeit ist nur die öffentliche Dokumentation verfügbar, keine installierbare Anwendung.**

## Prioritäten vor einer ersten Free-Beta

- Echte native Windows-11-Installation, Start, Upgrade, Deinstallation, Daten-/Rollback-Test.
- n8n-Berechtigungen und negative Backend-/Browser-Security-Szenarien prüfen.
- Exporte gegen die freigegebenen, bereinigten Darstellungen abgleichen.
- Reale Testdaten-Workflows, aussagekräftige Screenshots und transparent dokumentierte Einschränkungen.
- Release-Artefakt gegen sensible Dateien/Publisher-Komponenten scannen, Prüfsummen veröffentlichen und unabhängige Freigabe protokollieren.

[Produktprioritäten](PROJECT_DIRECTION.md) · [Release-Gates](RELEASE_POLICY.md) · [Anwenderhandbuch](USAGE_GUIDE.md)
