##### Création de compte sur github
##### Télécharger git windows: https://git-scm.com/download/win

##### Cloner le répository en local: 
git clone https://github.com/kdebdi/it-pour-les-nuls

##### Toutes les commandes git portées sur le projet doivent être sur le bon dossier
cd it-pour-les-nuls

##### Checkout de la branche main
git checkout main

##### Préparer les fichiers à commiter
git add <file> ou bien git add -A

##### Commiter les fichiers
git commit -m "commit message"

##### Afficher les branches
git branch
git branch -r

##### Envoyer au serveur
git push -u origin main

##### Synchroniser avec le serveur
git pull

##### Montrer les changements
git diff --name-only

##### Montrer les changements indexées
git diff --name-only --cached