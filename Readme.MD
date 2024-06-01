Git Command Basic


PC Configuration 
1. Set your username: git config --global user.name "FIRST_NAME LAST_NAME"  // github username
2. Set your email address: git config --global user.email "MY_NAME@example.com"  // Github account email

If already setup git in PC then  Go to cradintial manager >> windows Cradintial and then remove existing cradintial


* Adding new project on GIT

1. Login in the git 
2. go to Repesotory and Add New 
3. give Repository name >> Discription 
3. Select if the project is privet then select Privet // in privet project other can't copy or see your project without access
4. Normally projects are public
5. add a Readme.MD file then create 

* create a new repository on the command line
echo "# delete" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/nrzcse/delete.git
git push -u origin main
