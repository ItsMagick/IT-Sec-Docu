# IT-Sec-Docu
LaTeX documentation for module IT Security

Dieses Dokument beinhaltet eine Vollständige Studienarbeit als Wissenschaftliches Paper zum Thema Log4Shell.

Verfasst wurde es von https://github.com/JoStrecker und von https://github.com/ItsMagick.

Kompilieren kann man das Dokument mit 1. :
in IT-Sec-Docu/src

`pdflatex -file-line-error -interaction=nonstopmode -synctex=1 -output-format=pdf -output-directory=/home/charon/Downloads/IT-Sec-Docu/out main.tex`

gefolgt von 2. :
in IT-Sec-Docu/out
`biber --input-directory=/home/charon/Downloads/IT-Sec-Docu/src main`

gefolgt von zwei mal  dem Schritt 1. 
