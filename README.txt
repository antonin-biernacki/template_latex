COMMENT UTILISER CE TEMPLATE
=============================

1. Copie-colle tout ce dossier et renomme la copie pour ton nouveau rapport
   (ex. "rapport_POC1002").

2. Ouvre rapport_moderne.tex dans TeXstudio et modifie en haut du fichier :
   - \title{...}       -> le titre de ton rapport
   - \author{...}       -> ton nom
   - Nom de l'université, code du cours, intitulé du cours (dans le bloc titlepage)
   - Numéro d'étudiant (XXXXXX000)
   - La couleur accentcolor si tu veux changer la teinte des titres

3. Mets ton logo dans le dossier images/ puis décommente la ligne
   \includegraphics{...} dans la page de titre.

4. Ajoute tes références dans biblist.bib (format BibTeX), puis utilise
   \cite{clé} dans le texte.

5. Compile avec F5 ou F6 dans TeXstudio (pdflatex -> bibtex -> pdflatex -> pdflatex,
   enchaînement automatique si "compilation complète" est sélectionnée).

Astuce : ne modifie jamais ce dossier "maître" directement -- garde-le comme
base propre et duplique-le à chaque nouveau rapport.
