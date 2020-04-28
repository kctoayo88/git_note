# Git Introduction


## Overview

The simple introduction of git command.


## Command

1. Set user configuration
```
git config --global user.name "<user>"
```
e.g. git config --global user.name "kctoayo88"  


```
git config --global user.email "<email>"
```
e.g. git config --global user.name "kctoayo88@gmail.com"  
  

Using `git config --list` to check.  


2. Initialize git
```
cd <folder>  

git init
```


3. Submit changes
```
git add . (all files)  

git commit -m 'comment'  

git remote add <repo> <url>

git push

```

4. Branch
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

4. Tracking  
```
git status  (checking status)  

git log  

```


5. Clone (first time)
```
git clone <repo>
```


6. Update
```
git pull
``


## Reference

[1] Andreas ten Pas, Marcus Gualtieri, Kate Saenko, and Robert Platt. [**Grasp Pose Detection in Point 
Clouds**](http://arxiv.org/abs/1706.09911). The International Journal of Robotics Research, Vol 36, Issue 13-14, 
pp. 1455 - 1473. October 2017.

[2] Marcus Gualtieri, Andreas ten Pas, Kate Saenko, and Robert Platt. [**High precision grasp pose detection in dense 
clutter**](http://arxiv.org/abs/1603.01564). IROS 2016. 598-605.

[3] Andreas ten Pas. [**GPD**](https://github.com/atenpas/gpd)
