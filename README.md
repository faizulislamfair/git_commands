### To delete branch locally,
## git branch -D branch_name


### To delete branch remotely,
## git push origin --delete branch_name


### To remove a specific staged file (only added/staged, not committed) or unstage
## git rm --cached file_name(with extension) <br>
or, <br>
## git reset file_name(with extension)


### To remove all staged files (only added/staged, not committed) or unstage
## git reset HEAD


### To remove all staged changes (even from files) and staged files(only added/staged, not committed) or unstage
## git reset --hard HEAD


### To exit from git log press 'q' (just q)

### To view all commits with ids in a clean way 
## git log --pretty=oneline


### To view all commits with ids in a clean way (shorter version)
## git log --oneline


### To display changes between a specific commit and current head
## git diff commit_id
 

### git revert sekha lagbe


### To abort merge after getting conflict message
## git merge --abort


### git rebase sekha lagbe


### To bring in changes from a specific commit from another branch and commit(same repository)
## git cherry-pick commit_id


### To bring in changes from a specific commit from another branch and only add but not commit(same repository)
## git cherry-pick commit_id -n


### To not lose changes by not committing yet and moving to another branch to work on something
## git stash <br>
or, <br> 
## git stash -u <br>
and then to apply changes after coming back later <br>
## git stash apply index_number(0)


### To save stash with a custom message
## git stash push -m "message_name"


