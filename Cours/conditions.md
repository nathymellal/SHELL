# Les conditions
L'intéret de la condition est de faire une action si une opération est faite, par exemple : `si` "il a beaucoup d'argent",`alors` "il peut investire". `sinon` "il n'investit pas ".
Les conditions se note comme cela :

- `if`   :arrow_right: donne SI
- `then` :arrow_right: donne ALORS
- `else` :arrow_right: donne SINON
- `fi`   :arrow_right: donne la fin de la conditions
 
Exemple : 
* Condition `If`
```
if [ condition ]
then
        echo "action"
fi
```
* Condition `Then`/`Else`
```
if [ condition ]
then
        echo "act1"
else
        echo "act2"
fi
```

La condition `Elif` ( sinon si ) permet de vérifier plusieures actions ( la 1ère, la 2ème, la 3ème .....) et si aucunes conditions n'est remplis, éffectuer une action.

On peut administrer des conditions sur des fichiers, opérateur et des chaines de caractères.

###  :small_red_triangle: Fichiers

* `[-d dossier]` :arrow_right: savoir si le dossier existe
* `[-a  fichier]` :arrow_right: savoir si le fichier existe 
* `[-r fichier]`/`[-w fichier]`/`[-x fichier]` :arrow_right: savoir si le fichier est lisible, modifiable, executable
* `[-s fichier]` :arrow_right: savoir si la taille du fichier est supérieure a 0



###  :small_red_triangle: Chaines de caractères

* `[$string == $string1]` :arrow_right: savoir si string est égale a string1
* `[-z $string]` :arrow_right: savoir si string est vide
* `[-n $string]` :arrow_right: savoir si string n'est pas vide


###  :small_red_triangle: Opérateur

* `[$valeur0 -ne $valeur1]` :arrow_right: savoir si les nombres ne sont pas égaux
* `[$valeur0 -eq $valeur1 ]` :arrow_right: savoir si les nombres sont égaux
* `[ $valeur0 -lt $valeur1 ]	` :arrow_right: savoir si nombre0 est supérieure a nombre1
* `[ $valeur0 -gt $valeur1 ]` :arrow_right: savoir si les nombre0 est inférieure a nombre1

**conditions avec la double parenthèse**

* `(( valeur0 == valeur1 ))	` :arrow_right: savoir si les nombres sont égaux
* `(( valeur0 != valeur1 ))	` :arrow_right: savoir si les nombres ne sont pas égaux


 :back:[Sommaire](https://github.com/nathymellal/SHELL/blob/main/README.md)








