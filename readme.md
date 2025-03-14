Processus de création d'algoo pour déterminer le ombre de caratère

Etape N°1 : Déclaration de variable de compteur 

longueur : détermine le nombre total de caractères.

mots : Compte les mots en détectant les débuts et les fins des mots.

voyelles : Compte le nombre de voyelles grâce à un ensemble (Set) contenant toutes les voyelles.

Conditions principales :

Si un caractère fait partie des voyelles, le compteur de voyelles est incrémenté.

Si un caractère est un espace, il marque la fin d’un mot.

Si un caractère n'est pas un espace et qu'on était en dehors d'un mot, cela marque le début d’un nouveau mot.

Arrêt au point final :

L'algorithme cesse de parcourir la phrase dès qu'il rencontre un point.
