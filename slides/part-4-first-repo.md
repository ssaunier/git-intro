# Les bases

## Mon premier dépôt

```shell
$ git init
$ git status
$ git add
$ git diff
$ git commit
$ git log
```
note:
  Voici les commandes que nous allons apprendre


## Nouveau projet : Listes

<div class="fragment">
Créer l'espace de travail

```shell
$ cd
$ mkdir workspace
$ cd workspace
```

<div class="fragment">
Puis le dossier du nouveau projet

```shell
$ mkdir listes
$ cd listes
$ git init
```


## Nouveau fichier

Créer le fichier `courses.txt`

<div class="fragment">
```shell
$ git status
```

<div class="fragment">
```shell
$ git add courses.txt
$ git status
```

<div class="fragment">
```shell
$ git commit -m "Creation de la liste de courses"
$ git status
```

note:
    Pas besoin de serveur, pas besoin de connexion Internet


## Modification de fichier

Modifier le fichier `courses.txt`

<div class="fragment">
```shell
$ git status
```

<div class="fragment">
```shell
$ git diff courses.txt
```

<div class="fragment">
```shell
$ git add courses.txt
$ git status
```

<div class="fragment">
```shell
$ git commit -m "Ajout du beurre"
$ git status
```

<div class="fragment">
```shell
$ git log
```


## Que s'est-il passé ?


## Espace de travail

_working directory_

```shell
$ git status
  # Changes not staged for commit:
```


## Zone de transit

_index_ ou _staging area_

```shell
$ git status
  # Changes to be commited:
```


<img src="img/git-0-start.png" class="as-is" />


<img src="img/git-1-dirty.png" class="as-is" />


<img src="img/git-2-add.png" class="as-is" />


<img src="img/git-3-commit.png" class="as-is" />


## Et dans l'autre sens ?


<img src="img/git-1-dirty.png" class="as-is" />


<img src="img/git-4-checkout.png" class="as-is" />


<img src="img/git-2-add.png" class="as-is" />


<img src="img/git-5-reset.png" class="as-is" />


## Rinse and Repeat