# Atelier-Shell
Pour suppimer les lignes vides dans un fichier texte il faut se positionner dans le dossier contenent notre fichier texte avec la commande cd C:\Users\fatim\Desktop\ECF Mars.
Apres on utilise la dexième commande grep "\S" input-lignes-vides.txt >> output-lignes-vides.txt 
Grep recherche des motifs ou des expressions régulières dans un fichier donnée.
Dans ce cas le motif recherché est \S qui signifie "tous les caractères qui ne sont pas des espaces blancs" (c'est à dire les caractères qui ne sont pas un espace, une tabulation ou une nouvelle ligne)
La double flèche ">>" est utilisée pour rediriger la sortie de la commande vers un fichier "output-lignes-vides.txt", en ajoutant les résultats à la fin du fichier plutôt que de remplacer son contenu.

Ainsi, la commande complète grep "\S" input-lignes-vides.txt >> output.txt recherche toutes les lignes du fichier "input.txt" qui contiennent au moins un caractère non-espace et ajoute les résultats à la fin du fichier "output-lignes-vides.txt".