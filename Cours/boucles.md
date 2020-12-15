# les Boucles en Shell

Le bute d'une boucle est de répéter une action jusqu'a ce que une condition soit remplis/vérifiée. Pour boucler dans un script Shell on utilise  `while` et `for`.


:small_red_triangle: Le `for` renvoi au POUR. Exemple, POUR un jeux dans cette liste suivante " jeux de guerre " " jeux d'aventure ", donner chaque jeux et acheter le.
```
for var in valeur0 valeur1; do
     echo action
done

```
- `for` renvoi au POUR
- `in` renvoi au DANS CETTE LISTE
- `do` renvoi au ALORS
- `done` renvoi a la FIN DE LA BOUCLE

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


 :back: [Sommaire](https://github.com/nathymellal/SHELL/blob/main/README.md)

