# les Boucles en Shell

Le but d'une boucle est de répéter une action jusqu'à ce qu'une condition soit remplis/vérifiée. Pour boucler dans un script Shell on utilise  `while` et `for`.


:small_red_triangle:Le `for` renvoie au POUR. Exemple, POUR un jeu dans cette liste suivante " jeux de guerre " " jeux d'aventures ", donner chaque jeu et achetez-le.
```
for var in valeur0 valeur1; do
     echo action
done

```
- `for` renvoie au POUR
- `in` renvoie au DANS CETTE LISTE
- `do` renvoie au ALORS
- `done` renvoie a la FIN DE LA BOUCLE

Exemple :
``` 
for jeux in 'aventure' 'guerre' 'fantastique' do
        echo "A quelle thème appartien ce jeux ? : $jeux"
done
```
```
A quelle thème appartien ce jeux ? : aventure 
A quelle thème appartien ce jeux ? : guerre
A quelle thème appartien ce jeux ? : fantastique
```
:small_red_triangle: le `while` renvoi au TANT QUE.

```
while [ condition ]; do
   echo action à effectuer
done

```
- `while` renvoi au TANT QUE
- `do` renvoi au ALORS FAIT
- `done` renvoi a la FIN DE LA BOUCLE
Il est possible d'iverser un `while` avec la commande until.


 :back: [Sommaire](https://github.com/nathymellal/SHELL/blob/main/README.md)

