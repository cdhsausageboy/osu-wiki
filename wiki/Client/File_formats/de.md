# osu!-Dateiformate

## Liste der Dateiformate

| Dateiformat | MIME-Typ | Verwendung |
| :-- | :-- | :-- |
| [.osz](/wiki/osu!_File_Formats/Osz_(file_format)) | `x-osu-beatmap-archive` | osu!-Beatmap-Archiv |
| [.osk](/wiki/osu!_File_Formats/Osk_(file_format)) | `x-osu-skin-archive` | osu!-Skin-Archiv |
| [.osu](/wiki/osu!_File_Formats/Osu_(file_format)) | `x-osu-beatmap` | osu\![-Schwierigkeitsgrad](/wiki/Beatmap/Difficulty) |
| [.osb](/wiki/osu!_File_Formats/Osb_(file_format)) | `x-osu-storyboard` | osu\![-Storyboard](/wiki/Storyboard/Scripting) |
| [.osr](/wiki/osu!_File_Formats/Osr_(file_format)) | `x-osu-replay` | osu\![-Replay](/wiki/Gameplay/Replay) |

## .osz- und .osk-Dateien erstellen

`.osz`- und `.osk`-Dateien sind Archive, die Beatmaps bzw. Skins enthalten. Ihr Inhalt wird automatisch extrahiert von osu!, wenn sie geöffnet werden:

- `.osz`-Dateien werden in das Verzeichnis `Songs` extrahiert
- `.osk`-Dateien werden in das Verzeichnis `Skins` extrahiert

Wenn du weißt, wie du ein Skin- oder Beatmap-Archiv erstellst, welches von osu! erkannt wird, werden deine Werke für andere zugänglicher sein.

### Verwendung einer Archivierungssoftware

1. Installiere ein Dateiarchivierungsprogramm, das `.zip`-Dateien erzeugen kann, wie z. B. [7-Zip](https://www.7-zip.org/) oder [WinRAR](https://www.rarlab.com/).
2. Lege alle Dateien, die du archivieren möchtest, in einen separaten Ordner.
3. Klicke mit der rechten Maustaste auf den Ordner und wähle  `Zu einem Archiv hinzufügen...` (alternativ kannst du das auch im Archivierungsprogramm selbst machen).
4. Selektiere das Archivformat ZIP.
5. Ändere die Dateierweiterung `.zip` zu `.osz` im Dateinamen des Archivs (`.osk`, wenn du einen Skin archivierst).

Kreiere eine Kopie der Datei und öffne sie mit osu!, um das Archiv zu testen.

### Verwendung von osu!

Um ein Beatmap-Archiv zu produzieren:

- Öffne eine Beatmap mit dem [Editor](/wiki/Client/Beatmap_editor).
- Wähle `Datei` > `Paket exportieren ...` aus dem [oberen Menü](/wiki/Client/Beatmap_editor/Menu).
- Das Archiv `.osz` wird in den Ordner `Exports` innerhalb deines osu!-Ordners platziert.

Um ein Skin-Archiv zu erstellen:

- Versichere dich, dass dein Skin alles hat, was du exportieren möchtest. Du kannst das prüfen, indem du den Button `Skinordner öffnen` in den osu!-Einstellungen drückst.
- Klicke in den Einstellungen auf `Skin auswählen`.
- Wähle den Skin, den du exportieren möchtest, und klicke auf `Als .osk exportieren`.
- Das Archiv `.osk` wird im Ordner `Exports` innerhalb deines osu!-Installationsordners platziert.
