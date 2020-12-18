# Les commandes du Shell

### `man`
Cette commande permet d'afficher une documentation sur une commande renseignée.

### `echo`
Cette commande permet d'afficher une ligne, par exemple:

```
$echo "Hello World !"
Hello Wolrd !
```

### `let`
Cette commande permet de faire des oppérations comme des multiplications, divisions, additions, modulo, soustractions et les puissances.
```
x=25
let "x=$x + 5"
echo $x
```

## :small_red_triangle: La Naviguation dans les dossiers

### `cd` 
 Cette commande permet de changer de répertoire, on peut donner le nom du répertoire en argument fain d'y accéder.
 
### `pwd` 
 Cette commande permet de donner le répertoire de travail ou se trouve actuellement l'utilisateur.
 
 
### `ls`
Cette commande permet d'afficher le contenu du répertoire dans lequel se trouve l'utilisateur. Cette commande peut être complétée par des paramètres comme `-à` qui permet de montrer les fichiers cachés du répertoire, il y-a aussi `-l` qui lui permet d'afficher les permissions, la taille du fichier, la date et l'heure, l'utilisateur propriétaire.

## :small_red_triangle: La création, suppression et modification
 
### `touch`
Cette commande `touch` a pour bute de créer un fichier.

### `mkdir`
Cette commande `mkdir` a pour bute de créer un dossier.

### `mv`
Cette commande `mv` permet de déplacer un fichier/dossier en tapant en premier ce qu'on veut déplacer et en deuxième l'endroit où il va être mis.

### `rm`
Cette commande `rm` permet de supprimer un fichier en spécifiant en argument son nom.

### `cat` 
Cette commande `cat` permet d'afficher de contenu d'un fichier.

### `cp`
Cette commande `cp` permet de coller et/ou copier un fichier ou un dossier

### `useradd`
Permet de ajouter un utilisateur.

### `userdel`
Permet de supprimer l'utilisateur.

### `useradd -G`
Permet de crée un utilisateur username en lui affectant automatiquement les groupes listés dans groups.

### `groupadd`
Permet de creer un groupe.

###`groupdel`
Permet de supprimer un groupe.



:back: [Sommaire](https://github.com/nathymellal/SHELL/blob/main/README.md)






 
 
 
 
