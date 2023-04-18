**Nom :** Antunes Celia        **Année :** 2023         **IUT Le Havre - Cours GIT**
**Groupe :** B1 équipe 08


# Compte-rendu TP1 Introduction GIT


### 1. Configuration de GIT

***

Dans ce TP, nous allons dans un premier temps configurer GIT, à l'aide de la commande **git config**. En ajoutant des paramètres de configuration, comme notre nom d'utilisateur et notre addresse mail, qui sont très important.

A partir ce ce moment la, plusieurs commande avec **git config** se suivent :

*' git config --global user.name "Celia Antunes"'
* **git config --global user.email antunes.celia2004@gmail.com**
* **git config --global core.editor "Visual Studio Code"**

### 2. Création d’un dépôt git sur une machine locale

***

Il faut maintenant créer un répertoire de travail dans **courseGIT**, créer les dossiers tp1, tp2, tp3...
Une fois dans le bon dossier, créer notre premier dépôt git avec la commande **git init**   
La commande **git status** permet de vérifier les modifications apportées aux fichiers.  

### 3. Création d’un fichier texte README.md

***

Nous procédons ensuite à la création de ce fichier au format *markdown*.   
Maintenant nous voyons grace à la commande **git status** que le fichier a été modifier, il faut donc le sélectionner, l'inclur dans le dépôt git avec les commandes respectives : 

* git add README.md
* **git commit -m "Ajoute du fichier README.md"**

Maintenant, le fichier README.md est synchronisé avec le dépôt. Nous venons d’enregistrer une première version du fichier.

### 4. Gestion de version d’un programme Java

***

Nous allons développer notre projet de Cryptomonnaie en java pour bien comprendre la gestion des fichiers.  
Nous avons donc complété les programmes .java qui étaient à notre disposition.  

Que nous avons du donc ajoutez et validez le fichier java au dépôt git, avec les mêmes commandes **git add Cryptommonaie**, **git commit -m "Première version du fichier Cyptomonnaie.java"**  

Nous créons aussi un fichier **.gitignore** pour placer nos .class, avec les commandes.  
* **touch .gitignore**

Puis ajouter et et valider **add** et **commit -m**.

***

*FIN DU TP1*