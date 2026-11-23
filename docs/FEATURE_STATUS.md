# Feature-Status & Produktgrenzen

**Stand: 23.11.2026.** Diese Übersicht trennt **Code beziehungsweise Konzeption in privaten Entwicklungszweigen** von einer **öffentlich verfügbaren Beta, deren vollständige Abnahme noch nicht belegt ist**. Sie ist kein Testprotokoll.

| Bereich | Aktueller Entwicklungsbezug | Öffentlich freigegeben? |
|:--|:--|:--|
| Lesender n8n-Import / JSON | Implementierungen im privaten Projekt | **Beta.3-Paket vorhanden; unabhängige Funktionsabnahme nicht belegt** |
| Workflow-Canvas / Node-Fokus / Sticky Notes | Privater Entwicklungsstand | **Beta.3-Paket vorhanden; unabhängige Funktionsabnahme nicht belegt** |
| Goldene Markenidentität | Originalassets synchronisiert | **Nur Marketingassets** |
| Workflow-Landkarte / Subflow-Navigation | Fortgeschrittener privater Zweig | **Beta.3-Paket vorhanden; unabhängige Funktionsabnahme nicht belegt** |
| Versionshistorie / Vergleich / optionaler Sync | Fortgeschrittener privater Zweig | **Beta.3-Paket vorhanden; unabhängige Funktionsabnahme nicht belegt** |
| HTML, SVG, PNG, Markdown, Mermaid, JSON | Exportmodule im privaten Code vorhanden | Beta.3-Release-Notes beschreiben die Funktion; E2E-Validierung ausstehend |
| PDF / Einbettung / Sammelausgabe | Implementierungen in fortgeschrittenen Zweigen | Beta.3-Release-Notes beschreiben die Funktion; E2E-Validierung ausstehend |
| Erweiterte Erklärungen / Privacy Review | Privater Entwicklungszweig | Beta.3-Release-Notes beschreiben die Funktion; E2E-Validierung ausstehend |
| Windows Installation / Start / Upgrade | Installer-Code vorhanden, native E2E-Gates ausstehend | Beta.3 als Windows-ZIP verfügbar; native E2E-Gates nicht nachgewiesen |
| macOS-Unterstützung | Experimentelle Entwicklungszweige | Kein Public-Release |
| Verkauf, Preise, Pro-Edition | Ideen/experimentelle private Komponenten | **HOLD – keine Produktankündigung** |

## Bedeutung der Zustände

- **Implementiert:** Dateien/Funktionsmodule existieren in einem Quellstand; damit ist noch nicht bewiesen, dass sie in einer geprüften Installation zuverlässig funktionieren.
- **Getestet:** Konkrete reproduzierbare Testnachweise sind dem tatsächlichen Build/Commit zugeordnet.
- **Öffentlich veröffentlicht:** Paket, Release Notes, Versionsnummer und Freigabe liegen auf der [GitHub-Releases-Seite](https://github.com/rootkid-code/showcase-studio-releases/releases).

**Öffentlich:** Das [Prerelease v1.0.0-beta.3](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.3) enthält ZIP, Manifest und Signaturdatei. **Nicht durch diese Dokumentation belegt:** unabhängiger ZIP-/Signaturscan, vollständige Windows-/Browser-E2E-Tests und die nachvollziehbare private Source-Commit-Bindung. [Faktenblatt](releases/v1.0.0-beta.3.md).

## Prioritäten nach Veröffentlichung der ersten Free-Beta

- Echte native Windows-11-Installation, Start, Upgrade, Deinstallation, Daten-/Rollback-Test.
- n8n-Berechtigungen und negative Backend-/Browser-Security-Szenarien prüfen.
- Exporte gegen die freigegebenen, bereinigten Darstellungen abgleichen.
- Reale Testdaten-Workflows, aussagekräftige Screenshots und transparent dokumentierte Einschränkungen.
- Release-Artefakt gegen sensible Dateien/Publisher-Komponenten scannen, Prüfsummen veröffentlichen und unabhängige Freigabe protokollieren.

[Produktprioritäten](PROJECT_DIRECTION.md) · [Release-Gates](RELEASE_POLICY.md) · [Anwenderhandbuch](USAGE_GUIDE.md)
