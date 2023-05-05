# Examen-GIT
Voici la réponse à l'examen git.

RIBEIRO THOMAS
3ESGI IW

## 1. A quoi sert un gestionnaire de versions ?

Réponse : 
- Conserver un historique
- Revenir en arrière en cas de problème
- Travailler à plusieurs
- Suivre les modifications de chaque fichier

## 2. Git est un gestionnaire de version décentralisé

Réponse : 
- Vrai

## 3. Quelle commande permet d'initialiser son projet dans Git Bash ?

Réponse :
- `git init`

## 4. Quelles sont les trois zones locales majeures dans Git ?

Réponse :
- Working directory
- L'index
- Le Repository

## 5. Vous avez créé votre dépôt distant sur GitHub, que l'on appellera monDepotDistant, et vous souhaitez le lier avec votre dépôt local sur Git. DEP représente le nom court qui sera utilisé pour appeler le dépôt. 
## Quelle ligne de commande devez-vous taper ?

Réponse : 
- `git remote add DEP https://github.com/xxxxxx/monDepotDistant`

## 6. Maintenant que votre dépôt distant est lié à votre dépôt local, vous allez devoir dupliquer son contenu en local. Pour ce faire, nous devons utiliser

Réponse :
- `git clone https://github.com/xxxxxx/monDepotDistant`

## 7. Je suis sur ma Branch1 et je viens d’ajouter un fichier "File2.txt". Je change d’avis : je veux finalement ajouter mon fichier à une nouvelle branche, "BranchFile". Que dois-je faire ?

Réponse : <br>
`git status` <br>
`git stash` <br>
`git branch BranchFile`<br>
`git checkout BranchFile`<br>
`git stash apply`

## 8. git commit --amend -m "Test"
## Cette commande permet de : 

Réponse : 
- Modifier le message du commit précédent

## 9. Quelle est la différence entre git revert et git reset?

Réponse :
- `git revert` crée un nouveau commit alors que `git reset`, non

## 10.Je souhaite savoir qui a touché à une ligne en particulier dans le fichier test.html. Quelle commande vais-je devoir exécuter ?

Réponse :
- `git blame`