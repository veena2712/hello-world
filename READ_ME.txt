Basic commands related to the git

 
#heck the version of the git installed
git --version  

# these commnads to create repository in git 
git config --global user.name "Veena"
git config --global user.email "veenarmudhol@gmail.com" 

#initialize Git on that folder
git init 

#check the Git status and see if it is a part of our repo
git status

#As you are working, you may be adding, editing and removing files. But whenever you hit a milestone or finish a part of the work, you should add the files to a Staging Environment.
Staged files are files that are ready to be committed to the repository you are working on. can add it to the Staging Environment:
git add file_name.c

#add all files in the current directory to the Staging Environment:
git add --all
#The shorthand command for git add --all is git add -A

