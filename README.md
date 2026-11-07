# Everness Game-Launcher

Windows-Launcher für die Forever-Everness-Community. Unter Windows heißt die Anwendung **Evereness Launcher**; im Programm bleibt das Everness-Branding erhalten.

Dieses Repository ist der öffentliche **Download- und Updatekanal**. Es enthält veröffentlichte Windows-Programme, signierte Update-Manifeste und Versionshinweise. Das Entwicklungsrepository bleibt getrennt und privat. Private Kontodaten werden hier nicht veröffentlicht.

## Verwenden

Die **Setup.exe** unter **Releases** herunterladen und starten. Der deutsche Assistent bietet einen Installationsordner, erstellt Verknüpfungen und registriert die Deinstallation in Windows. Die portable **Windows.exe** bleibt als Alternative verfügbar. Minecraft Java muss auf dem verwendeten Microsoft-Konto vorhanden sein. In der ersten Ausgabe übernimmt das unveränderte offizielle Prism die Microsoft-Anmeldung und den kontogebundenen Spielstart. Die eigene Everness-Anmeldung folgt nach der erforderlichen Freigabe mit einem späteren Launcher-Update.

Aktuell: [Version 0.9.10](https://github.com/Jogurella/everness-launcher-releases/releases/tag/v0.9.10).

## Neu in 0.9.10

- **Eine Bildanzeige für alle Newsbereiche:** Minecraft News, Everness News und Launcher News verwenden dieselbe Darstellung. Vorschaubilder, Archivbilder und geöffnete Beiträge behalten die tatsächlichen Bildproportionen; zusätzliche dunkle Füllränder und Bildbeschnitt entfallen.
- **Bilder auch in Minecraft-Beiträgen:** Das Bild einer Minecraft-Meldung erscheint jetzt ebenfalls groß im geöffneten Beitrag. Der Link zum vollständigen offiziellen Artikel bleibt verfügbar.
- **Everness-Ersatzbilder vollständig anzeigen:** Auch ein mit dem Launcher geliefertes Packbild, etwa bei OpenGL ohne eigenes Repo-Updatebild, wird im Beitrag angezeigt. Repo-Bildunterschriften und alternative Bildbeschreibungen bleiben erhalten.
- **Passend zum Fenster:** Bild- und Rahmenmaße stimmen in kleinen Fenstern, Full HD und 4K überein. Große Beitragsbilder werden ohne Verzerrung auf die verfügbare Fläche begrenzt. Wenn kein Bild vorhanden ist, erscheint im Beitrag kein leerer Bildrahmen.
- **Eigenes Updatebild im gemeinsamen Everness-Stil:** Drei Bildtafeln auf einem Dorfplatz stehen für die einheitliche Darstellung in allen drei Newsbereichen; die wichtigsten Neuerungen sind direkt im Bild erklärt.

## Neu in 0.9.9

- **Newsbilder ohne künstliche Seitenränder:** Die Bildfläche übernimmt automatisch die tatsächlichen Proportionen des geladenen Bildes. Die feste Hintergrundfläche entfällt. Das komplette Bild bleibt erhalten; Texte und Motive werden weder beschnitten noch verzerrt.
- **Passende News-Karten:** Bei ausreichend Platz stehen Bild und Erklärung nebeneinander. In schmaleren Inhaltsbereichen wechseln sie untereinander. Auch Vollbild und Ultrawide erzeugen keine dunklen Füllstreifen neben dem Bild.
- **Archiv und geöffnete Beiträge angepasst:** Kleine Vorschaubilder und große Artikelbilder behalten ebenfalls ihr ursprüngliches Seitenverhältnis. Große Artikelbilder werden auf die verfügbare Fensterfläche begrenzt, ohne eine zusätzliche dunkle Bildmatte zu erzeugen.
- **Eigenes Updatebild im Everness-Stil:** Eine Galerie mit passgenauen Landschafts- und Hochkantbildern zeigt die neue Bildanpassung. Die wichtigsten Neuerungen stehen direkt im Bild.

## Neu in 0.9.8

- **Bis zu vier Pack-Dateien gleichzeitig:** Der Pack-Abgleich lädt neue Dateien parallel. Identische Inhalte werden auch bei mehreren Zielpfaden nur einmal übertragen. Alle Prüfsummen bleiben verpflichtend; der gesicherte Austausch im Spielordner beginnt erst nach vollständig erfolgreichen Downloads.
- **Sauberer Abbruch und Wiederholung:** Bei einem fehlgeschlagenen Download werden parallele Übertragungen abgebrochen und beendet, bevor der Auftrag fehlschlägt oder erneut gestartet werden kann. Ein fehlerhafter Download erzeugt keine teilweise aktualisierte Spielinstallation.
- **Weniger doppelte Prüfungen:** Installation und Spielvorbereitung verwenden einen gemeinsamen, frisch geprüften Pack-Stand für Minecraft/Fabric und Modpack. Der gleiche Ablauf lädt die Repository-Metadaten nicht erneut. Eine eigenständig gestartete Quellenprüfung bleibt aktuell; lokale Dateien und Prüfsummen werden weiterhin kontrolliert.
- **Effizientere große Downloads:** Kleine Netzwerkblöcke werden zu 256-KiB-Schreibvorgängen zusammengefasst. Fortschrittsmeldungen kommen gebündelt statt für jedes kleine Datenpaket; der geprüfte Endstand wird immer gemeldet. Das verringert Schreib- und Anzeigeaufwand auch beim Launcher-Update. Die verfügbare Internetbandbreite oder einen langsamen CDN-Knoten kann der Launcher dadurch nicht garantieren.
- **News zur passenden Pack-Version:** Everness News bevorzugt im CHANGELOG.md den Abschnitt, dessen Versionsnummer genau zu pack.toml passt. Frühere Änderungen und unveröffentlichte Planungen erscheinen dadurch nicht im aktuellen Beitrag. Ältere frei geschriebene Changelogs bleiben unterstützt. Ein eigener Pack-Newsbeitrag entsteht weiter automatisch aus dem veröffentlichten Repository, auch bevor das Pack aktualisiert wurde.
- **Bildvorschau vollständig:** Launcher-Updatebilder werden in den News vollständig angezeigt und erscheinen zusätzlich groß im geöffneten Beitrag. Die kurzen Erklärungen im Bild werden nicht abgeschnitten.
- **Neuer gemeinsamer Bildstil:** Das Titelbild übernimmt die visuelle Sprache der aktuellen Everness-Modpack-Updates mit heller Blockschrift, dunklen Informationsflächen und grünen/türkisen Akzenten. Motiv und Aufbau bleiben eigenständig. Die wichtigsten neuen Funktionen stehen als schnelle Vorschau direkt im Bild.

## Neu in 0.9.6

- **Persönliche Einstellungen schützen:** Jedes Modpack besitzt unter „Pack verwalten → Einstellungen“ einen dauerhaft gespeicherten Schalter. Er ist standardmäßig eingeschaltet und bewahrt vorhandene Hotkeys, Modoptionen und Shader-Einstellungen bei Pack-Updates. Fehlende Vorgaben werden ergänzt. Wer ausdrücklich neue Pack-Vorgaben übernehmen möchte, kann den Schutz für diese Instanz ausschalten.
- **Modpack-Updates repariert:** Ein lokal angepasstes Shader- oder Ressourcenpaket blockiert das Update nicht mehr, solange sich die zugehörige Quelldatei nicht geändert hat. Die lokale Datei bleibt erhalten und wird mit ihrer tatsächlichen Prüfsumme erfasst. Bei echten beidseitigen Änderungen zeigt „Dateikonflikte klären“ die betroffenen Dateien; erst eine ausdrückliche Bestätigung erlaubt den Austausch mit Sicherung. Eine erneute Änderung nach der Bestätigung erfordert eine neue Prüfung.
- **Modsuche korrigiert:** Suchbegriffe filtern die Modliste unmittelbar nach Modname oder Dateiname. Eingabe und Fokus bleiben erhalten.
- **Vollständige Umrandungen:** Fokusrahmen von Eingaben, Auswahlfeldern und Buttons liegen innerhalb der Bedienelemente und werden an Scrollbereichen nicht abgeschnitten. Suchleiste, Pack-Reiter und Einstellungsnavigation wurden angepasst.
- **Dialoge per Außenklick schließen:** Ein Klick auf den abgedunkelten Bereich schließt das Vordergrundfenster. Ziehen aus einem Eingabefeld nach außen schließt es nicht versehentlich.
- **Blattpartikel in allen Stimmungen:** Kleine Lichtpunkte und eine sanfte Windspur umspielen das Everness-Blatt in der jeweiligen Akzentfarbe. Bei deaktivierten Animationen, ausgeschalteten Effekten oder reduzierter Systembewegung verschwinden sie.
- **Eigenes Updatebild im Everness-Stil:** Ein geschütztes Reisetagebuch und leuchtende Blätter stehen für erhaltene persönliche Einstellungen und ruhige Animationen.

## Neu in 0.9.5

- **Windows-Dateisperre beim Prüfen behoben:** Schreibzugriffe auf dieselbe Metadaten-Datei werden geordnet ausgeführt. Kurzzeitige Windows-Sperren beim Umbenennen werden mit begrenzten Wiederholungen behandelt. Die vorherige Datei bleibt bis zum erfolgreichen Austausch erhalten; fehlgeschlagene Schreibvorgänge räumen ihre eigene temporäre Datei auf.
- **Aktuelle Pack-Version trotz GitHub-API-Limit:** Bei erschöpfter öffentlicher API-Quote ermittelt Everness den aktuellen Commit über den öffentlichen Repository-Feed. Alle Packdateien kommen anschließend aus genau diesem unveränderlichen Commit. Veraltete und neue Dateien aus dem Branch-Cache werden nicht mehr gemischt; sämtliche Prüfsummen bleiben verpflichtend.
- **News und manuelle Prüfungen abgestimmt:** Quellenprüfungen desselben Profils laufen nacheinander. Everness News prüft die aktuelle Pack-Quelle auch dann, wenn bereits alte Metadaten gespeichert sind. Fehlgeschlagene Prüfungen werden mit einer sichtbaren Meldung und dem gespeicherten Stand angezeigt.
- **Pack aktualisieren:** Ein erkannter neuer Pack-Stand erhält direkt in der Packkarte einen Aktualisieren-Button. Auch geänderte Inhalte oder Einstellungs-Vorlagen ohne geänderte Versionsnummer werden berücksichtigt. Die Installation bereitet bei Bedarf den neuen Fabric-Loader vor.
- **Eigenes Bild für Pack-News:** Pack-Beiträge übernehmen ein im geprüften Repository hinterlegtes Updatebild. Die News-Karte zeigt es vollständig; im geöffneten Beitrag erscheinen das große Bild und seine Bildunterschrift. Bilder bleiben im lokalen Cache verfügbar. Optional kann das Pack sein Bild über `options.everness.news-image` angeben; ansonsten wird ein passendes lokales README-Bild verwendet.
- **Vulkan 2026.11.07.3 erkannt:** Der Live-Abgleich erkennt den Wechsel von .2 auf .3, VIRIS und Voxy als neue Dateien, die Entfernung der verwalteten Distant-Horizons-JAR und Fabric 0.20.1. Das vorhandene Vergleichsbild aus dem Vulkan-Repo erscheint mit seinem Hinweis auf eine schematische Darstellung. Die News enthalten keine veraltete VulkanMod-Beschreibung mehr.
- **Updatebild im festen Everness-Stil:** Eine neue Lieferung am Walddepot steht für das zuverlässige Erkennen und Übernehmen neuer Versionen.

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
