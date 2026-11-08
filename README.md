# Chrome Profile Manager – Downloads

Chrome Profile Manager für Windows x64 mit .NET Framework 4.8.

**[Stable – ChromeProfileManager.exe herunterladen](https://github.com/mcdegi/chrome-profile-manager-releases/releases/latest/download/ChromeProfileManager.exe)**

[Testversion 0.2.3-beta.1 – ChromeProfileManager.exe](https://github.com/mcdegi/chrome-profile-manager-releases/releases/download/v0.2.3-beta.1/ChromeProfileManager.exe)

[Alle Releases, Änderungsbeschreibungen, ZIP-Dateien und Prüfsummen](https://github.com/mcdegi/chrome-profile-manager-releases/releases)

## Starten

1. Die gewünschte EXE in einem eigenen, beschreibbaren Ordner speichern. Stable und Test in getrennten Ordnern ablegen.
2. Die EXE starten und das eigene Chrome-Verzeichnis einrichten. Die Testversion verwendet eine getrennte Testumgebung mit eigenen Browserprofilen.
3. Persönliche Einstellungen und Browserprofile werden nicht mitgeliefert. Stable-Einstellungen liegen unter `%LOCALAPPDATA%\ChromeProfileManager`, Testdaten unter `%LOCALAPPDATA%\ChromeProfileManager.Test`.

## Updates

Ab 0.2.3 sind dieses öffentliche Repository unter dem GitHub-Konto **mcdegi** und der öffentliche Update-Prüfschlüssel in Stable und Test fest verankert. Die Quelle lässt sich im Programm und über die Einstellungsdatei nicht ändern. Ein GitHub-Konto ist zum Herunterladen und für die Updateprüfung nicht erforderlich. Zugangsdaten sind nicht in der EXE enthalten.

Stable erhält ausschließlich normale Releases. Test erhält ausschließlich Beta-Vorabversionen. Betas ersetzen nicht den aktuellen Stable-Download. Der Quellcode wird separat privat verwaltet.

Der Manager prüft bei geöffneter Anwendung einmal täglich automatisch, sofern der entsprechende Schalter aktiviert ist. Unter **Einstellungen → Anwendung → Version und Updates** lässt sich jederzeit manuell prüfen. Eine neue Version erscheint als Update-Hinweis. **Update herunterladen** lädt und prüft das Paket; **Installieren und neu starten** führt nach Bestätigung den Austausch aus. Dabei bleibt eine Sicherung der bisherigen EXE erhalten.

Für jede neue Version werden eine EXE, ein ZIP, SHA256-Prüfsummen und signierte Update-Metadaten veröffentlicht. Die App prüft vor der Installation die Signatur, den Kanal, die Version sowie Paket- und EXE-Prüfsummen. Änderungen am Quellcode allein lösen kein Update aus; dafür muss ein neuer vollständiger Release veröffentlicht sein.

Stable 0.2.2 kann über seine bereits eingerichtete Standardquelle aktualisiert werden. Ältere Versionen oder Testversionen ohne eingerichtete Quelle einmal durch die passende aktuelle EXE ersetzen. Alte manuell konfigurierte Quellen und Schlüssel werden ab 0.2.3 ignoriert; die Benutzervorgaben zur automatischen Prüfung bleiben erhalten.
