# The-Lost-Treasure
GL01 Project

## Première Installation
### Installation de Git
Installer [Git](https://git-scm.com/download)

### Première configuration de Git
Créer un dossier The Lost Treasure dans **Documents**  
Ouvrir **Git Bash** puis entrer les commandes suivantes

```
cd Documents/'The Lost Treasure'
git init
git config --global user.email "votremail@exemplemail.com"
git conig --global user.email
```
> Si votre mail apparaît c'est bon

```
git remote add origin https://github.com/HFraise/The-Lost-Treasure*
*git pull origin master*
```
> Tous les fichiers sur le GitHub devrait apparaître dans votre dossier The Lost Treasure

## Envoyer un fichier sur GitHub
Ouvrir **Git Bash**
> Verifier si on se situe bien dans le dossier The Lost Treasure sinon entrer la commande cd Documents/'The Lost Treasure'

Avant d'envoyer un fichier il est nécéssaire de récupérer les nouveaux fichiers ou les fichiers mis à jour sur le GitHub.

```
git pull origin master
```
> Recupère tous les fichiers présent sur github

Puis pour envoyer un fichier, entrer les commandes suivantes

```
git add NOM_DU_FICHIER.EXTENSION
git commit -m "Commentaire sur la modification ou l'ajout"
git push origin master
```
