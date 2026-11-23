# Support & Hilfe

Dieses Repository dient als **öffentlicher Release- und Informationskanal** für Showcase Studio. **Öffentliches Prerelease [v1.0.0-beta.3](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.3) verfügbar** (Stand 23. November 2026); keine bestätigte Stable-Abnahme.

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

- **Download:** In den [Assets von Beta.3](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.3) liegt **ShowcaseStudio-1.0.0-beta.3.zip**. Der GitHub-**Code → Download ZIP**-Button ist kein Installer.
- **n8n-Verbindung schlägt fehl:** Prüfe zunächst den Host deiner n8n-Instanz, die Erreichbarkeit und die erforderlichen Leseberechtigungen; teile den API-Key niemals öffentlich.
- **Windows-Setup startet nicht:** ZIP-Hash prüfen, Archiv vollständig entpacken und die in Beta.3 enthaltenen Installer-Hinweise beachten. Sicherheitssperren nicht pauschal umgehen. [Installationshilfe](docs/GETTING_STARTED.md).

[Zurück zur Produktübersicht](README.md)
