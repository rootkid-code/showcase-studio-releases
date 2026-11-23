<div align="center">

<img src="assets/brand/showcase-mark.svg" width="88" height="88" alt="Showcase Studio – originales Markenlogo" />

# SHOWCASE STUDIO

**Automationen verstehen. Workflows überzeugend präsentieren.**

Ein visueller, schreibgeschützter Workspace für n8n-Workflows – von der ersten Verbindung bis zur bewusst freigegebenen Präsentation.

<p>
  <img src="https://img.shields.io/badge/Windows-11-2563EB?style=flat-square&logo=windows11&logoColor=white" alt="Zielplattform: Windows 11" />
  <img src="https://img.shields.io/badge/n8n-Read--only-16A085?style=flat-square" alt="n8n-Integration: schreibgeschützt ausgelegt" />
  <img src="https://img.shields.io/badge/Release-Noch%20nicht%20ver%C3%B6ffentlicht-D97706?style=flat-square" alt="Noch kein öffentlicher Release" />
</p>

[**Releases**](https://github.com/rootkid-code/showcase-studio-releases/releases) ·
[**Produktvorschau**](#produktvorschau) ·
[**Installation**](#installation-nach-releasefreigabe) ·
[**Hilfe**](SUPPORT.md) ·
[**Sicherheit**](SECURITY.md)

</div>

<p align="center">
  <img src="assets/brand/repo-hero.svg" width="100%" alt="Showcase Studio: originale Konzeptgrafik zu einem visuellen, schreibgeschützten Workflow-Explorer – keine Aufnahme der Anwendung" />
</p>

> [!IMPORTANT]
> **Aktuell noch kein öffentlicher Download.** Dieses Repository ist für die spätere Verteilung von Showcase Studio vorgesehen. Zum Stand **23. November 2026** gibt es hier **keine veröffentlichten GitHub Releases**. Ein privater Release Candidate wird entwickelt; die native Windows-Installer-End-to-End-Abnahme steht noch aus. Verbindlich sind immer die tatsächlich vorhandenen Einträge unter [Releases](https://github.com/rootkid-code/showcase-studio-releases/releases). Das GitHub-Menü **Code → Download ZIP** enthält **nicht** die Anwendung.

## Was ist Showcase Studio?

In n8n steckt die Logik eines Prozesses oft in komplexen Node-Netzwerken, technischen Verbindungen und langen Sticky Notes. **Showcase Studio macht daraus einen verständlichen Präsentations- und Review-Workspace**, ohne einen Workflow zum Vorführen ausführen zu müssen.

| Entdecken | Verstehen | Präsentieren |
| :--- | :--- | :--- |
| n8n-Workflows über einen geführten Verbindungsprozess oder JSON-Import betrachten. | Canvas, Node-Fokus, Abschnitte und Notizen helfen beim Lesen komplexer Abläufe. | Ansichten aufbereiten und Inhalte vor einem öffentlichen Export bewusst prüfen. |
| **Read-only als Produktprinzip** | **Vom Detail zur Gesamtansicht** | **Freigabe statt versehentlichem Teilen** |

### Für wen?

Für **KI- und Automationsberater, Agenturen, Entwickler und Projektteams**, die technische Workflows gegenüber Kunden oder Kollegen strukturiert erklären möchten – ohne dafür Zugang zu einem ausführbaren Workflow zu benötigen.

## Produktvorschau

<p align="center">
  <img src="assets/screenshots/workspace-overview.png" width="100%" alt="Entwicklungs-Screenshot der Showcase-Studio-Übersicht mit Demo-Workflows, Workspace-Navigation und Schnellaktionen" />
  <br />
  <sub>01 — Workspace & Dashboard · Entwicklungsansicht mit ausschließlich beispielhaften Workflow-Inhalten</sub>
</p>

<table>
<tr>
<td width="50%" valign="top">
  <img src="assets/screenshots/workflow-details.png" alt="Workflow-Präsentationsstudio mit Canvas, Prozessabschnitten, Sticky Notes und Element-Inspektor" width="100%" />
  <br /><sub><strong>02 — Workflow-Canvas.</strong> Zusammenhänge und Notizen gezielt erklären.</sub>
</td>
<td width="50%" valign="top">
  <img src="assets/screenshots/n8n-connection.png" alt="Verbindungsassistent mit lokaler n8n-Adresse und Anleitung für lesende API-Berechtigungen" width="100%" />
  <br /><sub><strong>03 — n8n verbinden.</strong> Geführter Einstieg und Hinweise zu minimalen Rechten.</sub>
</td>
</tr>
</table>

<sub>**Hinweis zu den Bildern:** Originale Showcase-Studio-UI-Vorschauen aus dem privaten Entwicklungsprojekt, mit Demo- beziehungsweise Beispielinhalten. Sie sind weder Nachweis einer öffentlichen Release-Freigabe noch Garantie für eine unveränderte finale Oberfläche.</sub>

## So ist der Workflow gedacht

```mermaid
flowchart LR
    A["n8n / JSON-Import"] --> B["Workflow lesen"]
    B --> C["Canvas & Abschnitte erkunden"]
    C --> D["Inhalte manuell prüfen"]
    D --> E["Freigegebene Präsentation"]
```

- **Keine Workflow-Ausführung zum Präsentieren:** Showcase Studio ist auf lesende Erkundung ausgelegt und ersetzt nicht die n8n-Laufzeit.
- **Klare Trennung von privat und öffentlich:** Lokale Originalinhalte und bewusst freigegebene Ansichten sind unterschiedliche Bereiche.
- **Kontrolle vor dem Teilen:** Node-Texte, Sticky Notes und Geschäftslogik können vertraulich sein – vor einem Export müssen sie geprüft werden.
- **Lokaler Windows-Einstieg:** Die geplante Distribution setzt auf einen geführten Installer statt auf Terminalbefehle im Alltag.

> [!NOTE]
> Diese Punkte beschreiben das im privaten Entwicklungsstand dokumentierte Produktkonzept und seine vorhandenen UI-Bereiche. Sie stellen **keine unabhängige Sicherheitszertifizierung** und keinen vollständig abgenommenen Windows-Release dar.

## Installation nach Releasefreigabe

Sobald eine tatsächlich freigegebene Windows-Version vorhanden ist:

1. Die passende ZIP-Datei **ausschließlich aus** [GitHub Releases](https://github.com/rootkid-code/showcase-studio-releases/releases) herunterladen und die zugehörigen Release Notes lesen.
2. Falls veröffentlicht, den **SHA-256-Prüfwert** mit der Release-Angabe vergleichen; die ZIP anschließend vollständig entpacken.
3. Im entpackten Paket `00-START-HIER.html` öffnen und dem Installationsassistenten folgen. Der im Entwicklungsstand vorgesehene Einstieg heißt `01-INSTALLIEREN.vbs`.
4. Nach erfolgreicher Installation die Anwendung über den bereitgestellten Starter beziehungsweise die angelegte Verknüpfung öffnen.
5. Für eine n8n-Verbindung **nur erforderliche Leserechte** vergeben. API-Schlüssel niemals in Screenshots, Issues oder exportierten Beispielen veröffentlichen.

**Voraussetzungen / Umfang:** Zielplattform ist Windows 11; eine erreichbare n8n-Instanz oder ein geeigneter JSON-Workflow ist für die entsprechende Nutzung erforderlich. Verbindliche Systemvoraussetzungen, Paketnamen und gegebenenfalls geänderte Installationsschritte werden **erst in den jeweiligen Release Notes** festgelegt. Es ist derzeit **kein installierbares Paket** in diesem Repository veröffentlicht.

## Downloads & Versionsstand

| Bereich | Öffentlicher Stand |
| :--- | :--- |
| [Neueste Releases](https://github.com/rootkid-code/showcase-studio-releases/releases) | Noch keine Veröffentlichung (Stand 23.11.2026) |
| Windows-Installer | Native End-to-End-Abnahme vor Freigabe ausstehend |
| Release Notes / Prüfsummen | Werden je veröffentlichtem Artefakt bereitgestellt, sofern verfügbar |
| Quellcode | Nicht Bestandteil dieses öffentlichen Distributionsrepositories |
| Release-Prozess | [Freigabe- und Integritätskriterien](docs/RELEASE_POLICY.md) |

**Wichtig:** Der private Entwicklungsstand und interne Versionsbezeichnungen sind **keine** öffentlichen Downloadversionen.

## Sicherheit & Datenschutz

Showcase Studio behandelt die **Lesbarkeit technischer Automationen** als Produktfunktion – und die **Freigabe von Informationen** als eigenen Arbeitsschritt. Das ersetzt keine Prüfung der gewählten n8n-Berechtigungen, der Exportinhalte oder der tatsächlichen Windows-Paketierung.

- n8n-Zugriff auf das notwendige Minimum einschränken; keine Schreib-, Ausführungs- oder Credential-Rechte für reine Präsentationen erteilen.
- Vor einer Veröffentlichung alle personenbezogenen Informationen, URLs, interne Kommentare, Credentials und Geschäftsdetails prüfen.
- Keine echten API-Schlüssel, Workflow-Exporte oder vollständigen Diagnoseprotokolle in öffentliche Issues hochladen.
- Private Lizenz-Publisher, Signaturschlüssel und interne Werkzeuge dürfen **nicht** in Endnutzer-Releases gelangen.

Sicherheitsmeldungen: [SECURITY.md](SECURITY.md) · Hilfestellung und redigierte Fehlerberichte: [SUPPORT.md](SUPPORT.md)

## Häufige Fragen

<details>
<summary><strong>Wo kann ich Showcase Studio herunterladen?</strong></summary>

Aktuell noch nicht öffentlich. Sobald eine Version freigegeben ist, erscheint sie mit Dateien und Release Notes auf der <a href="https://github.com/rootkid-code/showcase-studio-releases/releases">GitHub-Releases-Seite</a>. Ein grüner `Code`-Button ist kein Anwendungsdownload.

</details>

<details>
<summary><strong>Verändert Showcase Studio meine n8n-Workflows?</strong></summary>

Die Anwendung ist als **Read-only-Explorer** konzipiert. Verwende trotzdem nur einen n8n-API-Key mit den minimal erforderlichen Leserechten. Die tatsächlichen Rechte werden auf Seite der n8n-Instanz durchgesetzt.

</details>

<details>
<summary><strong>Ist dieses Repository Open Source?</strong></summary>

Nein. Dieses öffentliche Repository dient zur Produktinformation und, nach Freigabe, zur Bereitstellung von Release-Artefakten. Eine Veröffentlichung ist **nicht automatisch eine Open-Source-Lizenz**. Siehe <a href="NOTICE.md">Rechte und Hinweise</a>; zukünftige Softwarepakete können gesonderten Nutzungsbedingungen unterliegen.

</details>

---

<div align="center">
  <sub>© 2026 Florian Windhager · Showcase Studio · Alle Rechte vorbehalten</sub>
  <br />
  <sub>Original-Logo und Produktgrafiken · Keine Herausgabe privater Entwicklungs- oder Lizenzierungswerkzeuge</sub>
</div>
