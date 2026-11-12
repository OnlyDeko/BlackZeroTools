# BLACK ZERO Tools

Downloads der BLACK-ZERO-Windows-Tools. © 2026 OnlyDeko

## Download

Die aktuellen Versionen findest du unter **[Releases](https://github.com/OnlyDeko/BlackZeroTools/releases)**:

| Tool | Datei | Hinweis |
|---|---|---|
| **BLACK ZERO System Toolkit** – Wartung, Diagnose, Auto-Repair und sichere Optimierung für Windows 11 | `BlackZeroToolkit-Setup-<Version>.exe` | Installation ohne Adminrechte. Fehlt die .NET-Desktop-Runtime, bietet der Installer an, sie direkt von Microsoft zu laden. |
| | `BlackZeroToolkit-<Version>-portable-win-x64.zip` | Ohne Installation, läuft ohne installiertes .NET |
| **BLACK ZERO Audio** – Musikplayer mit 8-Band-EQ, Visualizern, Szenen und Themes | `BlackZeroAudio-Setup-1.0.0.exe` / `.zip` | |

## Automatische Updates (System Toolkit)

Das installierte Toolkit prüft beim Start, ob es eine neue Version gibt, und installiert sie (einstellbar unter *Einstellungen → Updates*: automatisch, nur benachrichtigen oder aus).

- Update-Information: [`toolkit/latest.json`](toolkit/latest.json), signiert mit RSA-3072/SHA-256 ([`toolkit/latest.json.sig`](toolkit/latest.json.sig)). Der öffentliche Schlüssel ist fest im Toolkit eingebaut.
- Installiert wird nur, wenn Signatur, Download-Adresse (nur Releases dieses Repos), Versionsnummer, Größe und SHA-256-Prüfsumme stimmen.
- Beim Update-Check wird nur diese Datei abgerufen – es werden keine Nutzungs- oder Systemdaten gesendet.
