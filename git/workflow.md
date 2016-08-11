### Make sure you are on the main development branch by using the following command:
```sh
$ git checkout develop-branch
```
### Make sure you pull the latest changes on the remote development branch by using the command:
```sh
$ git pull [origin] develop-branch
```
### If you have a current branch you are working on the use the command.
```sh
$ git checkout your-local-branch
```
### If you don’t have a branch you working on and want to create a new branch use the command:
```sh
$ git checkout –b your-new-local-branch
```
### Make sure you sync your current branch with the development branch by using the command:
```sh
$ git rebase develop-branch
```
### If you have any conflict then resolve it then use the command
```sh
$ git rebase –continue
```
### After finishing changing your files type the following command to get a list of changes you made:
```sh
$ git status
```
### Add all the files you have changed using the command:
```sh
$ git add file-name
```
### Once you added all the files you should commit your changes using the command:
```sh
$ git commit –a –m ‘commit message’
```
### If you are using review code process then you will need to post the difference between your local branch and the
development branch using the following command:
```sh
$ git diff development-branch > filename.diff
```
## After you get an approval to merge your code then redo the steps 1,2,3,5 and (6 if needed because of conflict).
### Move to development branch using the command:
```sh
$ git checkout development-branch
```
### Merge your code using the command:
```sh
$ git commit - -no-ff your-local-branch-name
```
### Push all your changes to remote using the command:
```sh
$ git push origin development-branch
```
