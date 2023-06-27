# Mastering-Git
This file contains the most frequently used git commands.With this file , I think you will learn how to :
- be familiar with git commands.
- create your own reop from your local (PC).
- clone a repo and modify it.
- pull changes from github.
- push chages to remote reop origin.
- create your own branch and deal with it. 
- stash files.
- give alias to git commands.
- git configuration.
- create your public key.
- learn how to delete a commit using head.

## Push & Pull Commands
- clone the repo
```
  git clone <repo linke from github
```
         
          
- To see changes (step by step)
  ```
  git status
  ```            
          
- add files (staging)
  ```
   git add <filename>
  ```
          
- commit changes
  ```
  git commit -m "commit description"
  ```  
          
- get the branch_name
   ```
  git branch
   ```
          
- get the remot_name
  ```
  git remote -v
  ```
          
- puhs the commits
  ```
  git push <remote_name (origin)> <branch_name (main)>
  ```            
          
- pull commits (remote->local)
  ```
  git pull origin
  ```
          
- initialize directory as a repo
  ```
  git init
  ```             
          
- push to remote
  ```
  git remote add origin git@github.com:handle/repo_name.git
  ```
          
- pull then push repo from your local to remote
  ```
  git push -u origin main
  ```
