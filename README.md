# LaTeX template for academic theses or papers

Quick Start for the LaTeX template using Texmaker.


### Set up Texmaker:

1. Create "build" directory 

	"Options" > "Configure Texmaker" > Activate "Use a build subdirectory for output files" 
	
2. Configure Biber:

	"Options" > "Configure Texmaker" > Replace the value in "Bib(la)tex" by "biber build/%"


### Quick Start Guide using Texmaker

1. Open the "document.tex" in Texmaker

2. Compile the project by using the "Quick Bild" command (or the shortcut F1)


#### Notice:

- The Quick Build command (F1) has to be executed in "document.tex". Alternatively: "Options" > Define Current Document as "Master Document"
- The Quick Build command (F1) has to be executed twice in order to add sections to the table of contents
- After adding new literature to the bibliography.bib, you have to execute the Quick Build command (F1), the BibTex command (F11) and the Quick Build command (F1) again


--- 


# Latex Vorlage für wissenschaftliche Arbeiten

Quick Start für das LaTeX-Vorlage unter der Verwendung von Texmaker.


### Texmaker konfigurieren:

1. Build Folder erstellen:  

	"Options" > "Configure Texmaker" > Das Feld "Use a build subdirectory for output files" aktivieren

2. Biber konfigurieren:

	"Options" > "Configure Texmaker" > In das Feld "Bib(la)tex" den bestehenden Eintrag durch "biber build/%" ersetzen

	
### Projekt kompilieren:

1. "document.tex" im Texmaker öffnen

2. Quick Build (Klick auf den Pfeil neben Quick Build) oder F1
 

#### Anmerkungen:

- Das Quick Build Kommando muss in der "document.tex" Datei ausgeführt werden. Alternativ: "Options" > Define Current Document as "Master Document" 
- Damit Dateien in das Inhaltsverzeichnis aufgenommen werden, muss Quick Build (F1) zwei mal ausgeführt werden
- Nach dem Hinzufügen neuer Literatur: Quick Build (F1), BibTex (F11), Quick Build (F1)
