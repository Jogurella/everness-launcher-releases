# Everness Game-Launcher

Windows-Launcher für die Forever-Everness-Community.

Dieses Repository ist der öffentliche **Download- und Updatekanal**. Es enthält veröffentlichte Windows-Programme, signierte Update-Manifeste und Versionshinweise. Das Entwicklungsrepository bleibt getrennt und privat. Private Kontodaten werden hier nicht veröffentlicht.

## Verwenden

Die aktuelle Windows-EXE unter **Releases** herunterladen und starten. Minecraft Java muss auf dem verwendeten Microsoft-Konto vorhanden sein. In der ersten Ausgabe übernimmt das unveränderte offizielle Prism die Microsoft-Anmeldung und den kontogebundenen Spielstart. Die eigene Everness-Anmeldung folgt nach der erforderlichen Freigabe mit einem späteren Launcher-Update.

## Enthaltene Funktionen

- Getrennte OpenGL- und Vulkan-Instanzen mit eigenen Fensterlandschaften.
- Pack-Abgleich über die öffentlichen Everness-packwiz-Repositories, Prüfsummen und gesicherte Dateiwechsel.
- Import von Modrinth-.mrpack, packwiz-Quellen und unterstützten Java-Modpack-ZIPs (Fabric und Vanilla).
- Instanzeinstellungen, Welten-Backups und Serverstatus.
- Einstellbare Stimmungen und Hintergrundmusik aus lokal vorhandenen Minecraft-Assets.
- Signierte Programmupdates; Packs und Launcher werden unabhängig aktualisiert.

Eigene Spielstände und Einstellungen liegen unter `%LOCALAPPDATA%\EvernessGameLauncher` und bleiben bei Programmupdates erhalten.

## Programmupdates

Jede unterstützte Veröffentlichung enthält eine Windows-EXE und `everness-update.json`. Der Launcher kontrolliert die Ed25519-Signatur mit seinem hinterlegten öffentlichen Schlüssel, die Versionsnummer sowie Größe und SHA-256 der Programmdatei. Beim Installieren wird die vorige EXE gesichert. Private Signierschlüssel gehören nicht in dieses Repository.

## Unabhängiges Community-Projekt

Everness ist kein offizielles Minecraft-Produkt und wird nicht von Mojang oder Microsoft unterstützt oder mit ihnen verbunden. Minecraft-Spielprogramme und Musikaufnahmen werden nicht in der Launcher-EXE verteilt. Downloads und enthaltene Komponenten unterliegen den jeweiligen Nutzungsrechten und Lizenzen. Prism wird als unveränderte offizielle Anwendung mit seinen Lizenzdateien bezogen.
