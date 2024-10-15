## Mathématiques en classe de 1ère spécifique

Les notes de cours du dossier `/notes/` sont à compiler avec pdfLaTeX et le flag `-shell-escape`.

>> pdflatex -shell-escape notes.tex

Sur TeXworks, il faut aller dans Preferences, Typesetting, Tool Configuration (double click pdfLaTeX) et ajouter l'argument `-shell-escape`.

Les autres fichiers `.tex`se compilent sans précaution particulière. Les versions OpenDyslexic requièrent XeLaTeX et les polices OpenDyslexic et Fira Math.
