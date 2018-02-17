# Latex-Template
Dieses Template soll die Erstellung von Abschlussarbeiten, Projektdokumentationen oder anderen Schriftstücken erleichtern.
Die am Häufigsten benötigten Elemente finden hier beispielhaft Verwendung. Hierzu gehören Listen, Tabellen, Bilder, Zitierungen, Gleichungen, Referenzierungen sowie das Einbinden von Grafiken, Dateien und Dokumenten.

1.	Zur Generierung einer PDF-Ausgabe bieten sich folgende Programme an:
	1.1	Texmaker (aktuellste Version) zum Editieren der Quelltexte
	1.2	Miktex 2.9 als Paketmanager zur Verwaltung für im Quelltext verwendete Pakete und Erweiterungen
2.	Nach der Installation von TexMaker lassen sich die in diesem Repository bereitgestellten .tex-Dateien darin öffnen.
3.	Um das Generieren einer Ausgabe von einer beliebigen Stelle im Quelltext aus zu ermöglichen, muss die Datei '00_settings.tex' im Menü "zur Masterdatei" erklärt werden. Dieser Schritt muss nach jedem Öffnen des TexMakers wiederholt werden.
4.	Im nächsten Schritt sollte eine Einstellung für die Generierung des Literaturverzeichnisses mit 'biber' vorgenommen werden:
	Optionen > Texmaker konfigurieren > Zeile "Befehle" wählen > Bib(la)tex = "C:/Program Files/MiKTeX 2.9/miktex/bin/x64/biber.exe"
5.  Fehlende Packages - sofern im Quellcode verwendet - werden von MikTex automatisch (nach (Bestätigung) nachinstalliert.
	