# Erste Schritte mit Showcase Studio

> **Stand 23.11.2026:** Es gibt in diesem öffentlichen Repository **noch kein freigegebenes Download-Paket**. Die Anleitung beschreibt den vorgesehenen Weg nach einer tatsächlichen Veröffentlichung. Sie ist kein Nachweis, dass ein Installer bereits bereitsteht.

## 1 · Vorbereiten

- Ein Windows-PC ist derzeit die primäre Zielplattform; exakte unterstützte Builds stehen künftig in den jeweiligen Release Notes.
- Für den Einstieg reicht später ein **synthetischer, lokal erstellter n8n-Beispielworkflow** als JSON. Eine Live-Verbindung ist nicht erforderlich, um das Konzept zu verstehen.
- Bei Live-Zugriff benötigst du eine erreichbare n8n-Instanz und einen API-Key mit minimalen erforderlichen Leseberechtigungen. Welche Scopes deine n8n-Version unterstützt, muss in deiner Instanz geprüft werden.
- Keine produktiven Passwörter, Tokens oder echten Kundendaten für die ersten Tests verwenden.

## 2 · Offizielle Version finden

1. Öffne [GitHub Releases](https://github.com/rootkid-code/showcase-studio-releases/releases).
2. Prüfe, ob eine **konkrete Version mit Download-Artefakt** vorhanden ist.
3. Lies die Release Notes: Windows-Voraussetzungen, Dateinamen, bekannte Einschränkungen, Release-Kanal und Prüfsummen.
4. Vergleiche eine veröffentlichte SHA-256-Prüfsumme vor dem Start, wenn sie angeboten wird.
5. Lade **nicht** die automatisch angebotene Source-ZIP dieses Informationsrepositories als App herunter.

**Fehlt eine Release-Datei?** Dann gibt es noch keine öffentliche Installation. Auch ein interner Beta-Name in einer Dokumentation macht daraus kein veröffentlichtes Programm.

## 3 · Installation nach Veröffentlichung

Das interne Windows-Paket war als vollständig zu entpackendes Archiv mit einem grafischen Einstieg `00-START-HIER.html` und einer Installationsroutine `01-INSTALLIEREN.vbs` konzipiert. Diese Namen können sich ändern. Folge deshalb ausschließlich der Anleitung **im tatsächlich heruntergeladenen Release-Paket**.

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
