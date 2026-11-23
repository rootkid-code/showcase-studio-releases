# Security Policy

## Status

Showcase Studio hat zum Stand **23. November 2026** die öffentlich verfügbare **Vorabversion [`v1.0.0-beta.4`](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4)**. Es ist **keine Stable-Version**, und es wird derzeit keine unabhängige Sicherheitszertifizierung oder garantierte Support-SLA zugesichert. Ein Beta-Release ersetzt keine dokumentierte Freigabe der vollständigen Security- und Windows-Gates.

## Sicherheitsprobleme melden

**Bitte keine Sicherheitslücken, Tokens, personenbezogenen Daten oder echte n8n-Workflows in öffentlichen Issues veröffentlichen.**

- Wenn GitHub auf diesem Repository **Private Vulnerability Reporting** anbietet, diesen vertraulichen Meldeweg verwenden.
- Andernfalls den Repository-Inhaber über [sein GitHub-Profil](https://github.com/rootkid-code) für einen nichtöffentlichen Kontaktweg ansprechen; keine Exploit-Details in einem öffentlichen Issue hinterlegen.
- Nur die zur Reproduktion erforderlichen, bereinigten Angaben weitergeben; keine produktiven Zugangsdaten, Schlüsselmaterialien oder Kundendaten.

Es wird aktuell keine Reaktionszeit oder Sicherheitszertifizierung zugesichert.

## Sicherer Umgang mit Showcase Studio

- n8n-API-Berechtigungen auf lesenden Zugriff beschränken.
- Keine vollständigen Logs oder unbearbeiteten Workflow-Dateien in Issues posten.
- Inhalte vor HTML-, Bild- oder anderen öffentlichen Exporten manuell kontrollieren.
- Nur Artefakte aus den tatsächlichen [GitHub Releases](https://github.com/rootkid-code/showcase-studio-releases/releases) verwenden; für Beta 4 sind ZIP, SHA-256 und signiertes Update-Manifest in den Release Notes dokumentiert. Die Existenz der Dateien bedeutet nicht, dass diese Seite selbst deren Signaturen oder die Windows-Installation überprüft hat.

Weitere Hilfe: [SUPPORT.md](SUPPORT.md).
