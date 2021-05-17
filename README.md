Die Projektarbeit beschäftigt sich mit dem Thema Digitale Barrierefreiheit von Desktopanwendungen.

### Buildvorgehen:
1. lualatex document.tex
2. biber document
3. lualatex document.tex
4. lualatex document.tex

### Beispielsweise in der Shell:  
lualatex document.tex && biber document && lualatex document.tex && lualatex document.tex 

### In TexMaker unter Schnelles Übersetzen User-Buildvorgehen:
lualatex -interaction=nonstopmode %.tex|biber %|lualatex -interaction=nonstopmode %.tex|lualatex -interaction=nonstopmode %.tex

### Für das Quellenverzeichnis:
Bearbeite die Datei .bib in Ordner \content\bib.

Füge die Quellen in BibTeX Form hinzu.
Tipp: Verwende JabRef.
