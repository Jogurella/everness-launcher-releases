# Everness Game-Launcher

Windows-Launcher für die Forever-Everness-Community. Unter Windows heißt die Anwendung **Evereness Launcher**; im Programm bleibt das Everness-Branding erhalten.

Dieses Repository ist der öffentliche **Download- und Updatekanal**. Es enthält veröffentlichte Windows-Programme, signierte Update-Manifeste und Versionshinweise. Das Entwicklungsrepository bleibt getrennt und privat. Private Kontodaten werden hier nicht veröffentlicht.

## Verwenden

Die **Setup.exe** unter **Releases** herunterladen und starten. Der deutsche Assistent bietet einen Installationsordner, erstellt Verknüpfungen und registriert die Deinstallation in Windows. Die portable **Windows.exe** bleibt als Alternative verfügbar. Minecraft Java muss auf dem verwendeten Microsoft-Konto vorhanden sein. In der ersten Ausgabe übernimmt das unveränderte offizielle Prism die Microsoft-Anmeldung und den kontogebundenen Spielstart. Die eigene Everness-Anmeldung folgt nach der erforderlichen Freigabe mit einem späteren Launcher-Update.

Aktuell: [Version 0.14.5](https://github.com/Jogurella/everness-launcher-releases/releases/tag/v0.14.5).

## Neu in 0.14.5

- **Modbilder im Editor:** Hinzugefügte Mods und Abhängigkeiten zeigen ihre Projektbilder auch in „In deinem Pack“ und nach erneutem Öffnen. Bereits gespeicherte Packs werden ebenfalls berücksichtigt.
- **Lokal zwischengespeichert:** Wiederherstellung nach Neustarts, getrennte Anbieter und eingebettete Bilder unterstützter lokaler Mods. Fehlende Bilder blockieren keine Bearbeitung.
- **Geprüft:** 271 Tests und echte Bildausgabe mit JEI und MezzConfig. Packs und Einstellungen bleiben erhalten; eigenes Updatebild und privater Quellcode.

## Neu in 0.14.4

- **Eigene Packs mit Modloader:** Fabric, Forge, NeoForge, Quilt, LiteLoader oder Vanilla beim Erstellen wählen; passende offizielle Loader-Versionen pro Minecraft-Version.
- **Passende Bibliothek:** Modsuche, Versionsauswahl und benötigte Abhängigkeiten auf Modrinth und der verbundenen CurseForge-Bibliothek berücksichtigen den tatsächlichen Loader. Fremde Loader und falsche Minecraft-Versionen werden vor dem Download abgewiesen.
- **Lokale Mods:** Erkannte Loader- und Minecraft-Vorgaben prüfen, einschließlich LiteLoader-Dateien. Unklare Metadaten erhalten eine verständliche Fehlermeldung.
- **Geprüft:** 262 Tests, eigenes Updatebild und privater Quellcode. Bestehende Packs und Anmeldung bleiben erhalten.

## Neu in 0.14.3

- **Modloader-Import und Spielstart:** Fabric, Forge, NeoForge, Quilt, LiteLoader und Vanilla in den vorhandenen Java-Modpack-Importformaten; Forge + LiteLoader als ältere Kombination.
- **Richtig vorbereitet:** Passende Java-Version und echte Prism-Komponenten; Installer, Bibliotheken und Startargumente der erweiterten Loader übernimmt Prism.
- **Loader-Wechsel erkannt:** Name und Version verhindern, dass eine unpassende Vorbereitung nach einem Wechsel oder Pack-Update weiterverwendet wird.
- **Klare Meldungen:** Unbekannte Startprofile und widersprüchliche Loader werden nicht stillschweigend in Vanilla umgewandelt. Reine CurseForge-ID-Manifeste benötigen weiterhin eine autorisierte Downloadauflösung.
- **Prism bleibt Standard:** Die eigene Microsoft-App-Freigabe bleibt unbestätigt. Bestehende Packs und persönliche Daten bleiben erhalten; privater Quellcode.

## Neu in 0.14.2

- **Stil und Hintergrund gehören zusammen:** Cherry Dawn, Midnight, Aurora, Ember, Lagoon und Golden Dunes ändern nun auch den Fensterhintergrund und das große Startseitenbild.
- **Überall gespeichert:** Die Auswahl bleibt beim Seitenwechsel und nach erneutem Öffnen erhalten; Modpack-Karten behalten ihre eigenen Motive.
- **Ruhiger Bildwechsel:** Das nächste Motiv wird vor dem Austausch decodiert. Verspätete Antworten überschreiben keine neuere Stilwahl; wiederholte Prüfungen laden den aktiven Hintergrund nicht erneut.
- **Geprüft:** 219 Tests, alle sechs Stile und eigener Everness-Updatebanner. Funktionen aus 0.14.1 bleiben enthalten.

## Neu in 0.14.1

- **Dateiauswahl beim Pack-Update:** vorhandene Dateien einzeln behalten oder durch neue Pack-Vorgaben ersetzen; entfallene Dateien gezielt entfernen. Ersetzte Dateien werden gesichert, persönliche Welten und Kontodaten bleiben geschützt.
- **Fortschritt bis zum Abschluss:** Ladebalken beziehungsweise Ladekreis direkt im Paket, im Startpanel und im Packfenster, einschließlich Dateiaustausch. Pausen und Fehler bleiben sichtbar.
- **Neues Systemicon:** transparentes grünes Pixelblatt mit goldenem Ring und Lichtfunken, für Installer, Programm und eigene Windows-Verknüpfungen.
- **Kompakte News-Vorschau:** 280 statt 360 Pixel breit und vor dem Inhalt sichtbar, mit vollständigem Bild.
- **Normales Versionsupdate:** 0.14.1 wird auch von 0.14.0 Revision 2 als neue Version erkannt. 216 Tests bestanden; eigenes Updatebild im Everness-Stil.

## Neu in 0.14.0

**Revision 2 im selben Update:** Ältere Meldungen in allen Newsbereichen sind jetzt feste 84-Pixel-Zeilen statt großer Karten. Das Windows-Icon wurde zum E-Monogramm mit Blatt neu gestaltet. Bestehende eigene Verknüpfungen werden auf eine dauerhafte ICO-Datei mit Inhaltskennung umgestellt, auch bei der portablen Ausgabe. Die Titelleiste zeigt `0.14.0 · R2`. Eine bereits installierte erste 0.14.0 lässt sich durch erneutes Ausführen des korrigierten Installers ersetzen.


- **Sechs Stimmungen:** Cherry Dawn als neuer Standard, Midnight bleibt; Aurora, Ember, Lagoon und Golden Dunes kommen hinzu. Evergreen wird auf Cherry Dawn umgestellt.
- **Mods per Drag & Drop:** Karten in die Packauswahl ziehen, mit Zielmarkierung und Anzieh-Animation. Kompatible Dateien und Abhängigkeiten verwenden den bestehenden geprüften Downloadweg.
- **Start abbrechen:** Button direkt am Paket, einschließlich eines abbrechbaren Drei-Sekunden-Countdowns vor dem Engine-Start.
- **Eigenständige Seiten:** Server-Panorama mit horizontaler Verbindungsleiste; kompaktere kleine Fenster und Sidebar ohne zusätzlichen Spruch.
- **Ruhige Bildkanten und Archive:** Deckende runde Rahmen und deutlich kleinere ältere Meldungen mit vollständig sichtbaren Vorschaubildern.
- **Schnellnews:** Rotierende Meldungen in der Titelleiste mit holografischer Bildvorschau bei Hover oder Tastaturfokus.
- **Neues Windows-Icon:** Transparente Blatt-Ring-Gestaltung und Aktualisierung bestehender eigener Desktop-, Startmenü- und Taskleisten-Verknüpfungen.
- **Geprüft:** 207 Tests, kleine Fenster bis 4K, ein echter Mod-Download per Ziehen in ein isoliertes Testpaket und Windows-Verknüpfungsprüfung.

## Neu in 0.13.0

- **API mit automatischem Ersatzweg:** Updates und Launcher-News verwenden zuerst die GitHub-API. Bei Fehlern wie HTTP 403, 429 oder 504 übernimmt ein signierter Dateiindex ohne zusätzlichen Login.
- **Weniger Anfragen:** Gemeinsamer Fünf-Minuten-Cache und zusammengeführte gleichzeitige Prüfungen. Nach API-Fehlern wird diese 15 Minuten ausgesetzt; der Dateiweg bleibt aktiv.
- **Zwei Ersatzquellen:** Statische Indexdatei im Release-Repository, mit dem Index der neuesten GitHub-Veröffentlichung als weiterer Alternative.
- **Everness-Quellen abgesichert:** OpenGL und Vulkan lösen ihren festen Commit bei einem API-Fehler über den öffentlichen Feed auf. Packwiz-Prüfsummen bleiben erhalten.
- **Bestehende Sicherheit:** Programm-Manifeste bleiben auf allen Wegen signiert, dazu SHA256 und Größenprüfung. Der Ersatzindex ist ebenfalls signiert. Quellcode weiterhin privat.
- **Automatische Umstellung:** Nach Installation dieses normalen GitHub-Updates ist keine weitere Einrichtung nötig. Eigenes Everness-Updatebild, verlustfrei komprimiert.

## Neu in 0.12.0

- **Launcher Overhaul:** Start, Forever Everness, Server, News, Einstellungen und die linke Navigation übernehmen die neue Gestaltung der Modpack-Bibliothek.
- **Direkter Einstieg:** Eigenes Startpanel mit echtem Paketstatus, Fortschritt in der Karte und schnellen Wegen zu Bibliothek, Backups und Paketverwaltung.
- **Forever Everness als Projekt:** Große Projektidentität, Community-Server und klar getrennte OpenGL- und Vulkan-Spezialpakete.
- **News übersichtlicher:** Drei große Quellenauswahlen, eigene Packfilter, eine hervorgehobene neueste Meldung und vollständige Bilder ohne Beschnitt.
- **Einstellungen neu geordnet:** Übersicht und sieben klare Kategorien mit kompakter Bedienung; Stimmung und Musikstatus aktualisieren ihre Vorschau direkt.
- **Prism-Download ohne API-Limit:** Das offizielle Portable-Paket 11.1.1 wird direkt geladen und anhand fest hinterlegter Größe und SHA256 geprüft. Der erste Engine-Download benötigt keine GitHub-Release-API mehr.
- **Geprüft bis 4K:** 189 Tests, kleine Fenster und große Vollbildflächen sowie ein echter frischer Prism-Download bei absichtlich blockierter API.

## Neu in 0.11.0

- **Modpack-Bibliothek neu gestaltet:** Klare Einstiegskarten für Erstellen und Importieren, eigene und importierte Sammlungen sowie kompakte Fenster bis 4K.
- **50 wählbare Kartenbilder:** Beim Erstellen und Importieren auswählen oder später an der Packkarte ändern. Die Auswahl bleibt gespeichert; alle Motive sind offline enthalten.
- **News nach Pack:** OpenGL und Vulkan besitzen jeweils ihre eigene große Updatevorschau und ihren Verlauf.
- **Echte Online-Skinköpfe:** Öffentlich freigegebene Minecraft-IDs liefern die Spieleravatare über Mojang, mit Cache und neutralem Ersatzsymbol.
- **Ruhige Bedienung:** Startfortschritt ohne überlappende Texte, passende Symbole für Speicher/Barrierefreiheit/Diagnose und ein sanfter Glasübergang unter der festen Modsuche.
- **Verlustfreie Bildkomprimierung:** Rund 47 MB beziehungsweise 20 % weniger Bildspeicher gegenüber denselben PNGs, keine doppelten PNG-Quellen im Paket sowie stärkere Programmkomprimierung. Die 50 zusätzlichen Motive können die Gesamtgröße gegenüber älteren Versionen dennoch erhöhen.

## Neu in 0.10.1

- **Downloadfehler abfangen:** Vorübergehende HTTP-Fehler wie GitHub 504 werden bei lesenden Anfragen bis zu dreimal mit wachsendem Abstand erneut versucht. Abbrechen bleibt unmittelbar möglich.
- **Offizieller Ausweichweg:** Scheitert der normale Release-Download weiter, kann Everness Manifest und Programmdatei über die offizielle GitHub-API laden. Keine fremden Download-Proxys und keine zusätzliche Anmeldung.
- **Unveränderte Verifizierung:** Ed25519-Signatur, Dateigröße und SHA-256 bleiben auf beiden Wegen verpflichtend. Beschädigte Dateien werden nicht installiert.
- **Klarer Fortschritt:** Wiederholungen und Ausweichweg werden angezeigt. Automatische Updates prüfen nach vorübergehendem HTTP-Ausfall nach fünf Minuten erneut; längere Server-Wartezeiten bleiben maßgeblich.

## Neu in 0.10.0

- **Eigene Modpacks erstellen:** Name, Minecraft-Version sowie Fabric oder Vanilla wählen. Snapshots sind optional. Jedes Pack hat eine eigene Instanz.
- **Neue Modpack-Bibliothek und Werkstatt:** Selbst erstellte und importierte Pakete werden getrennt und alphabetisch sortiert. Die überarbeitete Verwaltung bietet Mods, Ressourcenpakete, Shader, Einstellungen und Paketinfos.
- **Modrinth direkt im Launcher:** Inhalte suchen, passende Version auswählen und per Plus hinzufügen. Erforderliche Abhängigkeiten und Anbieter-Prüfsummen werden berücksichtigt. Lokale JAR- und ZIP-Dateien können ebenfalls ergänzt werden.
- **CurseForge verbinden:** Die offizielle Schnittstelle benötigt einen eigenen API-Schlüssel im Windows-Anmeldeinformationsspeicher. Downloads beachten die Freigabe des Autors; eingeschränkte Dateien lassen sich lokal hinzufügen.
- **Ruhige, einheitliche Bedienung:** Spalt über der Modliste geschlossen, Scrollleisten an die Launcherfarben angepasst, klare Zahnradsymbole und direkte Dateipfad-Buttons für installierte Inhalte.
- **Eigenes Updatebild:** Die neue Werkstatt und ihre wichtigsten Funktionen stehen direkt im Bild im gemeinsamen Everness-Stil.

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
- Import von Modrinth-.mrpack, packwiz-Quellen und unterstützten Java-Modpack-ZIPs mit Fabric, Forge, NeoForge, Quilt, LiteLoader oder Vanilla.
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

Eigene Spielstände und Einstellungen liegen unter `%USERPROFILE%\Games\Everness Launcher Data` und bleiben bei Programmupdates erhalten. Ältere Daten aus `%LOCALAPPDATA%\EvernessGameLauncher` werden bei Bedarf übernommen.

## Programmupdates

Jede unterstützte Veröffentlichung enthält ein Setup mit `everness-installer-update.json` sowie eine portable EXE mit `everness-update.json`. Der Launcher kontrolliert die Ed25519-Signatur mit seinem hinterlegten öffentlichen Schlüssel, die Versionsnummer sowie Größe und SHA-256 der Programmdatei. Portable Updates sichern die vorige EXE bis zum erfolgreichen Neustart; installierte Ausgaben werden mit dem verifizierten Setup aktualisiert. Die Deinstallation behält persönliche Daten. Private Signierschlüssel gehören nicht in dieses Repository.

## Unabhängiges Community-Projekt

Everness ist kein offizielles Minecraft-Produkt und wird nicht von Mojang oder Microsoft unterstützt oder mit ihnen verbunden. Minecraft-Spielprogramme und Musikaufnahmen werden nicht in der Launcher-EXE verteilt. Downloads und enthaltene Komponenten unterliegen den jeweiligen Nutzungsrechten und Lizenzen. Prism wird als unveränderte offizielle Anwendung mit seinen Lizenzdateien bezogen.

