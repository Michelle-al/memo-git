# memo-git

* Différence entre git et Github :
  - Git est utilisé pour créer un dépôt local et versionner les projets (dépôt local).
  - Github est un service en ligne qui héberge le dépôt (dépôt distant).

* Staging area :
  * Zone du dépot local où les fichiers modifiés sont en attente pour le prochain commit.
  
  
## Commandes

### Branches
- `git branch test` : créer la branch "test".
- `git branch`: liste les branches du projet.
- `git branch -d footer` : aller sur une autre branche que la branche footer et lancer la commande pour supprimer la branche locale.
- `git push origin -d footer` : aller sur une autre branche que la branche footer et lancer la commande pour supprimer la branche distante.
- `git checkout test` : aller sur la branche "test".

### Proposer une nouvelle version du projet à ses collègues
- `git add NomDuFichier` ou `git add .` : pour ajouter 1 ou tous les fichiers modifiés à la staging area.
 - `git commit -m "message du commit` : création d'une nouvelle version des fichiers.
 - `git push`: les modification son envoyée dans le dépôt distant (Github).

### Récupérer la version à jour d'un projet
- `git pull` : permet de fusionner la version du dépôt distant avec celle du dépôt locale sans modifier les fichiers présents en local.

### Revenir à une version antérieure du projet
- revenir sur un commit : `git reset commit`
- revenir sur un push : `git revert commit

## Créer un dépôt local (2 méthodes)
Créer un repository sur github ex "memo-git".

- 1ère méthode :
  * `git init` initialise le projet
  * `add README.md`
  * `commit -m "message du commit`
  * `git branch -M main`
  * `git remote add origin https://github.com/Michelle-al/memo-git.git` relier au dépôt distant
  * `git push u- origin main`
 
 - 2ème méthode :
  * `git clone https://github.com/Michelle-al/memo-git.git`
