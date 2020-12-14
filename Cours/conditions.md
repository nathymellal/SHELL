# Les conditions
L'intéret de la condition est de faire une action si une opération est faite, par exemple : `si` "il a beaucoup d'argent",`alors` "il peut investire". `sinon` "il n'investit pas ".
Les conditions se note comme cela :

- `if`   :arrow_right: donne SI
- `then` :arrow_right: donne ALORS
- `else` :arrow_right: donne SINON
- `fi`   :arrow_right: donne la fin de la conditions

On peut administrer des conditions sur des fichiers, nombres et des chaines de caractères.

###  :small_red_triangle: Fichiers

* `[-d dossier]` :arrow_right: savoir si le dossier existe
* `[-a  fichier]` :arrow_right: savoir si le fichier existe 
* `[-r fichier]`/`[-w fichier]`/`[-x fichier]` :arrow_right: savoir si le fichier est lisible, modifiable, executable
* `[-s fichier]` :arrow_right: savoir si la taille du fichier est supérieure a 0



###  :small_red_triangle: Chaines de caractères

* `[$string == $string1]` :arrow_right: savoir si string est égale a string1
* `[-z $string]` :arrow_right: savoir si string est vide
* `[-n $string]` :arrow_right: savoir si string n'est pas vide


###  :small_red_triangle: Nombres

* `[$nombre0 -ne $nombre1]` :arrow_right: savoir si les nombres ne sont pas égaux
* `[$nombre0 -eq $nombre1 ]` :arrow_right: savoir si les nombres sont égaux
* `[ $nombre0 -lt $nombre1 ]	` :arrow_right: savoir si nombre0 est supérieure a nombre1
* `[ $nombre0 -gt $nombre1 ]` :arrow_right: savoir si les nombre0 est inférieure a nombre1





