# Everness Game-Launcher

Windows-Launcher für die Forever-Everness-Community. Unter Windows heißt die Anwendung **Evereness Launcher**; im Programm bleibt das Everness-Branding erhalten.

Dieses Repository ist der öffentliche **Download- und Updatekanal**. Es enthält veröffentlichte Windows-Programme, signierte Update-Manifeste und Versionshinweise. Das Entwicklungsrepository bleibt getrennt und privat. Private Kontodaten werden hier nicht veröffentlicht.

## Verwenden

Die **Setup.exe** unter **Releases** herunterladen und starten. Der deutsche Assistent bietet einen Installationsordner, erstellt Verknüpfungen und registriert die Deinstallation in Windows. Die portable **Windows.exe** bleibt als Alternative verfügbar. Minecraft Java muss auf dem verwendeten Microsoft-Konto vorhanden sein. In der ersten Ausgabe übernimmt das unveränderte offizielle Prism die Microsoft-Anmeldung und den kontogebundenen Spielstart. Die eigene Everness-Anmeldung folgt nach der erforderlichen Freigabe mit einem späteren Launcher-Update.

Aktuell: [Version 0.9.4](https://github.com/Jogurella/everness-launcher-releases/releases/tag/v0.9.4).

## Neu in 0.9.4

- **Importierte Modpacks löschen:** Auf der Packkarte und im Paketfenster gibt es jetzt einen Löschbutton. Nach einer eindeutigen Bestätigung entfernt Everness die Instanz inklusive Mods, Einstellungen, Welten, Screenshots und zugehörigen Welt- und Pack-Sicherungen. Auch die von Everness verwaltete Prism-Brücke wird entfernt. Die ursprüngliche Importdatei, andere Instanzen und gemeinsam genutzte Minecraft-Dateien bleiben erhalten.
- **Geschütztes Löschen:** Feste Everness-Pakete lassen sich nicht entfernen. Bei laufendem Minecraft, offenem Prism-Einrichtungsfenster oder aktiven, wartenden beziehungsweise pausierten Aufträgen wird die Löschung blockiert. Unsichere Pfade und fremde Prism-Instanzen werden geschützt. Die Auswahl wechselt nach dem Entfernen eines aktiven Packs auf ein vorhandenes Profil; gespeicherte Pack-Optionen und veraltete Aufträge werden bereinigt.
- **Importreste aufräumen:** Temporäre Archivordner werden nach einem erfolgreichen oder fehlgeschlagenen Import wieder entfernt.
- **Minecraft News:** Statt „Alle Neuigkeiten“ gibt es eine eigene Rubrik mit aktuellen offiziellen Meldungen von Minecraft.net, den zugehörigen Bildern und einem Button zum vollständigen Artikel. Meldungen und Bilder werden lokal zwischengespeichert und bleiben offline verfügbar. Die Quelle wird regelmäßig sowie über „Aktualisieren“ geprüft; der Wortlaut folgt der offiziellen Quelle.
- **Launcher News:** Dieser Reiter enthält ausschließlich Everness-Launcher-Veröffentlichungen und ihre Versionshinweise.
- **Everness News:** So heißt der bisherige Modpack-News-Reiter. Hier stehen die Neuigkeiten der Everness-Pakete. Bereits geladene ältere Pack-Versionen bleiben in der Nachrichtenhistorie erhalten.
- **Einheitliche Updatebilder:** Der feste Everness-Voxelstil mit Waldgrün, Lavendel und warmem Licht bleibt künftig erhalten. Jede Veröffentlichung bekommt ein neues Motiv, das wichtige Neuerungen sichtbar aufgreift. Die sortierten Pack-Truhen dieser Ausgabe stehen für die neue Verwaltung importierter Modpacks.

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
