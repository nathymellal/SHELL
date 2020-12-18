
# TP - 1


1- Scripts de gestion des comptes utilisateurs (Fini)
Faire un script de gestion des utilisateurs, qui doit permettre :

* de créer des utilisateurs
* de modifier des utilisateurs
* de supprimer des utilisateurs
* de voir tous les utilisateurs
* de faire une recherche sur l'existence d'un utilisateur en particulier












```bash

if [ $# = 0 ]
then
	echo "---MENU---"
	echo "./Tp4.sh add <username> / Ajouter un utilisateur" 
	echo "./Tp4.sh modify <username> Modifier un utilisateur" 
	echo "./Tp4.sh show <username> Lister les utilisateurs"
	echo "./Tp4.sh delete <username> / Supprimer un utilisateurs"
	echo "----------"
fi

if [ $1 = add ]
then
    sudo useradd $2
fi

if [ $1 = delete ]
then
    sudo userdel $2
fi

if [ $1 = show ]
then
    getent passwd $user > /dev/null
fi 

if [ $1 = modify ]
then
    echo "Que voulez-vous modifié ?"
    echo "1- Modifier l'utilisateur"
    echo "2- Modifier le mot de passe"
    read -p "saisissez un chiffre :" nbrmodify


    if [ $nbrmodify = 1 ]
    then 
        read -p "Entrez : 'nouvel_identifiant ancien_identifiant' " newid oldid
        sudo usermod --login $newid --home /home/$newid --move-home $oldid


        elif [ $nbrmodify = 2 ]
         then
            read -p "nouveau mot de passe :"
            sudo passwd $1
        else
            echo "le mot de passe saisie n'est pas bon"
    fi
fi
if [ $# = 0 ]
then
	echo "---MENU---"
	echo "./Tp4.sh add <username> / Ajouter un utilisateur" 
	echo "./Tp4.sh modify <username> Modifier un utilisateur" 
	echo "./Tp4.sh show <username> Lister les utilisateurs"
	echo "./Tp4.sh delete <username> / Supprimer un utilisateurs"
	echo "----------"
fi

f [ $1 = add ]
then
    sudo useradd $2
fi

if [ $1 = delete ]
then
    sudo userdel $2
fi

if [ $1 = show ]
then
    getent passwd $user > /dev/null
fi 

if [ $1 = modify ]
then
    echo "Que voulez-vous modifié ?"
    echo "1- Modifier l'utilisateur"
    echo "2- Modifier le mot de passe"
    read -p "saisissez un chiffre :" nbrmodify


    if [ $nbrmodify = 1 ]
    then 
        read -p "Entrez : 'nouvel_identifiant ancien_identifiant' " newid oldid
        sudo usermod --login $newid --home /home/$newid --move-home $oldid


        elif [ $nbrmodify = 2 ]
         then
            read -p "nouveau mot de passe :"
            sudo passwd $1
        else
            echo "le mot de passe saisie n'est pas bon"
    fi
fi

```


:back:[Sommaire](https://github.com/nathymellal/SHELL/blob/main/README.md)
