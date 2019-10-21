git config (--global user.name Tony) (--global user.email tony@tony.fr)  #| S'enregistre dans .gitconfig de votre compte user
git init                                #| Initialise un project git.
git status                              #| Affiche l'etat de configuration de Git. .
git add (fichier)                       #| Ajouter un fichier dans la zone de l'index.
git rm --cached (Fichier)               #| suprime du cache le fichier.
find .git/objects -type f               #| Affiche la clef de hachage.
git commit -m "texte"                   #| Créer un Commit et le nomme geace a -m.
git log 					            #| Affiche les commit et leurs information.
git log -5 					            #| Voir les 5 derniers commit.
git log -p -5				            #| Voir les modification entre les 5 dèrniers commit.
git log --oneline			            #| Affiche chaque commit en une seule ligne.
git log master..origin/master	        #| Affiche les différences entre les branches "Origine" et "Master".
git log --stat				            #| Voir le status des modification de commit.
git log --since=2.weeks                 #| Voir la modification de commit sur 2 semaine.
ls                                      #| Affiche les fichier du Dossier pour lequ'elle est tapé le "ls".
git blame -L 40,60 readme.md            #| rechercher qui a fait les modifs par ligne "-L".
git blame --since=3.weeks -- readme.md  #| depuis 3 semaines avec auteurs des modifications.
git blame -L "/^### /" readme.md        #| recherche avec expression régulière.
git mv                                  #| Git integre la modiffication a sont historique.
