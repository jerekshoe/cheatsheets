## Adding heroku to existing repository
```sh
heroku git:remote -a <app-name>
```

## Pushing to remote
### Push master branch
```sh
git push heroku master
```
### Push other branch
```sh
git push heroku <branchname>:master
```