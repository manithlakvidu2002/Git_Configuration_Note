     Config
####################
git --version
git config --global user.name "user_name"
git config --global user.email "email_address"
git config --list

git clone //url

git pull //url 	<---git hub eke project ekak update karnna

================================================================
     First time
####################
create a new repository on github
create a local repository 
shift + right click > git bash here

git init
git add .
git commit -m "test commit"
git remote add origin https://github.com/TheMIU/test.git  <--- copy from github new created repository
git push -u origin master

####################
    Save changes 
####################
git add .
git commit -m "test 2"
git push

####################
git status <-- check status
