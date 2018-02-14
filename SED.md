# Mémo commandes SED 

##Ressources intéressantes
- [funix](http://www.funix.org/fr/unix/expr-sed.htm).

##Les options
- -e : Permet de passer plusieurs commandes à la suite (de façon uniligne).
- -f : Permet de lancer un script sed externe (jamais essayé), par exemple :
'''bash
sed -f script.sed
'''
- -i : Permet d'appliquer le traitement directement sur le fichier passé en entrée
- -n : Permet de supprimer de la sortie les lignes non concernées par le traitement

##Les différentes fonctions
- /g : Applique le changement sur toutes les occurences
- s : Fonction de substitution qui permet de changer les occurences d'une chaîne par une autre
- d : Fonction de suppression 
- = : Permet d'afficher le numéro de la ligne sélectionnée
- p : Affiche les lignes selectionnées sur la sortie standard
