Git Command Basic


PC Configuration 
1. Download Git 
2. Set your username: git config --global user.name "FIRST_NAME LAST_NAME"  // github username
3. Set your email address: git config --global user.email "MY_NAME@example.com"  // Github account email

If already setup git in PC then  Go to cradintial manager >> windows Cradintial and then remove existing cradintial


* Adding new project on GIT

1. Login in the git 
2. go to Repesotory and Add New 
3. give Repository name >> Discription 
3. Select if the project is privet then select Privet // in privet project other can't copy or see your project without access
4. Normally projects are public
5. add a Readme.MD file then create 

* create a new repository on the command line

1. git init
2. git add README.md
3. git commit -m "first commit"
4. git branch -M main
5. git remote add origin https://github.com/nrzcse/git-command.git
6. git push -u origin main

* Push an existing repository from the command line
1. git remote add origin https://github.com/nrzcse/delete.git
2. git branch -M main
3. git push -u origin main


* Clone  a project from github

1. git clone https://github.com/nrzcse/git_basic.git // gitlab project link 
2. Then in your PC there willbe  a  project named Reponame where you can add new file 

* Git pushing project on Git

1. git add --all 
2. git commit -m "commit name"
3. git push 

* Git Branching 

1. $ git checkout -b branch-name
Switched to a new branch "branch-name"
2. git add --all 
3. git commit -m "commit name"
4. git push 


* Marge Project in master/ main 
1. git checkout master/name
2. git merge branch-name