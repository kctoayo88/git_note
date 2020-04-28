# Git Introduction


## Overview

The simple introduction of git command.


## Command

### 1. Set user configuration
```
git config --global user.name "<user>"
```
e.g. git config --global user.name "kctoayo88"  


```
git config --global user.email "<email>"
```
e.g. git config --global user.name "kctoayo88@gmail.com"  
  

Using `git config --list` to check.  


### 2. Initialize git
```
cd <folder>  

git init
```


### 3. Submit changes
```
git add . (all files)  

git commit -m 'comment'  

git remote add <repo> <url>

git push
```

### 4. Branch
Beginning
```
git branch  (checking branch)
```
  
Create a new branch
```
git branch (-b) <branch name>  

git checkout <branch name> (chane HEAD to this branch)
```

Change the branch name
```
git branch -m <branch name> <new name>
```  

Delete the branch
```
git branch -d <branch name>
```
  
Merge branchs
```
git merge <branch name> (merge the designated branch to HEAD branch)
```

Remote the branch
```
git remote  

git push origin <branch name>
```

### 4. Tracking  
```
git status  (checking status)  

git log  
```


### 5. Clone (first time)
```
git clone <repo>
```


### 6. Update
```
git pull
```


## Reference

[1] [Git command introduction blog](https://ithelp.ithome.com.tw/users/20119923/ironman/2232)
