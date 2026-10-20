# FX5 Plugin Usage Statistics – Windows 1.6.2

## English

FX5 Plugin Usage Statistics shows which installed VST2/VST3 plugins are used in your selected Fender Studio Pro / Studio One songs. It also lists unused plugins and entries that could not be reliably identified.

### Requirements and start

Windows 10/11 with .NET Framework 4.8. No installer, Python or Node.js is required.

Extract the complete ZIP and start `FX5_Plugin_Usage_Statistics.exe`. Keep the `Data` folder next to the EXE. The application folder must be writable so that settings can be saved.

### Language

English is selected on the first start, regardless of the Windows language. Choose **English** or **Deutsch** using **Language** in the main window. Changes apply immediately and your selection is remembered. Windows' own dialogs may follow the Windows display language.

### Create a report

1. Choose your **Song folder**. Subfolders are included. **Ignore backup files** is enabled by default; turn it off if you want to include backups and autosaves.
2. Open **Plugin folders / Scan …**. Use **Detect DAW folders** to add detected DAW search folders and existing Windows VST3 default folders. Add or remove folders as needed; **Suggest default folders** offers additional standard locations.
3. Choose **Refresh scan**, wait for completion, then **Apply**. The dialog shows whether DAW metadata was used or only the filesystem scanner. After installing or removing plugins, let the DAW finish its own plugin scan if necessary, then refresh the scan here. Changing search folders requires a new scan.
4. Choose an **Output folder** outside your song collection. The suggested folder is `Reports`. **Start analysis** becomes available when the plugin inventory and folder selections are valid.
5. Choose **Start analysis**. Each run creates a new `Report_YYYYMMDD_HHMMSS` folder; a number is added if that name already exists. Existing results are preserved. Unreadable songs are logged while the remaining songs are processed.
6. Choose **Open report in browser** or **Open output folder**. You can also open `Uebersicht.html` directly or use `Open_Report.bat` inside the report folder.

### Read and keep reports

Use the report's search, filters and column headings to find and sort plugins. Open the details to see associated songs. Song counts, instance counts and autosave usage are shown separately. Uncertain matches remain marked as uncertain. Results apply to the selected songs and scanned plugin folders.

HTML, CSV and text reports use the application language selected when analysis starts. Changing the GUI language later does not change existing reports. Folder and file names stay the same in both languages.

Reports work offline. Copy the entire report folder to keep its companion exports and links available on another computer.

### Settings and sharing

Settings are saved in `UserData` next to the application. Saved search folders must be scanned again after restarting the application.

Song files, plugins and DAW configuration files are read only. No plugins are loaded or executed, and nothing is automatically uninstalled.

To share the application, use the original release ZIP rather than a folder containing your settings or reports.

---

## Deutsch

FX5 Plugin Usage Statistics zeigt, welche installierten VST2-/VST3-Plugins in den ausgewählten Fender-Studio-Pro-/Studio-One-Songs verwendet werden. Zusätzlich werden unbenutzte Plugins und nicht sicher identifizierbare Einträge aufgelistet.

### Voraussetzungen und Start

Windows 10/11 mit .NET Framework 4.8. Installer, Python oder Node.js werden nicht benötigt.

Das vollständige ZIP entpacken und `FX5_Plugin_Usage_Statistics.exe` starten. Der Ordner `Data` muss neben der EXE bleiben. Der Anwendungsordner muss beschreibbar sein, damit Einstellungen gespeichert werden können.

### Sprache

Beim ersten Start ist unabhängig von der Windows-Sprache Englisch ausgewählt. Im Hauptfenster unter **Language** zwischen **English** und **Deutsch** wechseln. Die Änderung gilt sofort und die Auswahl wird gespeichert. Windows-eigene Dialoge können der Windows-Anzeigesprache folgen.

### Bericht erstellen

1. Den **Song-Ordner** auswählen. Unterordner werden berücksichtigt. **Backup-Dateien ignorieren** ist standardmäßig aktiviert; zum Einbeziehen von Backups und Autosaves die Option ausschalten.
2. **Plugin-Verzeichnisse / Scan …** öffnen. **DAW-Pfade erkennen** ergänzt ermittelte DAW-Suchpfade und vorhandene Windows-VST3-Standardordner. Bei Bedarf Ordner hinzufügen oder entfernen; **Standardpfade vorschlagen** bietet weitere übliche Speicherorte an.
3. **Scan aktualisieren** wählen, den Abschluss abwarten und **Übernehmen** anklicken. Der Dialog zeigt, ob DAW-Metadaten verwendet wurden oder nur der Dateisystem-Scanner. Nach Plugin-Installationen oder -Deinstallationen gegebenenfalls den eigenen Scan der DAW abschließen lassen und anschließend hier erneut scannen. Änderungen der Suchpfade erfordern einen neuen Scan.
4. Einen **Ausgabeordner** außerhalb der Song-Sammlung auswählen. Vorgeschlagen wird `Reports`. **Auswertung starten** wird verfügbar, sobald die Plugin-Inventur und die Ordnerauswahl gültig sind.
5. **Auswertung starten** wählen. Jeder Lauf erstellt einen neuen Ordner `Report_YYYYMMDD_HHMMSS`; bei bereits vorhandenem Namen wird eine Nummer ergänzt. Bisherige Ergebnisse bleiben erhalten. Nicht lesbare Songs werden protokolliert, während die übrigen Songs weiterverarbeitet werden.
6. **Auswertung im Browser öffnen** oder **Ergebnisordner öffnen** wählen. Alternativ `Uebersicht.html` direkt öffnen oder `Open_Report.bat` im Ergebnisordner verwenden.

### Berichte lesen und aufbewahren

Suche, Filter und Spaltenüberschriften helfen beim Finden und Sortieren der Plugins. In den Details stehen die zugehörigen Songs. Song-Anzahl, Instanzanzahl und Autosave-Nutzung werden getrennt angezeigt. Unsichere Zuordnungen bleiben entsprechend gekennzeichnet. Die Ergebnisse beziehen sich auf die ausgewählten Songs und gescannten Plugin-Ordner.

HTML-, CSV- und Textberichte verwenden die beim Auswertungsstart gewählte Anwendungssprache. Ein späterer Sprachwechsel der GUI verändert vorhandene Berichte nicht. Ordner- und Dateinamen bleiben in beiden Sprachen gleich.

Die Berichte funktionieren offline. Den gesamten Ergebnisordner kopieren, damit ergänzende Exporte und Verknüpfungen auch auf einem anderen Rechner verfügbar bleiben.

### Einstellungen und Weitergabe

Einstellungen werden im Ordner `UserData` neben der Anwendung gespeichert. Gespeicherte Suchpfade müssen nach einem Neustart der Anwendung erneut gescannt werden.

Songdateien, Plugins und DAW-Konfigurationsdateien werden ausschließlich gelesen. Es werden keine Plugins geladen oder ausgeführt und keine Plugins automatisch deinstalliert.

Zur Weitergabe der Anwendung das ursprüngliche Release-ZIP verwenden, nicht einen Ordner mit eigenen Einstellungen oder Berichten.
