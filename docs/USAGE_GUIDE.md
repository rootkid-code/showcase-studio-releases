# Showcase Studio · Anwenderhandbuch

> **Stand: öffentliches [Beta-4-Pre-release](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4).** Die folgende Nutzung orientiert sich an der Produktarchitektur und den Release Notes; eine unabhängige Windows-/Security-Abnahme ist damit nicht belegt. Konkrete Details können sich bis Stable ändern.

## 1 · Workflows einlesen

**Variante A: JSON-Datei.** Einen n8n-Workflow als JSON mit fiktiven Daten exportieren, anschließend im Studio importieren. Quelle nicht bearbeiten und keine eingebetteten sensiblen Parameter weitergeben.

**Variante B: n8n-Verbindung.** Die Adresse der eigenen n8n-Instanz wählen (lokal, Docker, Cloud oder HTTPS-Server) und einen auf das Lesen beschränkten API-Key verwenden. Testen, ob nur gewünschte Workflows gelesen werden. Die tatsächlichen Zugriffsrechte müssen **n8n-seitig** begrenzt sein.

## 2 · Im Canvas orientieren

- **Gesamtübersicht:** Trigger, Aktionen, Verzweigungen und zusammengehörige Abschnitte sehen.
- **Fokus:** Einen Node wählen, seine Position im Ablauf und begleitende Details erläutern.
- **Notizen:** Sticky Notes und Beschriftungen lesen; sensible Inhalte ausschließlich im privaten Kontext anzeigen.
- **Präsentationsansicht:** Für den jeweiligen Termin eine gut lesbare Darstellung wählen und den Ablauf logisch statt technisch erzählen.

Die **Beta-4-Release-Notes beschreiben** außerdem Workflow-Landkarte, Sub-Workflows, Layout-Entzerrung, Node-Erklärungen und Versionsvergleich. Welche Fälle in deiner Testumgebung funktionieren, muss am tatsächlichen Paket geprüft werden.

## 3 · Für Kunden verständlich präsentieren

Ein gutes Ablaufbeispiel besteht aus fünf Fragen:

1. Welches Geschäftsproblem löst der Workflow?
2. Wo beginnt der Prozess, und was löst ihn aus?
3. Welche Entscheidungen und Systemübergaben gibt es?
4. Wann greift ein Mensch ein, und welche Fehlerfälle existieren?
5. Was ist nachweisbar – und was ist Annahme, Testdatenlage oder ein offener Punkt?

Dadurch kann Showcase Studio als **Präsentations-/Dokumentationswerkzeug** dienen, nicht als Ersatz für Prozessvalidierung, Monitoring oder Audit-Trails.

## 4 · Ausgabe und Veröffentlichung

Die **Beta-4-Release-Notes nennen** interaktives HTML, SVG, PNG, Markdown, Mermaid, PDF-Handout, Galerien und einbettbare Ansichten. Welche Funktionen in der aktuellen Installation tatsächlich verlässlich funktionieren, muss getestet werden. Make- und Zapier-Looks sind **keine** Unterstützung für Make-/Zapier-Dateiimporte.

Vor dem Teilen: Testdaten wählen, private Originaltexte prüfen, Risiko- und Datenfreigabe bestätigen, Ausgabe selbst öffnen und den Inhalt gegen die freigegebene Vorschau vergleichen.

Weitere Hinweise: [Datenschutz & Export](PRIVACY_AND_EXPORT.md).

## 5 · Eigene Daten schützen

Keine automatischen Löschungen, keine ungefragten Updates, keine echten Kundenworkflows als Issue-Anhang. Bei Installations-, Export- und Updateproblemen die originalen Bibliotheksdaten sichern und nur redigierte Diagnoseinformationen weitergeben.

[Erste Schritte](GETTING_STARTED.md) · [Fehlersuche](TROUBLESHOOTING.md) · [Feature-Status](FEATURE_STATUS.md)
