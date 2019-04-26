# :mag: Tutoriel Git Windows

## :lock: Pré-requis
- Installation de [Git](https://git-scm.com/downloads)
- Installation de [GitKraken](https://www.gitkraken.com/download)

## :file_folder: Création d'un dépôt Git local
Ouvrir votre invite de commande<br>
*Raccourci clavier* :
```bash
> Window + R
```

Ecrire "cmd" et taper sur la touche entrée<br>

- Pour un nouveau répertoire Windows
```bash
> mkdir votre_nom_de_dossier<br>
> cd votre_nom_de_dossier
```

- Pour un répertoire Windows déjà existant
```bash
> cd votre_nom_de_dossier
```

Initialisation de git dans votre dossier Windows
```bash
> git init
```

Commit vide pour initialiser notre projet
```bash
> git commit -m "Initial commit" --allow-empty
```

Ajout du premier tag de notre projet
```bash
> git tag -a v0.0.0 -m "Initial version"
```

Créer deux fichiers dans votre dossier Windows :
```bash
> touch .gitignore<br>
> touch README.md
```

**README** : Fichier explicatif du projet
**.gitignore** : Fichier qui liste les fichiers ignorés par le repo git

Ajout de deux fichiers sur votre repo git
```bash
> git add .gitignore<br>
> git commit -m "add .gitignore"

> git add README.md<br>
> git commit -m "add README"
```

Créer une branche
```bash
> git branch nom_de_la_branche
```

Basculement sur une branche 
```bash
> git checkout nom_de_la_branche
```

## :page_facing_up: Liste des commandes Git

Commandes | Explications
----------|-------------
git clone [url] | Cloner un projet
git init | Initialiser un projet
git add fichier1 | Ajouter les fichiers au prochain commit
git reset HEAD fichier | Enlever un fichier ajouter au commit (undo git add)
git status  | Status des fichiers
git diff | Visualiser ce qui a été modifié mais pas encore indexé
git commit | Enregistrer les modifications
git commit -m "message de commit" | Enregistrer sans passer par l'éditeur (ajout direct d'un commentaire)
git commit -a | Tout commit sans passer par add
git tag | Placer un tag sur un commit
git tag -a -m | Ajout de version et message au tag
git branch branch_name | Création branch
git branch -a | Lister les branches
git checkout dest_branch_name | changer de branch
