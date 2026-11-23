# Veröffentlichungsstandard – Showcase Studio

> Stand: 23. November 2026. **Prozessbeschreibung, keine Aussage über durchgeführte oder bestandene Prüfungen.** **Ein öffentliches Prerelease v1.0.0-beta.3 wurde veröffentlicht.** Die Veröffentlichung ist **kein Beleg**, dass sämtliche Gates bestanden wurden.

Dieses öffentliche Repository enthält Produktinformationen und **Release-Dateien für die aktuelle Beta.3**. Der private Quellcode und der Lizenz-Publisher bleiben getrennt.

## Freigabe-Gates

Ein Release darf erst als freigegeben bezeichnet werden, wenn die jeweils relevanten Nachweise vorliegen:

1. **Scope & Versionsstand:** Reproduzierbare Version, nachvollziehbarer Commit/Build, vollständige Release Notes und bekannte Einschränkungen.
2. **Windows-E2E:** Echte native Windows-11-Tests für Installation, Start, Neustart, Upgrade, Abbruch, Deinstallation und erwartbares Daten-/Rollback-Verhalten.
3. **Funktionen & Bedienung:** Reale GUI-/Browser-Nachweise, Lesbarkeit der n8n-Darstellung, Import, Exportfreigabe, Dark/Light, grundlegende Tastaturbedienung.
4. **Security Review:** Negative Tests für Host/Origin/Session und Rechte, Prüfung der Paketdateien und Exportdaten auf Secrets, PII, echte Workflows sowie verbotene Publisher-/Signaturdateien.
5. **Artefaktintegrität:** Verifizierter Archivinhalt, nachvollziehbare SHA-256-Prüfsummen, eindeutige Dateien und Installationshinweise. Eine Signatur darf nur behauptet werden, wenn sie tatsächlich vorhanden und prüfbar ist.
6. **Unabhängige Abnahme:** Offene Risiken dokumentieren und explizite Freigabe für die Veröffentlichung erfassen.

## Release-Typen

| Typ | Bedeutung |
| :--- | :--- |
| Development / Private RC | Interne Entwicklungsstände; **kein** öffentlicher Download |
| Public Preview / Pre-release | Nur bei vorhandener Datei, Release Notes und klar gekennzeichneten Einschränkungen |
| Stable | Erst nach vollständiger, dokumentierter Freigabe der definierten Gates |

## Nicht veröffentlichen

- `publisher-private/` oder interne Lizenzwerkzeuge
- Private Ed25519-Signaturschlüssel, Zertifikate mit geheimen Schlüsseln, Tokens oder `.env`-Dateien
- Echte n8n-Workflows/Kundendaten, unbereinigte Logs, persönliche Dateien
- Ungeprüfte Build-Caches und fremde Installationsdaten

## Nachweisstand für das vorhandene Beta-Release

[**v1.0.0-beta.3**](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.3) ist als **Prerelease** mit ZIP, Manifest und Signaturdatei vorhanden. **Nicht unabhängig belegt:** realer Windows-E2E-Test, kryptografische Signaturprüfung, ZIP-Privacy-Scan und nachvollziehbarer privater Source-SHA des Pakets. Deshalb **kein Stable-GO**. [Metadaten und offene Prüfpunkte](releases/v1.0.0-beta.3.md).

## Quelle der Wahrheit

Die [GitHub-Releases-Seite](https://github.com/rootkid-code/showcase-studio-releases/releases) ist der einzige offizielle öffentliche Kanal für Versionen und Artefakte dieses Repositories. Dokumentation, Screenshots und interne RC-Bezeichnungen ersetzen keine Download-Datei oder Freigabe.

[Zurück zur README](../README.md)
