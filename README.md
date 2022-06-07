# Demo d'un projet git

## Présentation:
Ce projet est géré par git.

## Commande git
* Pour initialiser git dans un dossier:
```
git init
```

* Si c'est votre premier git sur ce pc:
```
git config --global user.name "<votre nom et prenom>"
```
```
git config --global user.email "<votre mail>"
```
* voir les changements depuis la derniere sauvegarde:
```
git status
```

* Ajouter les dernieres modifications du fichier `README.md`:
```
git add README.md
```

* Sauvegarder un commit:
```
git commit -m "<message du commit>"
```

* Ouvrir l'utilitaire `gitk`
```
gitk
```