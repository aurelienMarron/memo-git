# memo-git

git init = activer git pour un répertoire
git status = vérifiez l'état des modif dans un dépot
git diff = afficher les modifs
git add <file name> = ajouter les modifs    tenir compte du changement
git add . = ajouter toutes les modifs
git commit -m "" = soumettre les modifs
git push --tags= pousse les tags
git push origin v1.0
git remote origin ""https..."= donne l'url ou pousser
git push -u origin master= précise la branche...
git clone <url>=recuperer sur github



git permet de sauvegarder en local l'avancée d'un projet. Github permet de le faire en ligne et de collaborer sur un projet

conflit= modif sur le même fichier que github n'arrive pas à résoudre seul (en fusionnant les fichiers) par un merge
Le conflit se voit sur vs code en vert la modif en local et en bleu la modif sur github
Pour le résoudre il faut dans vs code choisir la version que l'on veut garder en supprimant l'autre