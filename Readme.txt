https://try.github.io/levels/1/challenges/17


-button droit sur un dossier  gitbsh et la commande
git init => permet de creer le premier repo local


git clone <url remote> permet de cloner un projet dans gitub


git  --->  creer un repo distant 
		lier le depot local  <> distant du local au remote


git config get --proxy // verification du pconfig actuelle du proxy

git config set --proxy "http://login%20password@domain:port"

login= mon login de l'entreprise

%20 = espace


//proxy de l'entreprise
- internet explore
- outil
- option internet
- connexion
- paramettre reseau
- dans adresse on a le proxy 

le proxy sert a securiser le pc et l'internet


vpn : permet de remplacer le proxy et ca te permet d'acceder a distance  à ton pc


git config --global user.name "MCHINDA Mohamed" //configuration du nom

commit: permet d'envoyer les modif dans le repos distant (formation-git)

staging area: fenetre permettant de voir les fichier modifier

git add : permet d'ajouter un fichier et il possede plusieurs option

git add . ajoute tout les fichier qui sont dans mon repo local

git add nom_file

git add fichier d'un rerepertoire

git add *.html //on spécifie l'extention des fichiers qu'on veut ajouter

git commit -m " l'option -m permet de spécifier un commentaire "
git pull -a <nom brache> au deuxieme pull je ne suis pas obliger de spécifier le nom de la branch



git status

git bransh

git checkout <nom branche>

git log

git --help

git remote -v //permet de visualiser les repertoires distant


git reset head <nom fichier> permer d'annuler un commit

git checkout develop ---> switcher  vers develop

git branch -av //montre les branches local et distant



feature-mes-declaration //une nouvelle branche doit commencer par feature


---------------------------------------------------
creation d'un repo distant

https://github.com/mchinda/formation_git.git


git remote add origin <url> // permet de connecter le projet local et le projet distant

push origin/feature-mes-declarartion // on pousse les modif dans feature-mes-declarartion distant

git merge: Permet de recuperer une modif en supprimant mon fichier de base.

git rebase : on se place dans le fichier future et je recupere les modification en gardant le fichier de base


avant git push on fait:

git pull origin master
Apres 
git push origin master

git pull remote local

