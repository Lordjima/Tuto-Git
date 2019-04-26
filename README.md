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
