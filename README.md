# Latex-Template
Dieses Template soll die Erstellung von Dokumenten wie Abschlusarbeiten, Projektdokumentationen oder Schrifstücken zu weiteren Zwecke erleichtern.
Es wurde versucht, in diesem Dokument die am Häufigsten benötigten Elemente beispielhaft zu verwenden.
Dazu gehören Listen, Tabellen, Bilder, wörtliche und nicht-wörtliche Zitate, Zitierweisen von Zeitschriftenartikeln, Büchern, Abschlussarbeiten und Webseiten, Gleichungen und Referenzierungen von Kapiteln und Grafiken.

Folgende Beschreibung zeigt, wie man dieses Template mit dem Tool TexMaker öffnet. Die Handhabung der Elemente wird direkt in der Vorlage erläutert.

1.	Zur Erstellung der Latex-Vorlage wurden folgende Programme verwendet:
	1.1	Texmaker 5.0.2
	1.2	Miktex 2.9
2.	Nach der Installation von TexMaker lassen sich die .tex-Dateien mit Drag-and-Drop in den Editor laden.
3.	Nun wählt man die Datei 00_settings.tex aus und wählt im Menü den Punkt "Aktuelle Datei zur 'Masterdatei' erklären" aus.
	Dieser Vorgang muss jedes mal nach dem Öffnen von TexMaker wiederholt werden und dient dazu, das Dokument von beliebiger Stelle aus zu bauen.
4.	Im nächsten Schritt muss man den Compiler anpassen:
	Optionen > Texmaker konfigurieren > Zeile "Befehle" wählen > Bib(la)tex = "C:/Program Files/MiKTeX 2.9/miktex/bin/x64/biber.exe"
5. Fehlende Packages - sofern im Quellcode verwendet - werden von MikTex automatisch (nach (Bestätigung) nachinstalliert.
	