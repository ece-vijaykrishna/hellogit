Git commands
git command	                                                  What it does
git config –global user.name “vijaykrishna”	                  Set user name
git config – global user.email “abc@gmail.com”	              Sets user email
git config – global core.editor “’installation-location’”	    Sets editor 
git config –list	                                            To view configuration
	
git init	                                                    Initialize git directory
git remote add origin url	
git remote -v	                                                To check which remote origin Is configured
	
git branch -vv	                                              Lists all local branches
 git status	                                                  Shows status of branch Untracked files 
git add filename.fileextension	Adds file to the 
git add .	Adds all untracked files
git status	 Changes to be committed
git status –short	To see the status of the repository in a more compact way
Git log	To view the history of commits in the repository
git commit -m “commit message”	
Git commit -a -m “commit message here”	Commit the updated files directly, skipping the staging environment:
git push -u -f origin master	When you are pushing first time you need to use the force flag
-u -> track new remote branch
-f -> force our changes
git checkout -b branch_name base_branch_name	Switches to branch_name
git branch -vv	Shows the current branch
git checkout master	Switches to master branch
git checkout branch_name	Switches to a particular branch
git push	
git fetch –all	
Gti branch -r	Shows list of remote branches
git push -d origin 	
git fetch – all	Fetches newly added branches
git branch -r	Displays newly added branches
git push -d remotename  branchname	To delete branch
git branch -vv	Displays list of branch
git checkout -b branch_name	To create a new branch
git merge branch_name	To merge our branch with main branch
	
git log --oneline	Displays commit id
git revert commit_id	Reverts the work to the mentioned commit_id;
After giving revert push the changes ; so give git push
git stash	Changes that are not committed are stored in memory stash in form of stack
git stash list	Lists the number of stash
git stash apply	Applies last element in stack
git stash save	To stash –same as stash apply
git stash clear	Clears the stash
	
Git help --all	See all possible commands
Git command -help	See all available options for specific command
	
	
