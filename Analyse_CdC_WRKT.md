# Différentes taches
## Deroulement du jeu
- Player avance autant que possible à travers des routes, des rivières.
- Si arrêt total, un aigle apparaît et s'empare OU se déplace de trois pas en arrière -> dans tous les cas, fin de partie
- Un deplacement d'un carré -> Points++ (tous les 50 points -> Faire un effet sonore)
- Pièces d'or pour déverouiller les mascottes sur le plateau

## Besoins
- UML : Etablir diagramme de classes, diagrammes d'activités, d'états et des cas d'utilisations
- Fonctionnalités minimum du jeu : 1 terrai fixe avec objet mouvant non franchissable

## Fonctionnalités du jeu
- Map :
    - Herbe : objets statiques (buissons ou arbres)
    - Route : objets en mouvement (voirture et camions) avec un espacement raisonnable entre chaque obstacle,
    - Rail : objets en mouvement (train)
    - Rivière : objet en mouvement (troncs d'arbres et nénuphars)
- Mouvement des objets
    - Differents types de lignes se succéder de manière aléatoire (pas le même pattern entre différentes parties)
    - Sens de direction d'une ligne -> Immutable après affichage
    - Vitesses de déplacement d'un objet -> Fixe
    - Les objets peuvent avoir des vitesses différentes
- Scoring
    - A chaque ligne franchie, score++
    - Si score = 50, son quack

- Interface (Faire un diagramme cas d'utilisation)