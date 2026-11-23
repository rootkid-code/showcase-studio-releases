# Erste Schritte · Showcase Studio

**Stand: 23. November 2026 · [Öffentliche Beta 4](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4)**

> Showcase Studio ist aktuell eine **öffentliche Vorabversion**, kein Stable-Release. Die folgenden Schritte folgen der offiziellen Beta-4-Release-Beschreibung. Diese Dokumentation hat den Installer nicht selbst auf Windows ausgeführt. Für den Einstieg ausschließlich **Testworkflows** verwenden.

## 1 · Was du benötigst

Die [Beta-4-Release-Notes](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4) nennen:

- **Windows 10 oder 11, 64 Bit**
- **Python 3.11 oder neuer**; laut Release Notes prüft das Setup die Voraussetzung
- Für ersten lokalen Test: ein **synthetischer n8n-Workflow als JSON-Datei**
- Optional: n8n lokal, in Docker, in der Cloud oder auf eigenem HTTPS-Server mit **möglichst minimalen Leserechten**

Keine echten Tokens, Passwörter oder vertraulichen Kunden-Workflows für erste Experimente nutzen.

## 2 · Richtiges Paket herunterladen

1. Die [Release-Seite `v1.0.0-beta.4`](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4) öffnen.
2. Im Bereich **Assets** ausdrücklich die Datei **`ShowcaseStudio-1.0.0-beta.4.zip`** wählen.
3. **Nicht** die automatisch erzeugte `Source code (zip)`-Datei herunterladen – diese enthält keine vollständige Studio-App.
4. Optional die heruntergeladene ZIP in PowerShell prüfen:

   ```powershell
   Get-FileHash .\ShowcaseStudio-1.0.0-beta.4.zip -Algorithm SHA256
   ```

   Erwarteter SHA-256 aus dem Release:
   `b67cf8906d95a0ee7da97a2363e620aee23620510513fe7294992ffc055e4bb2`

## 3 · Installieren

1. Die heruntergeladene ZIP vollständig in einen eigenen Ordner **entpacken**.
2. **`01-INSTALLIEREN.vbs`** aus dem entpackten Paket öffnen.
3. Den Hinweisen des grafischen Assistenten für Installations- und Datenordner folgen.
4. Studio über die angelegte Verknüpfung starten.

Falls Windows eine Sicherheitswarnung anzeigt, **nicht** pauschal Schutzfunktionen abschalten. Dateiquelle, Checksumme und Veröffentlichungsinformationen prüfen; bei Unsicherheit zuerst [Support](../SUPPORT.md) kontaktieren.

**Bereits installiert?** Die Release Notes beschreiben ein Update über **Einstellungen → Auf Updates prüfen** oder den erneut gestarteten Installer. Vor jedem Upgrade die eigene Bibliothek sichern. Behauptungen zu Datenübernahme und Rollback müssen an der eigenen Testumgebung geprüft werden.

## 4 · Ohne n8n-Verbindung ausprobieren

1. Eine **fiktive** n8n-JSON-Datei mit wenigen Nodes verwenden.
2. Studio starten und die **Dateiimport-Option** wählen.
3. Im Canvas Knoten und Verbindungen betrachten; Notizen/Abschnitte öffnen.
4. Zwischen den sieben verfügbaren **Präsentationslooks** wählen: n8n, Make, Zapier, Blueprint, Neon Aurora, Skizzenbuch, Linienplan.
5. Einen Präsentationsstand prüfen und nur **synthetische, ausdrücklich freigegebene Inhalte** exportieren.

Die Styles Make/Zapier bedeuten **nicht**, dass das Studio bereits Make-Blueprints oder Zapier-JSONs importieren kann.

## 5 · Optionale n8n-Verbindung

Bei bestehender n8n-Instanz die korrekte Basisadresse und nur notwendige API-Rechte verwenden. Rechte müssen **bei n8n** begrenzt werden, nicht durch eine Anzeige in Showcase Studio. Bei Problemen nicht einfach pauschal zusätzliche Schreib-/Ausführungsrechte geben. Siehe [Fehlerbehebung](TROUBLESHOOTING.md).

## 6 · Vor dem Teilen

Ein Export kann URLs, Notizen, Node-Namen oder vertrauliche Prozessstruktur enthalten. **Prüfen → bereinigen → manuell freigeben → die tatsächliche exportierte Datei ansehen.** Der Privacy-Scanner hilft, ersetzt aber keine fachliche Freigabe.

[Datenschutz & Export](PRIVACY_AND_EXPORT.md) · [Anwenderhandbuch](USAGE_GUIDE.md) · [Feature-Status](FEATURE_STATUS.md)

## Feedback

Fehler mit **Version, Windows-Build, Reproduktionsschritten und synthetischem Beispiel** melden. Nie Zugangsdaten, Workflow-Rohdaten oder komplette Logs in öffentliche Issues einfügen.

[Support](../SUPPORT.md) · [Releases](https://github.com/rootkid-code/showcase-studio-releases/releases) · [Zurück zur README](../README.md)
