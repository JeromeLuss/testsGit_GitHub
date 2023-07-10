Premier fichier créé sur la branche Master (pas encore renommée) du repertoire local Git. 
Suivi de [git add .] puis git [commit -m "premier commit, premier fichier"]

Première modification pour le second commit. 
Suivi de [git add .] puis git [commit -m "deuxieme commit, premier fichier modifie"]

<<<<<<< HEAD
ceci engendrera plus tard un conflit. Je modifie en local cette ligne. 
Puis je fais git pull
=======
ceci engendrera plus tard un conflit. En effet, je rajoute ceci sur l'éditeur gitHub.
>>>>>>> 99b38ca1991b783ce8dc364647c03a8e2d9a4375

Le pull a créé cette erreur. Le fichier a été modifié par Git comme ci-dessus. 
Auto-merging readme.md
CONFLICT (content): Merge conflict in readme.md
Automatic merge failed; fix conflicts and then commit the result.

 Je le modifie et refait un push. (dans la réalité je choisirais une version par rapport à l'autre ou je ferais 
 un mix des deux, et j'enlèverais les signes >> et<<< et autres infos de comparaison).