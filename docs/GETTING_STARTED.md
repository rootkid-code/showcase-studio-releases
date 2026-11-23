# Erste Schritte mit Showcase Studio

**Stand 23.11.2026:** Das [öffentliche Prerelease v1.0.0-beta.3](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.3) enthält ein Windows-ZIP. Es ist eine Community-Testversion, keine nachgewiesene Stable-Abnahme.

## 1 · Vorbereiten

- Die Beta.3-Release-Notes nennen **Windows 10 oder 11 (64 Bit)** und **Python 3.11 oder neuer**.
- Für den Einstieg reicht ein **synthetischer, lokal erstellter n8n-Beispielworkflow** als JSON. Eine Live-Verbindung ist nicht erforderlich, um das Konzept zu verstehen.
- Bei Live-Zugriff benötigst du eine erreichbare n8n-Instanz und einen API-Key mit minimalen erforderlichen Leseberechtigungen. Welche Scopes deine n8n-Version unterstützt, muss in deiner Instanz geprüft werden.
- Keine produktiven Passwörter, Tokens oder echten Kundendaten für die ersten Tests verwenden.

## 2 · Beta.3 herunterladen und SHA-256 prüfen

1. [Release v1.0.0-beta.3 öffnen](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.3).
2. Unter **Assets** die Datei **ShowcaseStudio-1.0.0-beta.3.zip** laden, nicht die GitHub-Source-ZIP.
3. In Windows PowerShell ausführen:

       Get-FileHash ".\ShowcaseStudio-1.0.0-beta.3.zip" -Algorithm SHA256

4. Erwarteter Wert laut GitHub-Release-Metadaten:

       01460c3d52ac03e30be254e6ea588bc45421c9c65bb2e345006d25b882838afb

**Bei Abweichung das Paket nicht ausführen.** Die zusätzlich veröffentlichten Dateien **release.json** und **release.json.sig** wurden hier nicht unabhängig kryptografisch verifiziert. [Faktenblatt](releases/v1.0.0-beta.3.md).

## 3 · Installation der Beta

Das ZIP **vollständig in einen eigenen Ordner entpacken**. Laut Beta.3-Release Notes **01-INSTALLIEREN.vbs** im entpackten Ordner doppelklicken und dem Assistenten folgen. Sicherheitswarnungen nicht pauschal umgehen. Bei Abweichungen die **im tatsächlich heruntergeladenen Release-Paket** enthaltene Anleitung beachten.

Vor einem Upgrade: persönliche Studio-Bibliothek sichern; keine vorhandenen Datenordner vorschnell löschen. Ein Installer muss fremde Verzeichnisse und unabhängige n8n-/Python-Installationen unberührt lassen.

## 4 · Ersten Workflow ansehen

1. Studio öffnen und Einführungsbildschirm beziehungsweise Workspace wählen.
2. Demo-Workflow importieren oder – falls verfügbar – über den Verbindungsassistenten eine n8n-Instanz mit minimalen Leserechten anbinden.
3. Im Canvas Gesamtablauf, einzelne Knoten und ggf. Sticky Notes ansehen.
4. Eine eigene Präsentationsansicht erstellen; Originaldaten und freigegebene Informationen unterscheiden.
5. Vor jedem Export die Datenschutz- und Freigabekontrolle durchgehen.

Mehr dazu im [Nutzerhandbuch](USAGE_GUIDE.md) und unter [Datenschutz/Export](PRIVACY_AND_EXPORT.md).

## Probleme?

Siehe [Fehlerbehebung](TROUBLESHOOTING.md) und [Support](../SUPPORT.md). Bitte keine Zugangsdaten oder vollständigen Workflow-Dateien in Issues teilen.
