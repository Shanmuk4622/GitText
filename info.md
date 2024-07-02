# Git Test
this is a pratics file for git, 
# to update a file in an exiting reposetery we use ,
add - commit - git push origin main

# but to upload / create a reposetory 
afer creating a directory to get the features of hit you have to use a command
git init, to verify ls -Force (you will see .git)
go to my github account and create same reposetory in the directory name
add - commit - git remote add origin <-link->
"<>" this meant nothing required
1. git init, (to make features like git ), for ls -Force
2. git remote add origin https://github.com/Shanmuk4622/GitText.git || or git branch -M main || git push -u origin main
3. git remote -v  (to verify remote)
4. git branch  (checking branch)
5. git branch -M main   (changing branch to main)
6. git push origin main , But before that make sure your files are upto date
"first time you use 
git pust -u origin main
from next time on wards you can use 
git push"
=> to do both add and commit in sigle time "git commit -am <messsage>" bot only if new fime not creeated 
anlways checkk status by "git status"   

# Branch Commands
branches are used in different ways, it is very useful features, more people can modify code simultaneously and can combined together.

git branch (to check breanch)
git branch -M main (to rename branch to main)<cumpulsury>
git checkout <-branch name-> (navigate t0 another branch)
git checkout -b <-new branch name -> (create new branch )
git branch -d <-branch name-> (to delete branch)
git push --set-upstream origin AdditionalFEatures, (to set upstream).