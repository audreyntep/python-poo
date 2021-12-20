# Cour OPEN CLASS ROOMS : https://openclassrooms.com/fr/courses/4302126-decouvrez-la-programmation-orientee-objet-avec-python/4302133-tirez-pleinement-parti-de-ce-cours

# UN MONDE PARALLELE

Nous allons manipuler les données sur les habitants qui peuplent ce monde parallèle pour répondre à deux questions existentielles :

    À partir de quelle densité de population est-on moins agréable que la moyenne ?

    Est-ce que les seniors gagnent plus d’argent que les jeunes ?

## Les habitants de notre monde

Nous utiliserons la base http://pplapi.com/, un réseau social factice composé de centaines de milliers de personnes, pour peupler notre monde.

## Fonctionnalité du programme

Comment notre programme va-t-il nous aider à répondre à nos interrogations ? 

Voici les étapes qu'il devra suivre :

    Ouverture d'un fichier JSON qui contient 100 000 agents,

    Réalisation de calculs,

    Affichage d'un premier graphique montrant le degré d'agréabilité en fonction de la densité de population

    A la fermeture de ce graphique, un second s'affiche avec les revenus moyens en fonction de l’âge.

## Etapes

Nous allons réaliser ce programme en plusieurs étapes :

    Transformation des agents JSON en agents que nous pourrons réutiliser.

    Agents : ajout des attributs (chaque agent a plusieurs "propriétés" : agréabilité, revenu, ...)

    Création de la grille qui nous permettra de situer les personnages dans le monde.

    Création des zones composant cette grille.

    Ajout du premier habitant dans sa zone.

    Peuplement du monde avec les 100 000 agents.

    Création du graphique Agréabilité versus densité de population.

    Création du graphique Revenu versus âge