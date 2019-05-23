# Latex Vorlage für wissenschaftliche Arbeiten

Quick Start für das LaTeX Dokument unter der Verwendung von Texmaker.


### Projekt kompilieren:

- "document.tex" im Texmaker öffnen
- Quick Build (Klick auf den Pfeil neben Quick Build) oder F1
 

Anmerkungen:

- Das Kompilieren muss in der "document.tex" Datei ausgeführt werden. Alternativ: "Options" > Define Current Document as "Master Document" (muss bei jedem Start von Texmaker ausgeführt werden)
- Damit Dateien in das Inhaltsverzeichnis aufgenommen werden, muss Quick Build (F1) zwei mal ausgeführt werden
- Nach dem Hinzufügen neuer Literatur: Quick Build (F1), BibTex (F11), Quick Build (F1)


### Texmaker konfigurieren:

1. Build Folder erstellen:  

	"Options" > "Configure Texmaker" > Das Feld "Use a build subdirectory for output files" aktivieren

2. Biber konfigurieren:

	"Options" > "Configure Texmaker" > In das Feld "Bib(la)tex" den bestehenden Eintrag durch "biber build/%" ersetzen



