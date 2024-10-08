My Name Is Sadek Belkhiria

6. Si vous avez oublié de créer un fichier README.md lors de l'ini�alisa�on du projet,
comment pouvez-vous l'ajouter après coup et commiter les changements ?

*git add README.md
*git commit -m "Ajout du fichier README.md"
*git push origin main



7. Comment définir un dépôt distant si vous n'en avez pas configuré un lors de la créa�on
du projet ?
*git remote add origin git@gitlab.com:zorgatiomar428/devops.git
*git push -u origin main

3. Comment annuler les modifica�ons locales d'un fichier avant de les ajouter à l'index ?

*git checkout -- index.html


4. Comment visualiser les fichiers qui sont prêts à être commités dans Git (staging) ?
*git status


4. Comment suivre (track) un dépôt distant et récupérer toutes les branches de ce dépôt ?
*git remote add origin git@<remote-repo-url>.git
*git fetch origin


5. Comment supprimer une branche locale après l'avoir fusionnée dans master ?
*git branch -D dev

8. Comment afficher la liste des branches ac�ves et en cours de développement dans
Gi�low ?
*git flow feature list


9. Comment annuler une branche de correc�f (ho�ix) avant de la finaliser si vous constatez
une erreur ?
*git checkout develop
*git branch -D hotfix/mon-correctif
*git push origin --delete hotfix/mon-correctif
