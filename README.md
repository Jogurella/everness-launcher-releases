# Everness Game-Launcher

Windows-Launcher für die Forever-Everness-Community. Unter Windows heißt die Anwendung **Evereness Launcher**; im Programm bleibt das Everness-Branding erhalten.

Dieses Repository ist der öffentliche **Download- und Updatekanal**. Es enthält veröffentlichte Windows-Programme, signierte Update-Manifeste und Versionshinweise. Das Entwicklungsrepository bleibt getrennt und privat. Private Kontodaten werden hier nicht veröffentlicht.

## Verwenden

Die **Setup.exe** unter **Releases** herunterladen und starten. Der deutsche Assistent bietet einen Installationsordner, erstellt Verknüpfungen und registriert die Deinstallation in Windows. Die portable **Windows.exe** bleibt als Alternative verfügbar. Minecraft Java muss auf dem verwendeten Microsoft-Konto vorhanden sein. In der ersten Ausgabe übernimmt das unveränderte offizielle Prism die Microsoft-Anmeldung und den kontogebundenen Spielstart. Die eigene Everness-Anmeldung folgt nach der erforderlichen Freigabe mit einem späteren Launcher-Update.

Aktuell: [Version 0.9.3](https://github.com/Jogurella/everness-launcher-releases/releases/tag/v0.9.3).

## Neu in 0.9.3

- **Leise Musik präzise einstellen:** Der untere Lautstärkebereich ist deutlich ruhiger abgestimmt. Die maximale Lautstärke verstärkt das Original nicht zusätzlich.
- **Sanft ankommen:** Musik blendet beim Öffnen des Hauptfensters und nach dem Spielende vom stummen Anfang auf die gespeicherte Lautstärke ein. Bootlogo, minimierter Launcher und Updateinstallation bleiben stumm.
- **Musik automatisch wechseln:** Eine neue gespeicherte Option spielt nach dem Ende den nächsten verfügbaren Titel. Ohne diese Option bleibt die bisherige Wiederholung aktiv.
- **Dein zuletzt gespieltes Paket:** Die Startseite merkt sich das zuletzt tatsächlich gestartete Modpack. Das bloße Ansehen oder Auswählen einer anderen Karte ersetzt diesen Eintrag nicht.
- **Dein Minecraft-Skin:** Das Kontofenster zeigt den eigenen vollständigen Charakter; oben rechts erscheint der passende Kopf. Das funktioniert auch mit einem über Prism bestätigten Profil. Öffentliche Skinbilder werden zwischengespeichert und können manuell aktualisiert werden.
- **Kompakter Musikbereich:** Kleinerer Regler und Musikschalter, gezieltes Leuchten direkt am Symbol und ein bündig in die Seitenleiste passendes Lautstärkefenster.
- **Einheitliche Symbole:** Prüf-, Aktualisierungs- und Downloadaktionen verwenden die zum Launcher passenden leichten Symbole. Die Serverstatusanzeige richtet ihre Breite nach dem Inhalt aus.
- **Neu angeordnete News:** Das neueste Update steht groß im Mittelpunkt, darunter erscheinen zunächst nur zwei ältere Meldungen. Weitere Nachrichten öffnet ein eigener Button. Die vorhandenen Filter bleiben verfügbar. Der Bereich Einstellungen → Updates behält seine bisherige Anordnung.
- **Manuell in den Infobereich:** Ein eigener Button oben neben den Fensteraktionen blendet Everness in den Windows-Infobereich aus. Das Tray-Symbol öffnet den Launcher wieder. Manueller Modus und automatisches Ablegen beim Spielstart verwenden dasselbe Symbol.
- **Eigenes Updatebild:** Eine neue Waldsee-Landschaft begleitet diese Ausgabe.

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
