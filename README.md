# Git-Github
git remote add origin https://github.com/repo.git
git push origin master
git push -f origin master

git branch --delete <branchname>

git branch -a
git checkout master
git branch -m main

1)   touch filename.extension      --to create a file 
2)   mkdir foldername                  --  to create a folder 
      2.1)  cd foldername               --   to enter a folder
3)    git init                                    --    to create a git in your working directory
4)    git clone URL                        --     to pull a repository from the cloud 
5)    git status                               --     to check the changes in your file or to check the    current status
6)    pwd                                       --     to check the  directory currently you are working 
7)   ”git add -all” or “git add -A”     - to stage your root folder
        7.1)  ” git add . ”                   -- to stage changes in your folder you are currently staying
        7.2)   git add *                      -- to stage changes  all the files except the deleted one
        7.3)   git add *.extension      -- to stage changes of all the files of the specific extension 
8)   git reset                                  -- to unstage your changes in your files
9)   git commit -m”write something here”      --to commit your staged changes
10) git reset HEAD~                                      -- to unstage your committed changes
11)  git reset -hard                                        - almost same to the “git reset” but it also gives you the deleted files
12)  git rm filename.extension                       -- to delete and stage the changes in your file
     12.1) git rm filename.extension f             - to delete the file forcefully which hasn’t been staged
      12.2) git rm --cached filename.extension    --to stage the changes and not to  delete the                     file from working directory  
      12.2)git rm -r folder                                 ( google it)  


Branch
13) git branch                              ---to check the current branch
14)git branch branch-name         -- to create a new branch
15)git checkout branchName      -- to switch to a branch
16) git merge branchName -m”write something”         --to merge your branch with another branch
17)   ls                                           --to see the list of your files   

Git push, fetch, pull
18)   git push origin branchName          
19)   git fetch
20)   git pull
