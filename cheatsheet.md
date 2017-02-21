# Git Command Cheat Sheet

##### Cloning your remote directory
		git clone <remote directory>

##### Checking that status of your local repository - shows changed but not added files in red
		git status

##### Creating a new branch for you to work on
		git branch <new branch name>

##### See all branches in your remote repository
		git branch -a

##### Moving onto a branch
		git checkout <branch name>

##### Deleting a branch
		git branch -d <branch name>

##### Moving files while preserving git history
		git mv <source> <destination>


##### making a new branch whilst moving into it AT THE SAME TIME
		git checkout -b <new branch name>

##### you can clear the terminal
		clear

#### tell git to keep on eye on altered files NOT source
		git add <file name>

#### commit changes to master and include message #### if you don't write a message, press escape, type :wq then enter
		git commit -m 'add new message here although -m and message are nor necessary'
