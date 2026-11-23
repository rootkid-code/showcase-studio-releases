# Feature-Status · Showcase Studio

**Stand: 23. November 2026 · Öffentliche Vorabversion: [`v1.0.0-beta.4`](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4)**

> [!IMPORTANT]
> **„In Beta 4 beschrieben“ bedeutet nicht „unabhängig geprüft“ oder „Stable“.** Die öffentlichen Release Notes sind die Funktionsbeschreibung der ausgelieferten Beta. Für diese Dokumentationsaktualisierung wurde das Windows-ZIP nicht installiert oder der darin enthaltene Code unabhängig auditiert. Reale Tests, Sicherheitsprüfung und Freigabe bleiben getrennte Nachweise.

## Drei Ebenen unterscheiden

| Kennzeichnung | Bedeutung |
|:--|:--|
| **Öffentliche Beta** | Ein konkretes, herunterladbares Pre-release mit Dateianhang und Release Notes ist vorhanden. |
| **Im Beta-4-Release beschrieben** | Eine Funktion wird vom veröffentlichten Release dokumentiert, ohne dass daraus ein unabhängiger QA-Nachweis entsteht. |
| **Geplant / HOLD** | Konzeption oder private Entwicklungsarbeit; **nicht** als öffentliche Funktion versprechen. |

## Funktionsübersicht

| Bereich | Beta-4-Release-Status | Was noch abzugrenzen ist |
|:--|:--|:--|
| n8n JSON / Verbindung | **Im öffentlichen Beta-4-Release beschrieben** | Read-only-Rechte und reale n8n-Varianten testen |
| Canvas, Notes, Fokus, Layout | **Im öffentlichen Beta-4-Release beschrieben** | Großflächige Browser-/Windows-Layouttests |
| **7 Styles: n8n, Make, Zapier, Blueprint, Aurora, Sketch, Metro** | **Im öffentlichen Beta-4-Release beschrieben** | Make/Zapier sind hier **Visual-Looks, keine Adapter** |
| Workflow-Landkarte, Subflows | **Im öffentlichen Beta-4-Release beschrieben** | Korrekte Verknüpfungen und unbekannte Fälle |
| Versionen, Vergleich, optionaler Sync | **Im öffentlichen Beta-4-Release beschrieben** | Reimport und Datenerhalt bei Fehlern |
| HTML/SVG/PNG/PDF/Markdown/Mermaid/Collection | **Im öffentlichen Beta-4-Release beschrieben** | Exportparität, Offline-/Printqualität |
| Privacy Scan, Korrekturen, Freigaben | **Im öffentlichen Beta-4-Release beschrieben** | Fehlalarme, PII/Secret-Regressionen und Endkontrolle |
| Vorlagen, Guided Setup, Dark/Light | **Im öffentlichen Beta-4-Release beschrieben** | A11y, Fokus und Win-Scaling |
| Beta-ZIP, Update-Manifest, Signaturdatei | **Öffentliche Artefakte vorhanden** | Signaturkette, Paketinhalt und nativer Upgrade-Test nicht unabhängig verifiziert |
| **Make Blueprint JSON importieren** | **Geplant** | File-first Adapter, Fixture-/Security-Gates |
| **Zapier Classic JSON importieren** | **Geplant** | Tarifabhängigkeit und echte Export-Fixtures |
| Node-RED / Power Automate / Activepieces | **Discovery / HOLD** | Kein Versand-/API- oder Formatversprechen |
| Pro, Checkout, Preisgestaltung | **HOLD** | Keine öffentliche Verkaufsfreigabe |
| Stable Windows / macOS | **Nicht freigegeben** | Native Tests, Security Review, Freigaben |

## Öffentlicher Download

[`v1.0.0-beta.4`](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4) wurde am **23.11.2026** als Pre-release veröffentlicht. Unter **Assets** existieren:

- `ShowcaseStudio-1.0.0-beta.4.zip` (Windows-Paket)
- `release.json` (Release-Manifest)
- `release.json.sig` (Signaturdatei des Manifests)

Der dokumentierte SHA-256-Hash für die ZIP ist:

`b67cf8906d95a0ee7da97a2363e620aee23620510513fe7294992ffc055e4bb2`

Die Existenz von Prüfsumme/Signaturdatei ist **nicht** gleichbedeutend mit einer hier durchgeführten Signaturprüfung oder einem Installer-PASS.

## Was vor Stable nachgewiesen sein muss

1. Reale Windows-10/11-Installation, Start, Upgrade, Rollback, Deinstallation und Bibliotheks-Datenerhalt.
2. Negative Backend-/Session-/Host-/Origin- und n8n-Rechteprüfungen.
3. Privacy- und Content-/HTML-/SVG-/PDF-Egress-Tests mit synthetischen Gegenbeispielen.
4. A11y und 7-Look-Regressionen in Dark/Light, hohen Zoom-/DPI-Stufen, Exportvarianten.
5. Binärpaket-, Publisher-/Private-Key-/Secret-Scan; reproduzierbare Build-Provenienz und eindeutige Freigabe.

[Erste Schritte](GETTING_STARTED.md) · [Release-Policy](RELEASE_POLICY.md) · [Produktprioritäten](PROJECT_DIRECTION.md) · [README](../README.md)
