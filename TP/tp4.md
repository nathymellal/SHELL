# TP - 4

Créer un annuaire téléphonique
Le script devra permettre la gestion d'un annuaire téléphonique. Il devra inclure les fonctionnalités suivantes :

ajouter un contact (nom + tel + mail) modifier un contact voir la liste de tous les contacts (triés par ordre alphabétiques grâce à leurs noms et n'afficher que leurs noms) voir le détail d'un contact grâce à son nom, retrouver le nom d'un contact grâce à son adresse mail, retrouver le nom d'un contact grâce à son téléphone, supprimer un contact, L'ensemble des informations devront être enregistrées dans un fichier texte.

## le CODE & les commentaires : ( en cours )
```bash


#!/bin/bash


refus()
{
echo Ne pas interrompre le programme...
}

if [ $# = 0 ]
then
	echo "---MENU---"
	echo " 1- Ajouter un contact" 
	echo " 2- Modifier un contact" 
	echo " 3- Rechercher un contact (téléphone)"
	echo " 4- Rechercher un contact (email)"
	echo " 5- Lister les contacts"
	echo " 6- Supprimer un contact"
	echo "----------"
	read -p "Saisissez un chiffre : " contactmodify


else
	echo " erreur "

fi

if [ $contactmodify = 1 ]
then
	read -p"Nom : " nom
	read -p"Prenom : " prenom
	read -p"Numero de telephone : " tel
	read -p"Email : " email
	
	echo "$nom:$prenom:$tel:$email"
	echo "Confirmez-vous ? (o/n)"
	read reponse
	case "$reponse" in
	o|oui)	echo "$nom:$prenom:$tel:$email" >> annuaire.txt
	echo Utilisateur $nom enregistré;;
	n|non)	echo "Information NON enregist
```
