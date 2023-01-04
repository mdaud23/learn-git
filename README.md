# learn-git
Let's learn git

## Initializing
To initialize a folder (u r inside this folder)
```
git init
```
## Status
Check the status of your folder (what has been changed and committed)
```
git status
```
## Add
Add file(s) to be committed
```
git add <file_1> <file_2> ... <file_n>
```
## Commit
To commit git status and leave a message
```
git commit -m "<your message>"
```
## Integration
Connect your local git repo to github. There's no need for this action if you forked your folder from a repo
```
git remote add origin <url>
```
## Checking Branch
```
git branch
```

## Push
Push your current git status to github
```
git push -u origin <branch>
```
## Token
You can get token from ``Settings > Developer settings > Personal access tokens``
