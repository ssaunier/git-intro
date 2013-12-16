# Branches

Expérimentez en toute sécurité


<img src="img/branch-0-master.png" class="as-is" />


## Une branche = Une fonctionnalité


```shell
$ git checkout -b noel
```
<img src="img/branch-1-checkout-b.png" class="as-is" />


## Naviguation

Lister les branches
```shell
$ git branch
```

Se positionner dans une branche
```shell
$ git checkout <branch_name>
```


```shell
$ git commit
```
<img src="img/branch-2-commit.png" class="as-is" />


## Fusion
### En anglais, _merge_


```shell
$ git checkout master
$ git merge noel
```
<img src="img/branch-3-merge.png" class="as-is" />


## Nettoyage


```shell
$ git branch -d noel
```
<img src="img/branch-4-br-d.png" class="as-is" />