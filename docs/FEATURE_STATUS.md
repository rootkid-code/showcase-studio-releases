# Feature-Status & Produktgrenzen

**Stand:** 23.11.2026. Diese Tabelle unterscheidet **Quellcode im privaten Entwicklungszweig** von einer **öffentlich installierbaren, getesteten Version**. Sie ist kein Testprotokoll.

| Funktionsbereich | Code-/Dokumentationslage | Öffentliche Freigabe |
|:--|:--|:--|
| Lesender n8n-Import und JSON-Einstieg | Im privaten Projekt vorhanden | **Nicht veröffentlicht** |
| Canvas / Node-Fokus / Sticky Notes | Im privaten Projekt vorhanden | **Nicht veröffentlicht** |
| Theme-Farben und Gold-Logo | Neue Assets in Entwicklungszweig; Marken-Synchronisierung dokumentiert | **Marketingassets öffentlich**, App nicht |
| Workflow-Landkarte & Subflow-Navigation | Im privaten 14.1-Entwicklungszweig implementiert | **Nicht veröffentlicht** |
| Versionshistorie / Vergleich / optionaler Sync | Im privaten 14.1-Entwicklungszweig dokumentiert und implementiert | **Nicht veröffentlicht** |
| HTML / SVG / PNG / Markdown / Mermaid / JSON-Exporte | Exportmodule im privaten Entwicklungszweig vorhanden | **Nicht öffentlich abgenommen** |
| PDF / Embed / Sammelexport | Im fortgeschrittenen Entwicklungszweig implementiert | **Nicht öffentlich abgenommen** |
| Erweiterte Erklärungen und Privacy-Prüfung | Im privaten Beta-Entwicklungszweig vorhanden | **Nicht öffentlich abgenommen** |
| Windows Installer / Start / Upgrade / Uninstall | Installer-Code vorhanden, native E2E-Gates ausstehend | **Kein Public-Build** |
| Free-/Pro-Lizenzierung und signierte Updates | Private Entwicklung / QA- und Paketfreigabe erforderlich | **Kein kaufbares Produkt** |
| macOS | Experimentelle Zweige vorhanden | **Kein macOS-Public-Release** |

## Vertrauensniveaus

- **Code vorhanden:** Quelldateien/Funktionsmodule sind einsehbar im privaten Entwicklungsrepo; das beweist noch keine vollständig geprüfte Benutzbarkeit.
- **QA bestätigt:** Reproduzierbare Tests und manuelle Plattform-Abnahme mit Build-/Commit-Zuordnung wurden durchgeführt.
- **Öffentlich freigegeben:** Das konkrete, geprüfte Paket ist im [Release-Kanal](https://github.com/rootkid-code/showcase-studio-releases/releases) vorhanden.

**Aktuell ist ausschließlich der öffentliche Marken-/Dokumentationsstand verfügbar**, keine installierbare App.

## Bevor du Funktionen produktiv anbietest

- Native Windows-Installation inklusive Upgrade, Deinstallation, Daten-/Rollback-Proben.
- Backend- und Browser-Tests mit negativen Security-/Privacy-Szenarien.
- Exportvergleiche mit echten Demo-Workflows; vertrauliche Inhalte dürfen nicht unbeabsichtigt ausgegeben werden.
- Installationsdatei, Versionsnummer, Signaturstatus und SHA-256-Prüfsummen pro Release nachweisen.
- Prüfen, ob fremde n8n-/Drittherstellerlizenzen für die gewählte Vertriebsform relevant sind.

[Release-Standard](RELEASE_POLICY.md) · [Nutzerhandbuch](USAGE_GUIDE.md)
