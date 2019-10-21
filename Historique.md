git log -p					        #| Affiche les modifications de l'ensemble des commits
git log -2 -p					    #| Affiche les modifications sur les 2 derniers commits
git log -p exemple.txt				#| Affiche les modifications au sein d’un fichier 
git --no-pager log --oneline        #| Affiche les logs puis sortir de la commande.
git --no-pager log -3 --oneline		#| Affiche les 3 derniers commit et sortir de la commande.
git log --author "Name"			    #| Consulter les commits d’un auteur en particulier.
git log --since=1.day				#| Consulter les commits sur 1 jour.
git log --before="2019-09-01"		#| Consulter les commits à une date précise.
git log exemple.txt				    #| Consulter les commits sur un fichier Précis.
git log "Hachagecommit1" "Hachagecommit2"   #| voir les modifications entre deux commits.
git log --stat exemple.txt			#| Visualiser les stats du fichier exemple.txt.
git blame exemple.txt				#| Montre qui a modifié dans un lapsus de temps le fichier exemple.txt.
git diff					        #| Montrer les differences sur le dernier fichier modifié.
git diff --stat				    	#| Faire des stat sur les différences opérées dans les fichiers.
git diff --cached				    #| Affichera les différences entre le dernier commit et l’index.
git diff HEAD-1					    #| Affichera les differences entre le fichier modifier et l'avant dernier commit.
git diff HEAD-1 HEAD				#| Voir les différences entre le HEAD et les 3 commits d'avant.
git restore exemple.txt				#| Remet le dépôt dans l’état dans lequel il se trouvait juste avant la modification
git restore --staged				#| Refait la modification ajoute le fichier dans l’index.
git reset HEAD~1			    	#| Annule le dernier commit et met remonte au dernier
git reset "Hachagecommit"		    #| annule le commit.
git reset --hard HEAD~1				#| Annule le dernier commit et supprime les modifications.
git checkout 9b85968 index.html	    #| Permet de revenir avant les modifications.
git revert 419e298				    #| la commande suivante elle va créer un commit revert d’annulation du dernier commit réalisé .


