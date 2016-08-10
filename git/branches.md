# Branches
## Create
Create the branch
```sh
$ git checkout -b <branch>
```
Push the branch to the remote (will be able to see on GitHub)
```sh
$ git push -u <remote> <branch>
```

## Delete
#### local
Delete local branch (will not affect GitHub)
```sh
$ git branch -D <branch>
```
#### remote
Deletes the branch from the remote (will no longer be on GitHub)
```sh
$ git push <remote> --delete <branch>
```
## Switch
```sh
$ git checkout <branch>
```
## View
#### local branches
```sh
$ git branch
```
#### all
```sh
$ git branch -a
```
