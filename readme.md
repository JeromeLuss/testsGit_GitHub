Premier fichier créé sur la branche Master (pas encore renommée) du repertoire local Git. 
Suivi de [git add .] puis git [commit -m "premier commit, premier fichier"]

Première modification pour le second commit. 
Suivi de [git add .] puis git [commit -m "deuxieme commit, premier fichier modifie"]

Ceci est une ligne ajoutée sur la branche "new"
Pour ajouter une nouvelle branche, on peut soit faire :
- [git branch new] la nouvelle branche est créée mais on reste sur l'ancienne branche.
- [git checkout -b new] la nouvelle branche est créée et on bascule sur celle-ci.

Après avoir testé différentes opérations entre les branches new et master,
On va passer sur github. 
Créer un repository (sur mon gitHub ce sera "testsGit_GitHub"). 
Surtout ne pas mettre de fichier readme sur ce dépôt github, cela facilitera le push de Git
vers gitHub. 

GitHub propose des marches à suivres intéressantes dont celle ci:
   ==========================================================================
	…or push an existing repository from the command line

	git remote add origin https://github.com/JeromeLuss/testsGit_GitHub.git
	git branch -M main
	git push -u origin main
   ==========================================================================	

Ce sont les instructions que nous allons donner à Git. 
La première permet de déclarer un dépot distant s'appelant "origin" et pointant vers l'URL qui suit. 
La deuxième permet de renommer la branche actuelle en "main". Il faut le faire quand on est sur la branche master. 
La troisième va pousser le contenu de main local vers main distant. L'option -u permet de rendre cette liaison 
   répétable au prochain push sans la préciser. 