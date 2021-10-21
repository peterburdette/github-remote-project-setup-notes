# How to Setup a New Project in GitHub within VS Code

All commands are executed in the terminal within the project foler.

### Initialize the connection:
```
git init
```
### Add the origin:
```
git remote add origin https://github.com/USERNAME/REPO-NAME.git
```
### Add files for initial commit:
```
git add .
```
### Perform the commit:
```
git commit -m 'first commit'
```
### Push the changes to the default branch:
(GitHub will use 'main' or 'master' as the default branch)
```
git push -u origin main
```

##### If the push does not work you may need to try the following:
```
git push --set-upstream origin main
```
or 
```
git push -f origin main (-f force pushes to the main branch)
```
