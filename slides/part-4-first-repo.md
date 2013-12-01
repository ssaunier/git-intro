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


## Nouveau projet : Listes

```shell
$ mkdir -p ~/workspace && cd $_
```

```shell
$ mkdir listes
$ cd listes
$ git init
```


## Nouveau fichier

Créer le fichier `courses.txt`

```shell
$ git status
```

```shell
$ git add courses.txt
$ git status
```

```shell
$ git commit -m "Creation de la liste de courses"
$ git status
```

note:
    Pas besoin de serveur, pas besoin de connexion Internet


## Modification de fichier

Modifier le fichier `courses.txt`

```shell
$ git status
```

```shell
$ git diff courses.txt
```

```shell
$ git add courses.txt
$ git status
```

```shell
$ git commit -m "Ajout du beurre"
$ git status
```

```shell
$ git log
```