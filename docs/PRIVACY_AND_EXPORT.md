# Datenschutz & kontrollierte Workflow-Freigabe

> Diese Seite beschreibt sichere **Nutzungsprinzipien**. Sie ist weder ein Audit noch eine Zertifizierung des derzeit unveröffentlichten Produkts.

## Schutzbereiche

Ein n8n-Workflow kann API-Adressen, Webhook-Pfade, Personendaten, interne Prozesslogik, Prompt-Inhalte, IDs, URLs, technische Fehlertexte und Hinweise auf Zugangsdaten enthalten – auch in **Sticky Notes** oder Node-Beschriftungen.

Für Präsentationen werden deshalb zwei Ebenen unterschieden:

1. **Privater Arbeitsstand:** Workflow in der lokalen Bibliothek für die eigene Analyse.
2. **Freigegebener Präsentationsstand:** bewusst reduzierte, überprüfte Inhalte für Kunden oder Dritte.

## Vor jeder Weitergabe

- **Datenquelle prüfen:** nur synthetische oder für diesen Zweck ausdrücklich freigegebene Workflows.
- **Zugriff minimieren:** API-Schlüssel n8n-seitig auf die benötigten Leserechte beschränken; kein Schreib- oder Ausführungsrecht für die Präsentation.
- **Inhalte sichten:** Node-Namen, Notizen, Verbindungen, URLs, interne Referenzen, Debug-Texte und IDs prüfen.
- **Automatische Bereinigung nur als Unterstützung:** auch eine implementierte Maskierung kann Informationen übersehen; manuelle Endkontrolle bleibt erforderlich.
- **Export selbst öffnen:** HTML, PDF, SVG, PNG und JSON können verschiedene Informationen transportieren; tatsächlichen Inhalt kontrollieren.
- **Freigabe dokumentieren:** was geteilt wurde, mit wem, zu welchem Zweck und auf welchem Versionsstand.

Die private Entwicklung enthält einen erweiterten Prüfungsschritt mit Kategorien wie Credentials, Personendaten, internen Adressen, IDs, Links und Notizen. **Das ist kein Nachweis**, dass ein heute herunterladbares Produkt diese Prüfungen bereits zuverlässig durchführt.

## Lokaler Betrieb und Diagnose

Die Anwendung ist auf lokale Datenverwaltung ausgelegt. Daraus allein folgt **keine** DSGVO-Konformität für jeden Einsatzfall. Datenflüsse, API-Rechte, Aufbewahrung, Exporte und gegebenenfalls die eingesetzte n8n-Umgebung müssen im konkreten Kundenszenario beurteilt werden.

**Keine** vollständigen Workflow-JSONs, API-Schlüssel, Logdateien, personenbezogenen Daten oder vertraulichen Screenshots in öffentlich zugängliche Issues hochladen.

[Sicherheit](../SECURITY.md) · [Support](../SUPPORT.md) · [Anwenderhandbuch](USAGE_GUIDE.md)
