# Everness Game-Launcher

Windows-Launcher für die Forever-Everness-Community. Unter Windows heißt die Anwendung **Evereness Launcher**; im Programm bleibt das Everness-Branding erhalten.

Dieses Repository ist der öffentliche **Download- und Updatekanal**. Es enthält veröffentlichte Windows-Programme, signierte Update-Manifeste und Versionshinweise. Das Entwicklungsrepository bleibt getrennt und privat. Private Kontodaten werden hier nicht veröffentlicht.

## Verwenden

Die **Setup.exe** unter **Releases** herunterladen und starten. Der deutsche Assistent bietet einen Installationsordner, erstellt Verknüpfungen und registriert die Deinstallation in Windows. Die portable **Windows.exe** bleibt als Alternative verfügbar. Minecraft Java muss auf dem verwendeten Microsoft-Konto vorhanden sein. In der ersten Ausgabe übernimmt das unveränderte offizielle Prism die Microsoft-Anmeldung und den kontogebundenen Spielstart. Die eigene Everness-Anmeldung folgt nach der erforderlichen Freigabe mit einem späteren Launcher-Update.

Aktuell: [Version 0.9.2](https://github.com/Jogurella/everness-launcher-releases/releases/tag/v0.9.2).

## Neu in 0.9.2

- Sichtbarer Downloadfortschritt direkt im Updatebereich, synchron zum Status oben rechts.
- Unabhängiges transparentes Updatefenster mit Everness-Logo, Ladekreis und Partikeln; ohne Hintergrundfläche, Ladebalken oder Musik.
- Bestätigte Übergabe, Installation, Versionsprüfung und automatischer Neustart. Alte Programm- und Update-Dateien werden erst nach bestätigtem Start aufgeräumt.
- Korrigierte Desktop- und Startmenü-Verknüpfungen; vorhandene reguläre Installationen werden auch beim Update aus der portablen Ausgabe berücksichtigt.
- Korrekte Umlaute und sichtbare Fehler mit Wiederherstellung statt eines kommentarlosen Abbruchs.
- Musik startet erst nach dem Bootlogo im sichtbaren Hauptfenster und läuft dort auch ohne Fokus weiter. Beim Minimieren und Aktualisieren pausiert sie.
- Beim echten Spielstart verschwindet Everness in den Taskleisten-Infobereich und öffnet sich nach Spielende automatisch wieder.

## Enthaltene Funktionen

- Transparentes Startlogo vor dem Launcherfenster: Aurora Flow als Standard, vier dauerhaft auswählbare Designs unter Einstellungen → Übersicht.
- Startanimation mit echtem Fortschritt und separater Vorschau; die Bibliothek erscheint erst nach vollständigem Laden.
- Quellenprüfungen aktualisieren nur ihre Statusfelder; Hintergründe und Eingaben bleiben unverändert.
- Verbesserter automatischer Neustart nach Updates und Korrektur alter Everness-Verknüpfungen auf die installierte Ausgabe.

- Getrennte OpenGL- und Vulkan-Instanzen mit eigenen Fensterlandschaften.
- Pack-Abgleich über die öffentlichen Everness-packwiz-Repositories, Prüfsummen und gesicherte Dateiwechsel.
- Import von Modrinth-.mrpack, packwiz-Quellen und unterstützten Java-Modpack-ZIPs (Fabric und Vanilla).
- Pack-Fenster mit Mod-Icons und Instanzeinstellungen, Welten-Backups und Live-Spielern.
- Kompakte Einstellungen, Stimmungen und zehn Hintergrundmusikstücke mit Motiven aus lokal vorhandenen Minecraft-Assets.
- Animiertes Download-Popup und News direkt aus den Pack-Updates.
- Signierte Programmupdates für Installer und portable Ausgabe, auf Wunsch automatisch nach Ende laufender Spiele/Aufträge.
- Alte Update-Dateien werden nach erfolgreichem Neustart aufgeräumt.
- Animierter Musik-Schalter mit kompaktem, bündig in die Seitenleiste passendem Lautstärke-Popup, zuverlässiger Wiederholung und The End von C418.
- Ansichten ohne sichtbaren Neuaufbau, ausgewogene Vollbildflächen und animiertes saisonales Wetter.
- Aufräumbare Downloads, Spielvorbereitung in der Karte und optional separates Logfenster.
- Laufende Spiele bleiben nach Schließen des Launchers aktiv und werden beim Wiederöffnen erkannt.
- Packs und Launcher werden unabhängig aktualisiert.

Eigene Spielstände und Einstellungen liegen unter `%LOCALAPPDATA%\EvernessGameLauncher` und bleiben bei Programmupdates erhalten.

## Programmupdates

Jede unterstützte Veröffentlichung enthält ein Setup mit `everness-installer-update.json` sowie eine portable EXE mit `everness-update.json`. Der Launcher kontrolliert die Ed25519-Signatur mit seinem hinterlegten öffentlichen Schlüssel, die Versionsnummer sowie Größe und SHA-256 der Programmdatei. Portable Updates sichern die vorige EXE bis zum erfolgreichen Neustart; installierte Ausgaben werden mit dem verifizierten Setup aktualisiert. Die Deinstallation behält persönliche Daten. Private Signierschlüssel gehören nicht in dieses Repository.

## Unabhängiges Community-Projekt

Everness ist kein offizielles Minecraft-Produkt und wird nicht von Mojang oder Microsoft unterstützt oder mit ihnen verbunden. Minecraft-Spielprogramme und Musikaufnahmen werden nicht in der Launcher-EXE verteilt. Downloads und enthaltene Komponenten unterliegen den jeweiligen Nutzungsrechten und Lizenzen. Prism wird als unveränderte offizielle Anwendung mit seinen Lizenzdateien bezogen.
