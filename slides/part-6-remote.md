# Remote

Parlons de dépôt *distant*


<img src="img/remote-0-master.png" class="as-is" />


<img src="img/remote-1-remote.png" class="as-is" />


## Héberger un dépôt distant ?
Github (Ou [BitBucket](https://bitbucket.org/))


## Ajouter une _remote_

```shell
$ git remote add origin git@github.com:<user>/<proj>.git
$ git remote -v
```


```shell
$ git push origin master
```
<img src="img/remote-2-push.png" class="as-is" />


## Récupérer les changements

```shell
$ git checkout master     # Aller sur la branche master
$ git status              # Est-ce propre? (Bien sûr!)
$ git pull origin master  # Récupérer le travail
                          # de l'équipe
```


## _Sync_
Terminologie de l'application GitHub