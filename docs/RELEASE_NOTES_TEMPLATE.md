# Showcase Studio – Release Notes Template

> **VORLAGE, KEIN RELEASE.** Nicht als tatsächliche veröffentlichte Version ausgeben. Die Platzhalter erst bei geprüfter Freigabe ersetzen.

## Version: `vX.Y.Z[-beta.N]`

- Release-Datum: `YYYY-MM-DD`
- Kanal: `preview | stable`
- Verantwortliche Freigabe: `<Name / Review>`
- Git-Commit / Build-Identität: `<SHA>`
- Plattform/Architektur: `<Windows-Build und Architektur>`

### Was ist neu?

- `<Echte, durch Test belegte Funktionen>`

### Was wurde behoben?

- `<Reproduzierte und geprüfte Fixes>`

### Downloads

| Datei | Größe | SHA-256 | Signaturstatus |
|:--|:--|:--|:--|
| `<exakter Dateiname>` | `<Bytes>` | `<64 hex Zeichen>` | `<signiert/verifiziert oder nicht signiert>` |

**Keine Dateien/Hashwerte erfinden.** Alle Angaben auf das **hochgeladene** Artefakt beziehen.

### Installation und Upgrade

1. `<Nachvollziehbare Installationsschritte>`
2. `<Voraussetzungen, Admin-Rechte, Benutzerordner>`
3. `<Backup/Upgrade/Rollback>`
4. `<Deinstallation und Datenerhalt>`

### Verifikation

- [ ] Release-Artefakt gebaut und Dateiliste auf private Publisher-Quellen, Credentials, PEM, Datenbanken, Workflow-Exports, Logs und PII gescannt
- [ ] Windows-native Installation/Start/Upgrade/Uninstall auf Zielsystem getestet
- [ ] Read-only n8n und Host/Origin/Session-Negativtests bestanden
- [ ] Export-Privacy-Gate und Dateiausgabe geprüft
- [ ] Dark-/Light-/Tastatur- und README-/Dokumentationsansichten geprüft
- [ ] SHA-256 vom tatsächlichen Upload erneut berechnet
- [ ] Marken-SVG/PNG und Screenshots mit der ausgelieferten Build-Version abgeglichen
- [ ] Freigabeverantwortliche Person hat die dokumentierten Gates akzeptiert

### Bekannte Einschränkungen

- `<Keine Stable-Zusage, falls Beta>`

### Support

[Hilfe](../SUPPORT.md) · [Sicherheit](../SECURITY.md) · [Release-Kriterien](RELEASE_POLICY.md)
