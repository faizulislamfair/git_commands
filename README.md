# Git Commands

<div align='center'>
<img alt="Git" width="300px" src="git.png" />
</div>

<br>

## To setup username globally
### git config --global user.name "username"

<br>

## To setup email globally
### git config --global user.email "email"

<br>

## To change username globally
### git config --global user.name "username"

<br>

## To change email globally
### git config --global user.email "email"

<br>

## To check if the setup is complete
### git config --list

<br>

## To exit the list 
### press 'q'(just q)

<br>

## To see the username
### git config user.name

<br>

## To see the email
### git config user.email

<br>

## To delete branch locally,
### git branch -D branch_name

<br>

## To delete branch remotely,
### git push origin --delete branch_name

<br>


## To download latest changes from a remote repository to local machine
### git fetch 

<br>

## To integrate changes from one branch into another
### git checkout branch_to_merge_into 
### git merge branch_to_merge_from 

<br>


## To download latest changes from a remote repository to local machine and integrate into current branch (git fetch + git merge)
### git pull

<br>


## To remove a specific staged file (only added/staged, not committed) or unstage
### git rm --cached file_name(with extension) <br>
or, <br>
### git reset file_name(with extension)

<br>



## To remove all unstaged changes and move head to specific point
### git reset commit_id

<br>

## To remove all staged and unstaged changes and move head to specific point
### git reset --hard commit_id

<br>

## To remove all staged files (only added/staged, not committed) or unstage
### git reset HEAD

<br>

## To remove all staged changes (even from files) and staged files(only added/staged, not committed) or unstage
### git reset --hard HEAD

<br>

## To exit from git log press 'q' (just q)

<br>

## To view all commits with ids in a clean way 
### git log --pretty=oneline

<br>

## To view all commits with ids in a clean way (shorter version)
### git log --oneline

<br>

## To display changes between a specific commit and current head
### git diff commit_id
 
<br> 

<!-- ### git revert sekha lagbe -->

<br>

## To abort merge after getting conflict message
### git merge --abort

<br>

<!-- ### git rebase sekha lagbe -->

<br>


## To not lose changes by not committing yet and moving to another branch to work on something
### git stash <br>
or, <br> 
### git stash -u <br>
and then to apply changes after coming back later <br>
### git stash apply index_number(0)

<br>

## To save stash with a custom message
### git stash push -m "message_name"

<br>

## To change name of most recent commit that hasn't been pushed to remote repo yet
### git commit --amend -m "new commit message"

<br>

## To change name of most recent commit that has been pushed to remote repo
### git commit --amend -m "new commit message"
### Plus
### git push --force

<br>

## To forcefully revert back to the state of the latest commit, discarding any local changes and disregarding any conflicts or warnings

### git checkout HEAD~ --force

<br>


## To move HEAD to a particular commit, push to repo and pull to master branch

### git checkout commit_id
### git add .
### git commit -m "commit message"
### git push origin HEAD:master --force
### Plus
### git checkout master
### git pull 

<br>


## To bring in changes from a specific commit 

## To bring in changes from one commit and commit directly in my branch

### git cherry-pick commit_id 


or, <br>


## To bring in changes from more than one commit and commit directly in my branch

### git cherry-pick commit_id_one commit_id_two 


## To bring in changes from one commit and without committing directly in my branch

### git cherry-pick commit_id -n

then commit, <br>

### git commit -m "commit_name"

<br>


## To undo changes introduced in a previous commit and commit
### git revert commit_id
### Plus
### :q (to exit)

<br>




