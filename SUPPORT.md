# Support & Hilfe

Dieses Repository dient als **öffentlicher Release- und Informationskanal** für Showcase Studio. **Noch kein öffentlicher Download vorhanden** (Stand 23. November 2026).

## Vor einer Meldung

1. Prüfe die [Release-Liste](https://github.com/rootkid-code/showcase-studio-releases/releases) und die zu deiner Version gehörenden Release Notes.
2. Prüfe die dokumentierten Systemanforderungen und stelle sicher, dass ein offizielles Paket verwendet wurde.
3. Suche in [bestehenden Issues](https://github.com/rootkid-code/showcase-studio-releases/issues), ob der Fehler bereits bekannt ist.

## Fehler melden

Nutze die [Issue-Vorlage](https://github.com/rootkid-code/showcase-studio-releases/issues/new/choose) und beschreibe:

- Verwendete **öffentliche Release-Version** (nicht nur einen internen RC-Namen)
- Windows-Version und Art der Installation
- Erwartetes und beobachtetes Verhalten
- Reproduktionsschritte mit **synthetischen Beispieldaten**
- Relevante, **anonymisierte** Fehlermeldung

**Vor dem Hochladen entfernen:** API-Keys, Tokens, lokale Benutzer-/Kundenpfade, URLs interner Instanzen, E-Mail-Adressen, vertrauliche Node-Texte, personenbezogene Daten sowie unbereinigte Logs.

### Sicherheitsthema?

Bitte **kein öffentliches Issue** mit Schwachstellendetails anlegen. Den vertraulichen Meldeweg in [SECURITY.md](SECURITY.md) verwenden.

## Häufige Installationsfragen

- **Es gibt keine ZIP zum Herunterladen:** Bisher ist kein GitHub Release veröffentlicht. Der `Code`-Download ist kein Installer.
- **n8n-Verbindung schlägt fehl:** Prüfe zunächst den Host deiner n8n-Instanz, die Erreichbarkeit und die erforderlichen Leseberechtigungen; teile den API-Key niemals öffentlich.
- **Windows-Setup startet nicht:** Wenn später ein Release existiert, gelten die dort mitgelieferten Hinweise, die lokalen Fallbacks und die jeweiligen Supportinformationen. Vorher lässt sich kein öffentliches Installationspaket diagnostizieren.

[Zurück zur Produktübersicht](README.md)
