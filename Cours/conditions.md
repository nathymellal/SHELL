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
On peut aussi utiliser des symboles comme `&&` qui signifie "ET" et `||` qui signifie "OU" :
```
if [ $# -ge 1 ] && [ $1 = 'adresse' ]
then
        echo "Bravo !"
        echo "..."
else
        echo "..."
fi
```

La condition `Elif` ( sinon si ) permet de vérifier plusieures actions ( la 1ère, la 2ème, la 3ème .....) et si aucunes conditions n'est remplis, éffectuer une action.

On peut administrer des conditions sur des fichiers, nombre et des chaines de caractères.

###  :small_red_triangle: Fichiers

* `[-d dossier]` :arrow_right: savoir si le dossier existe
* `[-e  fichier]` :arrow_right: savoir si le fichier existe 
* `[-r fichier]`/`[-w fichier]`/`[-x fichier]` :arrow_right: savoir si le fichier est lisible, modifiable, executable
* `[-s fichier]` :arrow_right: savoir si la taille du fichier est supérieure a 0
* `[ fichier1 -ot fichier2 ] ` :arrow_right: savoirsi le fichier 1 est plus vieux que le fichier 2
* `[ fichier1 -nt fichier2 ] ` :arrow_right: savoirsi le fichier 1 est plus récent que le fichier 2

##  :small_red_triangle: Chaines de caractères

* `[$string == $string1]` :arrow_right: savoir si string est égale a string1
* `[ $string != $string1 ] ]` :arrow_right: savoir si string est différent de string1
* `[-z $string]` :arrow_right: savoir si string est vide
* `[-n $string]` :arrow_right: savoir si string n'est pas vide


###  :small_red_triangle: Nombre

* `[$nombre0 -ne $nombre1]` :arrow_right: savoir si les nombres ne sont pas égaux
* `[$nombre0 -eq $nombre1 ]` :arrow_right: savoir si les nombres sont égaux
* `[ $nombre0 -lt $nombre1 ]	` :arrow_right: savoir si nombre0 est supérieure a nombre1
* `[ $nombre0 -gt $nombre1 ]` :arrow_right: savoir si les nombre0 est inférieure a nombre1
* `[ $nombre0 -ge $nombre1] ` :arrow_right: savoir si nombre0 est supérieur ou égal à nombre1

**conditions avec la double parenthèse**

* `(( nombre0 == nombre1 ))	` :arrow_right: savoir si les nombres sont égaux
* `(( nombre0 != nombre1 ))	` :arrow_right: savoir si les nombres ne sont pas égaux


 :back:[Sommaire](https://github.com/nathymellal/SHELL/blob/main/README.md)








