# Git

## Git Tags
 - $ git tag reation
```sh
$ git tag <name-tag>
$ git tag -a <name-tag> -m <comment>
```
 - $ git check tags
```sh
$ git tag
$ git show <name-tag>
$ git tag -t <v1.*>
```
 - $ git push remote
```sh
$ git push origin <name-tag>
$ git push origin --tags //push all tags
```
 - $ git delete tag local
```sh
$ git tag -d <name-tag>
$ git tag --delete <name-tag>
$ git tag -d <name-tag> <name-tag>
```
 - $ git delete tag remote
```sh
$ git push origin -d <name-tag>
$ git push --delete <name-tag>
$ git push origin :v1.0
$ git push origin -d <name-tag> <name-tag>
```
 
