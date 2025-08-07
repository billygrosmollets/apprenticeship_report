Utilisation
Une fois le fichier créé :

Compiler : latexmk document.tex
Nettoyage : latexmk -c (supprime les fichiers temporaires)
Nettoyage complet : latexmkrc -C (supprime aussi le PDF)
Mode continu : latexmk -pvc document.tex (recompile automatiquement)