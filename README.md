# Chrome Profile Manager – Stable-Downloads

Chrome Profile Manager für Windows x64 mit .NET Framework 4.8.

**[ChromeProfileManager.exe herunterladen](https://github.com/mcdegi/chrome-profile-manager-releases/releases/latest/download/ChromeProfileManager.exe)**

[Alle Stable-Releases, Änderungsbeschreibungen, ZIP-Dateien und Prüfsummen](https://github.com/mcdegi/chrome-profile-manager-releases/releases)

## Starten

1. `ChromeProfileManager.exe` in einem eigenen, beschreibbaren Ordner speichern.
2. Die EXE starten und das eigene Chrome-Verzeichnis einrichten.
3. Persönliche Einstellungen und Browserprofile werden nicht mitgeliefert. Die Manager-Einstellungen liegen unter `%LOCALAPPDATA%\ChromeProfileManager`.

## Updates

Ab Stable 0.2.2 sind dieses öffentliche Repository und der öffentliche Update-Prüfschlüssel bereits eingerichtet. Ein GitHub-Konto ist zum Herunterladen und für die Updateprüfung nicht erforderlich.

Der Manager prüft bei geöffneter Anwendung höchstens einmal täglich automatisch. Unter **Einstellungen → Anwendung → Version und Updates** lässt sich jederzeit manuell prüfen. Eine neue Version erscheint als Update-Hinweis. **Update herunterladen** lädt und prüft das Paket; **Installieren und neu starten** führt nach Bestätigung den Austausch aus. Dabei bleibt eine Sicherung der bisherigen EXE erhalten.

Für jede neue Version werden eine EXE, ein ZIP, SHA256-Prüfsummen und signierte Update-Metadaten veröffentlicht. Die App prüft vor der Installation die Signatur, den Stable-Kanal, die Version sowie Paket- und EXE-Prüfsummen. Änderungen am Quellcode allein lösen kein Update aus; dafür muss ein neuer vollständiger Stable-Release veröffentlicht sein.

Versionen bis einschließlich 0.2.1 einmal durch die aktuelle EXE ersetzen oder die Updatequelle mit dem öffentlichen Schlüssel manuell einrichten. Danach laufen weitere Updates direkt im Programm.

Dieses Repository enthält die öffentlichen Stable-Downloads. Quellcode und Testversionen werden getrennt verwaltet.
