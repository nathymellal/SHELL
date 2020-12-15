# Les variables

> En informatique, les variables sont des éléments qui associent un nom (l'identifiant) à une valeur. La valeur peut être de nature différente : nombre, texte, etc...  Une variable contient une valeur qui peut varier au cours de l’exécution du programme.

Déclaration d'une variable : `nomdelaVAR='valeur de la VAR'`

Exemple :
```
var1="Hello"
phrase='comment allez vous?'

```
Pour montrer une variable il suffit de taper echo $nomdelaVAR

```
var1="Hello"
echo $var1
```
le résultat : 
```
$./variable.sh
Hello
$

```

### :small_red_triangle: Les variables d'environnment 

Une variable d'environnement est une donnée du système que l'on peut récupérer à n'importe quel moment dans nos scripts Shell. Elles servent à communiquer des informations entre les programmes qui ne se trouvent pas sur la même ligne hiérarchique, et qui ont donc besoin d'une convention pour se communiquer mutuellement leurs choix.

### :small_red_triangle: Quelque variables d'environnement
- HOME : répertoire home
- PWD : chemin d'accès dans lequel se trouve l'utilisateur
- USER : identifiant de l'utilisateur
- SHELL : Type de Shell utilisé
- OLPWD : dossier dans lequel on se trouvait avant

### :small_red_triangle: Variables de paramètres
```
echo "Vous avez lancé $0, il y a $# d\ 'élèves"
echo "Le paramètre 1 est $3"

```
```
$ ./variables.sh param1 param2 param3
Vous avez lancé ./variables.sh, il y a 3 élèves
Le paramètre 1 est param3
```
"$#" contient le nombre de paramètres"$0" contient le nom du script exécuté"$1" contient le premier paramètre "$2"contient le second paramètre ... "$n" contient le énième paramètres.










 :back: [Sommaire](https://github.com/nathymellal/SHELL/blob/main/README.md)

