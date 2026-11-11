# Chrome Profile Manager – Downloads

Chrome Profile Manager für Windows x64 mit .NET Framework 4.8.

**[Stable – ChromeProfileManager.exe herunterladen](https://github.com/mcdegi/chrome-profile-manager-releases/releases/latest/download/ChromeProfileManager.exe)**

[Testversion 0.2.24-beta.1 – ChromeProfileManager.exe](https://github.com/mcdegi/chrome-profile-manager-releases/releases/download/v0.2.24-beta.1/ChromeProfileManager.exe)

[Alle Releases, Änderungsbeschreibungen, ZIP-Dateien und Prüfsummen](https://github.com/mcdegi/chrome-profile-manager-releases/releases)

## Neu in 0.2.24: Einzeilige Truppenwarnung

„Nicht genügend Truppen im Dorf!“ steht mit den drei Mengenangaben in einer gelben Zeile. Nur „noch erforderlich:“ und seine Zahlen sind fett.

## Neu in 0.2.23: Workbench-Import

„WB Plan hochladen“ importiert Workbench-Befehle in einen ausgewählten DS-Hub-Plan. Der Dialog bietet Katapultziel, Train, Bot-Auswahl, Nachtbonus und Raubzug-Reservierung.

## Neu in 0.2.22: Fehlbestandswarnung mit Truppenicons

Die gelbe Warnung steht über dem Trennstrich. „benötigt:“, „verfügbar:“ und
„noch erforderlich:“ zeigen die betroffenen Einheiten mit Icons und Mengen.
Die letzte Bestandszeile heißt bei mehreren Angriffen „Verfügbare Truppen in diesem Train“ und passt auf eine Zeile.

## Seit 0.2.21: Update-Symbol in der Profilnavigation

Links neben „Minimieren“ öffnet ein Update-Symbol die Prüfung und Installation
direkt in der Profilnavigation. Eine blaue „1“ zeigt ein verfügbares Update.
Die Update-Seite in den Einstellungen bleibt ebenfalls erreichbar.

## Seit 0.2.20: Truppen- und Rückkehr-Tooltips

Die Angriffsanzahl steht neben der Truppengruppe. Auch bei einem einzelnen AG
zeigt der Tooltip die vorgesehenen Truppen und den Trennstrich bis zum Rahmen.
Die Ergebniszeile unterscheidet Angriff und Unterstützung. Im Rückkehr-Tooltip
stehen Bezeichnung und gerundeter Zeitstempel nebeneinander, ohne Zusatzhinweis
bei gültiger Rückkehrzeit.

## Seit 0.2.19: Kürzere Rekrutierungszeile

Im Befehls-Tooltip entfällt „(geschätzt)“ aus der Zeile „Rekrutierung bis zur
Abschickzeit“. Die Mengenberechnung bleibt unverändert.

## Seit 0.2.18: Truppenbestand als Rechnung

Die Angriffsanzahl steht unter „Für diesen Train vorgesehen“ in einer eigenen
Zeile. Plus und Minus kennzeichnen Rückläufer, Rekrutierung und Vorplanung.
Der Summenstrich vor den Resttruppen endet am breitesten sichtbaren Bestand.

## Seit 0.2.17: Zweispaltige Truppen-Tooltips

Die dunkle Truppenaufstellung zeigt Bezeichnungen links und Truppen rechts.
Alle Truppengruppen erhalten dieselben abgerundeten Hintergründe wie in der
Befehlstabelle. Die Rückläufer-Zeile entfällt vollständig, wenn bis zur
Abschickzeit alle bekannten Rückkehrmengen null sind. Unbekannte Mengen bleiben
sichtbar. Lange Einheitenlisten können innerhalb ihrer Gruppe umbrechen.

## Seit 0.2.16: Truppenbestand zur Abschickzeit

Die Befehlsprüfung berücksichtigt eigenen Heimatbestand, rechtzeitige eigene
Rückläufer aus allen Wellen und fertige Rekrutierung, abzüglich früherer offener
Befehle aller Pläne. Bereits enthaltene Mengen und identische Rückkehrberichte
mehrerer Bots werden nicht doppelt addiert. Teilproduktion ist als Schätzung
markiert; fehlende oder widersprüchliche Daten bleiben unbekannt.

## Seit 0.2.13: Planer-Stepper und gelbe Ankunftsabweichung

Der Aktionsplaner zeigt Übersicht, Herkunft, Ziele, Zeiten und Berechnen als
horizontalen Stepper mit nummerierten Kreisen und Verbindungslinien. Der aktuelle
Schritt ist gefüllt und hervorgehoben. Alle Schritte bleiben direkt anwählbar;
Zurück/Weiter sowie Links/Rechts und Pos1/Ende funktionieren weiterhin. Die Anzeige
bleibt beim Scrollen im Formular sichtbar und in schmalen Ansichten horizontal
erreichbar. Die Markierung zeigt die Position, nicht die Gültigkeit der Eingaben.

Der Abweichungszusatz unter „Echte Ankunft“ ist jetzt gelb statt grün. Zeitstempel,
Berechnung sowie grüne Versand- und Botstatussymbole bleiben unverändert.
Keine automatischen Angriffe durch die Anzeige oder Navigation.

## Seit 0.2.12: Herkunftsdörfer einzeln tauschen

Der Tausch zweier geplanter DSHub-Befehle speichert beide Änderungen nacheinander
einzeln. Erst nach bestätigendem Neuabruf der ersten Änderung wird die zweite
gesendet. Status, Befehlsdaten und Abschickzeiten werden erneut geprüft; zuletzt
müssen beide Änderungen bestätigt sein. So wird der fehlschlagende Batch-Pfad
umgangen. Das Ersetzen durch ein unverplantes Dorf im rechten Tab bleibt unverändert.

Der Ablauf ist nicht atomar: Bei unklarer Bestätigung zeigt der Dialog den
bestätigten Fortschritt und fordert zum manuellen Tabellen-Neuabruf auf. Keine
automatische Schreibwiederholung, kein Rücktausch und kein automatischer Versand.
Mit synthetischen API-/WPF-Fixtures geprüft; keine Schreibtests an echten Befehlen.

## Seit 0.2.11: Kopier-Icons in der Befehlstabelle

Hinter Start-/Zielkoordinaten sowie geplanter Abschick-/Ankunftszeit stehen kleine
Kopier-Icons ohne Hintergrund. Sie kopieren den vollständigen angezeigten Wert,
bei Zeiten mit lokalem Datum, Sekunden und „Uhr“. Fehlende Werte zeigen kein
Icon. Zeilenauswahl und Sortierung bleiben unverändert; Tabellen-Refresh und
Zeilen-Recycling aktualisieren auch den Kopierwert. Kurze Hinweise bestätigen
den Erfolg oder melden eine nicht verfügbare Zwischenablage. Keine API-Aufrufe
oder automatischen Schreibwiederholungen durch Kopieren.

## Seit 0.2.10: Statusabgleich nach unbestätigten Änderungen

Die Angriffspläne aktualisieren Status und echte Ankunft auch nach einem
fehlgeschlagenen oder unbestätigten Herkunftstausch, einer Änderung oder Löschung
weiter automatisch. Es handelt sich ausschließlich um lesende Abrufe: keine
Schreibwiederholung und kein aus dem Countdown abgeleiteter Versandstatus.
Weitere Änderungen bleiben bis zum erfolgreichen manuellen Tabellen-Neuabruf
gesperrt. Der Statusabgleich behebt selbst keinen HTTP-500-Speicherfehler;
ab 0.2.12 umgeht der Herkunftstausch dessen Batch-Pfad mit Einzeländerungen.

## Seit 0.2.9: Mindestmoral im Aktionsplaner

Unter **Aktionsplaner → Übersicht → Mindestmoral** lässt sich je Planungsgruppe
eine Grenze von 0 bis 100 % einstellen; 0 deaktiviert den Filter. Die konservative
Schätzung verwendet Spieler-Gesamtpunkte, den Moralmodus der Welt und beobachtete
Neustartzeiten. Unbekannte oder veraltete Daten bestehen einen aktiven Filter nicht.
AG-Angriffe und Unterstützungen sind ausgenommen; eine benötigte Off muss ihren
eigenen Filter erfüllen. Berechnung, Ergebnisbearbeitung und bestätigte Übernahme
prüfen dieselbe Bedingung. Keine Kampf-/Versandgarantie und kein automatischer Versand.

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
## Weltdaten und Spieler-Neustarts

Ab 0.2.8 werden die öffentlichen Weltdaten für **de258** stündlich auf einem
kostenlosen öffentlichen GitHub-Standard-Runner erfasst, auch bei ausgeschaltetem PC.
Stable und Test laden den signierten Stand beim Start und alle fünf Minuten.
Unter **Einstellungen → DSHub** stehen der Datenstand und **Daten aktualisieren**.
Offline bleibt der letzte gültige Stand erhalten.

- [Aktuelle Neustartliste als CSV](https://github.com/mcdegi/chrome-profile-manager-worlddata/releases/latest/download/player-starts.csv)
- [Datenablage und stündlicher Ablauf](https://github.com/mcdegi/chrome-profile-manager-worlddata)

CSV: `player_id,timestamp`, Unix-Sekunden UTC. Neue aktive Spieler werden beim
ersten Erfassen aufgenommen, Spieler mit 0 Punkten entfernt und bestätigte
Neustarts ersetzen die vorherige Zeit. Rohdaten werden 48 Stunden aufbewahrt;
die aktuelle Liste und ihr Vergleichszustand bleiben dauerhaft erhalten.
GitHub kann geplante Läufe verzögern oder auslassen. Der CDN-Zwischenspeicher kann neue Daten zusätzlich einige Minuten verzögert sichtbar machen.
