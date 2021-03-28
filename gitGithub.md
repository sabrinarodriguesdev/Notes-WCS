# Commandes de base  ***Git et Github***  
## Gestion de version de code 

### Git config 
 On l’utilise pour configurer les préférences de l’utilisateur :git config --global user.email sam@google.com  
### Git init  
 créer un nouveau dépôt Git.  
### Git add  
ajouter des fichiers à l’index ex: ***git add temp.txt*** ou ***.*** pour mettre "tout"
### Git commit  
soumettre  : ***git commit –m “Description du commit”***
### Git status
affiche la liste des fichiers modifiés et les fichiers en attente
### Git remote
lier dépot DISTANT à un dépot LOCAL : ***git remote add  (nom du remote) + (url du remote )*** 
### Git push
mettre à jour dépot dépot DISTANT des modifs LOCALES. ***git push origin master***
### Git pull
mettre à jour dépot LOCAL des modifs du DISTANT. ***git pull origin master*** 
### git branch 
creer une branche ***git branch (+nom de la branche )*** 
creer + se déplacer dedans : ***git checkout -b (+nom de la branche)*** 
renommer la branche : ***git branch -m (+ nouveau branchname )***
supprimer une branche : ***git branch -d (+ nom de la branche )
### Git checkout
se deplacer dans une branche : ***git checkout (+ nom de la branche )*** 
### Git merge
fusionner une branche dans la branche active :***git merge ( + nom-branche)***
### Git diff
lister les conflits. Pour visualiser les conflits d’un fichier : ***git diff --base (nom-fichier)***
afficher les conflits entre les branches à fusionner avant de les fusionner: ***git diff (branche-source) (branche-cible)***
Pour simplement énumérer tous les conflits actuels, utilisez: ***git diff***
### Git log --oneline 
liste les commits et leur numéro de hashage 
### Git revert 
git revert (+ numéro de hashage) 
revenir en arrière sur un commit ( on garde la trace avec revert ) + :wq
### Git commit --amend 
revient sur le dernier commit pour rajouter un élement (stagger le commit avant ) 


