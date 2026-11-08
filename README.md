# Chrome Profile Manager – Downloads

Chrome Profile Manager für Windows x64 mit .NET Framework 4.8.

**[Stable – ChromeProfileManager.exe herunterladen](https://github.com/mcdegi/chrome-profile-manager-releases/releases/latest/download/ChromeProfileManager.exe)**

[Testversion 0.2.6-beta.1 – ChromeProfileManager.exe](https://github.com/mcdegi/chrome-profile-manager-releases/releases/download/v0.2.6-beta.1/ChromeProfileManager.exe)

[Alle Releases, Änderungsbeschreibungen, ZIP-Dateien und Prüfsummen](https://github.com/mcdegi/chrome-profile-manager-releases/releases)

## Starten

1. Die gewünschte EXE in einem eigenen, beschreibbaren Ordner speichern. Stable und Test in getrennten Ordnern ablegen.
2. Die EXE starten und das eigene Chrome-Verzeichnis einrichten. Die Testversion verwendet eine getrennte Testumgebung mit eigenen Browserprofilen.
3. Persönliche Einstellungen und Browserprofile werden nicht mitgeliefert. Stable-Einstellungen liegen unter `%LOCALAPPDATA%\ChromeProfileManager`, Testdaten unter `%LOCALAPPDATA%\ChromeProfileManager.Test`.

## Updates

Dieses öffentliche Repository unter dem GitHub-Konto **mcdegi** und der öffentliche Update-Prüfschlüssel sind in Stable und Test fest verankert. Die Quelle lässt sich im Programm und über die Einstellungsdatei nicht ändern. Ein GitHub-Konto ist zum Herunterladen und für die Updateprüfung nicht erforderlich. Zugangsdaten sind nicht in der EXE enthalten.

Stable erhält ausschließlich normale Releases. Test erhält ausschließlich Beta-Vorabversionen. Betas ersetzen nicht den aktuellen Stable-Download. Der Quellcode wird separat privat verwaltet.

Ab 0.2.4 befindet sich unter **Einstellungen → Updates** direkt unter „DSHub“ alles zur Versionsanzeige, Updateprüfung und Installation. „Anwendung“ enthält diese Funktionen nicht mehr. Der Bereich „Testinstanz erstellen“ wird ausschließlich in der Testversion angezeigt.

Bei aktivierter Automatik prüft der Manager **bei jedem Programmstart** und zusätzlich einmal täglich während der Laufzeit. Das gilt auch beim Start nur mit Sidebar oder minimiert. Eine hervorgehobene **1 rechts unten am Einstellungen-Zahnrad** zeigt ein angebotenes Update an. Ab 0.2.6 erscheint dieselbe blaue „1“ auch rechts im Updates-Tab. Beide Anzeigen erscheinen und verschwinden gemeinsam. Ein Klick auf das markierte Zahnrad öffnet direkt den Updates-Tab. Die manuelle Prüfung ist dort jederzeit möglich.

Ab 0.2.5 erscheint die Bestätigung vor der Installation im dunklen App-Dialog mit abgerundeten Ecken und passenden Schaltflächen. **Installieren und neu starten** bestätigt den Wechsel; Abbrechen und Escape installieren nichts.

**Update herunterladen** lädt und prüft das Paket; **Installieren und neu starten** führt nach Bestätigung den Austausch aus. Dabei bleibt eine Sicherung der bisherigen EXE erhalten.

Für jede neue Version werden eine EXE, ein ZIP, SHA256-Prüfsummen und signierte Update-Metadaten veröffentlicht. Die App prüft vor der Installation die Signatur, den Kanal, die Version sowie Paket- und EXE-Prüfsummen. Änderungen am Quellcode allein lösen kein Update aus; dafür muss ein neuer vollständiger Release veröffentlicht sein.

Stable ab 0.2.2 und Test ab 0.2.3 können über die bereits eingerichtete Quelle aktualisiert werden. Ältere Versionen ohne Updatequelle einmal durch die passende aktuelle EXE ersetzen. Alte manuell konfigurierte Quellen und Schlüssel werden ab 0.2.3 ignoriert; die Benutzervorgaben zur automatischen Prüfung bleiben erhalten.
