# Support & Hilfe

Dieses Repository dient als **öffentlicher Release- und Informationskanal** für Showcase Studio. **Aktuelle öffentliche Vorabversion:** [`v1.0.0-beta.4`](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4) (Stand 23. November 2026). Keine stabile Produktfreigabe oder zugesicherte Support-SLA.

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

- **Wo ist die ZIP?** Im [Beta-4-Release](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4) unter **Assets**. `Code → Download ZIP` ist kein Installer.
- **n8n-Verbindung schlägt fehl:** Prüfe zunächst den Host deiner n8n-Instanz, die Erreichbarkeit und die erforderlichen Leseberechtigungen; teile den API-Key niemals öffentlich.
- **Windows-Setup startet nicht:** Beta-ZIP vollständig entpacken und `01-INSTALLIEREN.vbs` laut Release Notes ausführen. Kein Windows-Schutzsystem pauschal deaktivieren, keine fremden Python-/n8n-Installationen löschen. Vor einem Update Daten sichern.

[Zurück zur Produktübersicht](README.md)
