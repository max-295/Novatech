## Reponses

### 1 
Comme les 2 même lignes ont étré modifiées, git ne peut merge automatiquement sous
peine de perdre une des deux versions.

### 2 - Mission 6
1er commit : 7341fb3
commit ajout contact : cc3605a (commit fait en 2 parties donc c'est le premier)
10 commits pour le moment.
Usage de git log --graph
git show 2b30b8e

### 3 - Mission 9
git reset --soft
ça ne conserve rien dans l'historique mais conserve le staging + modif


### 4 - Mission 10
git revert HEAD~1 -m "revert test affichage"
alors que
git reset HEAD~1 aurait tout supprimé

### 5 - Mission 11
git stash
puis git stash pop pour récupérer le travail