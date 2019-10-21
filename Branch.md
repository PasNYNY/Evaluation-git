git branch					                        #| Affihe les Différente branch.
git branch "Nom-branch"				                #| Créer une nouvelle branch.
git checkout "Nom-branch"				            #| Se deplace sur la branch.
git checkout -b "Nom-Branch"			            #| Créer une branche et ce déplace dessus.
git branch --no-merged				                #| List toutes les branch non mergées.
git branch -d "Nom-Branch"		                    #| Supprime la branch.
git branch -D "Nom-Branch"		                    #| Force la suppression de la branch.
git merge "Nom-Branch"					            #| Merge la branch dans master.
git commit "un message" --amend --no-edit           #| Elle permet de changer uniquement le message du dernier commit.
git log --oneline --graph			                #| Visualise le graph des commit
git stash					                        #| Remiser le code.
git stash apply --index				                #| Essaye de remettre ce qui était dans l'index.
git stash apply					                    #| On recupère ce qui était dans la stash et on l'applique.
git stash list					                    #| Listez sur la branche les stash.
git stash drop					                    #| Supprime le premier stash.
git tag 					                        #| liste les tag.
git tag v1					                        #| Créer un tag legé (tres peu utilisé).
git tag -l 'v8.*'				                    #| Rechercher des tag particuliers.
git tag -a v1.0 -m "version 1 de l'application"     #| Créer un tag noté avec un message.
git tag -a v1.0.1 -m "version 1.0.1" 9fceb2	        #| Etiquetter après coup sur un commit donné.
git show v8.2					                    #| Voir un tag Noté.