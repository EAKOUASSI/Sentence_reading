Instructions Exercice

    La longueur de la phrase (le nombre de caractères).
    Le nombre de mots dans la phrase (en supposant que les mots sont séparés par un seul espace).
    Le nombre de voyelles dans la phrase.

Vous devez garder à l'esprit que: 

    Chaque caractère sera traité séparément.
    Le dernier caractère est le point.
    Utiliser trois variables comme compteurs.

Processus de création d'algo:
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