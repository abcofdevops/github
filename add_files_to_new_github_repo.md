## Add Files to new GitHub Repo

>Commands for local changes to send to a new repo in github

### Initialise git 
```bash
git init
```

### To check status
```bash
git status
git status -uall
```

### Add and commit changes 
``` bash
git add .
git commit -m "Initial commit"
``` 

### Create Repo in github and add remote in local
``` bash
git remote add origin https://github.com/abcofdevops/MERN-docker-compose.git
git remote -v
```

### Rename master → main
```bash
git branch -M main
git branch
```

### Setup user commit details and git Personal Access token 
```bash
git config --global user.name "abcofdevops"
git config --global user.email "abcofdevops@gmail.com"

git config --global credential.helper store
```

### Check status and Push
```bash
git status
git push -u origin main
```

> Issue: ! [rejected] main -> main (fetch first)
> 
> error: failed to push some refs to

### Pull and Rebase before Push
```bash
git pull origin main --rebase
git push -u origin main
```
