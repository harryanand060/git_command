## Git Commands

#### History: You can check the history of all command for your git bash
	command: history
	
#### Inialize the Git:
	command: git init
	
#### CHECK STATUS:
	command: git status
	
#### RESET THE CHANGE:
	command: git reset FILE_NAME

#### Set Upstream- It is variable you can set any name here. In Upstream you set the source location from where you want to PULL Repo
	command: git remote add upstream https://github.com/harryanand060/git_command

#### Set Origin: It is variable you can set any name here. In Upstream you set the destination location to where you want to Push changes
	command:  git remote add origin https://github.com/harryanand060/git_command

#### PULL Request: Pull the Repo from github or gitlab to your local repo
 	command: git pull upstream (It take the changes from Master Branch)
		 git pull upstream DEVELOPMENT_Branch (It take change from DEVELOPMENT_Branch)

#### ADD NEW CHANGES:
	command: git add .( for all items) or (give filename one by one)
	
#### COMMIT CHANGES:
	command: git commit -m MSG
	
#### PUSH CHANGES TO GIT:
	command: git push https://github.com/harryanand060/git_command/folder.git BRANCH_NAME
	
#### DELETE Specific Directory From Git
	command: git rm -r .idea//
	
#### CREATE NEW BRANCH
	command: git checkout -b BRANCH_NAME

#### SWITCH BRANCH:
	command: git checkout 

#### CHECK THE FILE DIFFERENCE:
	command: git diff
