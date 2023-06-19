# LearnGit
LearnGit
//clone the repo into local mashine
git clone https://github.com/Guenbay/LearnGit.git


//checking the pulled repo and file on local mashine in gitbash
ls -la 
//or
ls

//to see what the log looks like for the repo
git log

//Readme file editing in gitbash console
vim README.md
>i for insert mode
This is a new Line from new test
>ESC to get back
>:wq to write and exit

//to check status
git status

//to restore the staged state
git restore --staged README.md

//to check again if the restore is done
git status 

//want to restore file back
git restore README.md

//also checking the status as in line 28-29
//now adding the new lines to modified file
git add README.md

//check with git status that there is a commit request
//to do so do as followed

git commit 
//or also possible for example
git commit -m "My First Commit from local mashine"

//check the origin to fetch and push
git remote 
//or
git remote -v

//check status to get "Your branch is ahead of 'origin/main' by 1 commit."
//if you can read above you now able to push the new file you modifed back 
//you modifed back to Server / GitHub
git push origin master

//file is now pushed in Repository at GitHub and modifications are updated
