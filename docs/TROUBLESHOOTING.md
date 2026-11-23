# Fehlerbehebung · Showcase Studio

> Das [öffentliche Prerelease v1.0.0-beta.3](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.3) enthält ein Windows-ZIP. Vollständige Windows-/Security-E2E-Nachweise sind hier jedoch noch nicht als bestanden dokumentiert.

## Ich finde keine Installationsdatei

Unter den [Beta.3-Assets](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.3) liegt **ShowcaseStudio-1.0.0-beta.3.zip**. Es muss vollständig entpackt werden; laut Release Notes startet **01-INSTALLIEREN.vbs** die Installation. Das GitHub-**Code → Download ZIP** ist nur die Dokumentation.

## Die n8n-Verbindung klappt nicht

Prüfe in dieser Reihenfolge:

1. Ist deine n8n-Instanz im Browser auf dem betroffenen Rechner erreichbar?
2. Stimmt die **Basisadresse** (nicht eine Workflow-Editor-URL oder ein API-Key-Pfad)?
3. Ist n8n lokal, in Docker, in der Cloud oder auf einem fremden HTTPS-Host? `localhost` verweist immer auf **die Maschine beziehungsweise den Container**, in der beziehungsweise dem der jeweilige Prozess läuft.
4. Hat dein Key die erforderlichen **minimalen** Leseberechtigungen? Bei 401/403 die Rechte in n8n prüfen, nicht pauschal Vollzugriff erteilen.
5. Falls HTTPS benutzt wird: Hostname, Zertifikat und Netzwerkrichtlinien prüfen, ohne Zertifikatswarnungen zu ignorieren.

Teile niemals den API-Key, echte Workflow-JSONs oder vollständige Request-Headers in einem Issue.

## Import oder Anzeige ist unvollständig

Mit einem synthetischen, kleinen JSON-Workflow wiederholen. Bei großen Flows zuerst die Lesbarkeit von Sticky Notes, Abschnitten und Zoom prüfen. Änderungen am Original-Workflow sind für eine Präsentation nicht erforderlich.

## Export enthält sensible Informationen

**Nicht weitergeben.** Den freigegebenen Darstellungsstand erneut prüfen, Notizen und URLs bereinigen, Export erneut erzeugen und die konkrete Datei vor der Veröffentlichung öffnen. Siehe [Datenschutz & Export](PRIVACY_AND_EXPORT.md).

## Installation / Start / Upgrade

Bei Beta.3: Release Notes, Archivhash, Windows-Version, Installer-Log und lokale Berechtigungen prüfen; Sicherheitswarnungen nicht pauschal umgehen. Bestehende Bibliotheksdaten vorher sichern. **Keine** fremden Python-, Docker- oder n8n-Installationen löschen, um ein Studio-Problem zu beheben.

## Einen Fehler melden

Eine [Issue-Vorlage](https://github.com/rootkid-code/showcase-studio-releases/issues/new/choose) verwenden, nur mit einer **tatsächlich veröffentlichten** Version. Windows-Build, Reproduktionsschritte und vollständig bereinigte Fehlermeldung nennen. Sicherheitsprobleme vertraulich über [SECURITY.md](../SECURITY.md) melden.

[Erste Schritte](GETTING_STARTED.md) · [Support](../SUPPORT.md)
