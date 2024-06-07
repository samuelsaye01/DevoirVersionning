1. clone du dépôt
   git clone https://github.com/samuelsaye01/DevoirVersionning.git

-configuration de l'identité Git avec le nom et l'email
git config --global user.name "samuel"
git config --global user.email "samuel.saye01@gmail.com"

2. Création de branches et developement
   intialisation du repot local sur Git
   git init
   création de la branche feature
   git checkout -b feature

Commit des changements
git commit -m "premier commit" 3) Gestion des conflits
Retour sur la branch main
git checkout main
bascule sur la branch feature
git checkout feature
Envoie des modifications
git add . : pour ajouter les fichiers
git push : pour envoyer les fichiers sur git
git checkout main : pour retourner sur la branch principale
git checkout feature : pour basculer vers la branche feature
git push : pour envoyer les modifications sur le remote de Git
git merge feature : pour fusionner la branche main avec la branche feature

Pour resoudre le conflit, j'ai utilisé les commandes :
git rebase feature
git rebase --continue
