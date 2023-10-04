# TP03 - Tableaux et Vecteurs
**STS 1CIEL** - Un nouveau TP pour mettre en application les tableaux et les vecteurs vus en cours.

Ce repository est un projet CLion dans lequel vous trouverez un certain nombre de fichiers `.cpp` qui vont vous permettre de coder chaque exercice demandé. Une fois terminé il suffira de faire un commit, puis un push vers GitHub afin de rendre votre travail.


## Exo1 - Un premier exercice sur les tableaux
- Créez un tableau de 10 entiers que vous appellerez `tab`, vous initialiserez toutes les cases de ce tableau à 0.
- Affichez sur le terminal la valeur du premier élément et du dernier :
```text
** Avant changement **
Le contenu du premier element est : 0 , le contenu du dernier est : 0
```
- Ensuite vous initialiserez le premier élément du tableau à 100 et le dernier à 1000.
- Pour terminer, vous afficherez à nouveau le contenu à l'écran :
```text
** Après changement **
Le contenu du premier element est : 100 , le contenu du dernier est : 1000
```


## Exo 2 - Critique de films
Nous souhaitons afficher les notes attribuées par 4 journaux pour 3 films : 

|Journal|Moi Moche et Méchant|Les Minions|Il était une fois Gru|
|:---:|:---:|:---:|:---:|
|Le Monde|5|5|5|
|Libération|2|3|4|
|Le Figaro|5|4|5|
|Les cahiers du cinéma|0|0|0|

Pour cela vous devrez déclarer :

- 2 constantes : `NB_JOURNAUX` et `NB_FILMS` représentants respectivement le nombre de journaux et le nombre de films.
- Un tableau de chaines de caractères : `journaux` qui contiendra le nom des journaux.
- Un autre tableau de chaines de caractères : `films` qui contiendra le nom des films.
- Un dernier tableau 2D d'entiers `notes` qui contiendra les notes. Les lignes sont attribuées aux journaux et les colonnes aux films.

L'exemple suivant montre le comportement attendu du programme à réaliser :
```text
Pour quel film voulez-vous afficher les notes ?
1. Moi Moche et Méchant
2. Les Minions
3. Il etait une fois Gru
2
**** Les Minions ****
Le Monde : 5
Liberation : 3
Le Figaro : 4
Les cahiers du cinema : 0
```
⛔ **Il est interdit d'utiliser des alternatives (`if, switch case ...`) ou des boucles (`while, for, ...`)**


## Exo 3 - Un premier exercice sur les vecteurs
- Déclarez un vecteur d'entiers appelé `vec` et initialisez les éléments de ce vecteur à : 10, 20, 30, 40 et 50.
- Affichez sur le terminal la valeur du premier élément et du dernier :
```text
** Avant changement **
Le contenu du premier element est : 10 , le contenu du dernier est : 50
```
- Modifiez ensuite le premier élément du vecteur pour qu'il devienne 100 et le dernier pour qu'il devienne 1000.
- Au final le vecteur doit contenir : 100,20,30 et 1000
- Pour terminer, vous afficherez à nouveau le contenu à l'écran :
```text
** Après changement **
Le contenu du premier element est : 100 , le contenu du dernier est : 1000
```

## Exo 4 - Un exo plus difficile sur les vecteurs

Écrivez un programme C++ comme suit :

1. Déclarez 2 vecteurs vides d'entiers nommés `vector1` et `vector2`, respectivement.
1. Ajoutez `10` et `20` à `vector1` de manière dynamique en utilisant `push_back`.
1. Affichez les éléments dans `vector1` en utilisant la méthode `at()` ainsi que sa taille en utilisant la méthode `size()`.
1. Ajoutez `100` et `200` à `vector2` de manière dynamique en utilisant `push_back`.
1. Affichez les éléments dans `vector2` en utilisant la méthode `at()` ainsi que sa taille en utilisant la méthode `size()`.
1. Déclarez un vecteur 2D vide appelé `vector_2d`. Rappelez-vous qu'un vecteur 2D est un **vecteur de vecteurs** d'entiers.
1. Ajoutez `vector1` à `vector_2d` de manière dynamique en utilisant `push_back`.
1. Ajoutez `vector2` à `vector_2d` de manière dynamique en utilisant `push_back`.
1. Affichez les éléments dans `vector_2d` en utilisant la méthode `at()` (Vous n'utiliserez pas de boucle).
1. Modifiez `vector1.at(0)` pour qu'il devienne `1000`.
1. Affichez à nouveau les éléments dans `vector_2d` en utilisant la méthode `at()`.
1. Affichez les éléments dans `vector1`.

Qu'avez-vous obtenu ? Avez-vous obtenu ce que vous attendiez ? Que pensez-vous qu'il s'est passé ?
<br>→ Donnez des explications en commentaire de votre programme !