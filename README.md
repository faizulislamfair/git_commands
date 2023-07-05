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

## To remove a specific staged file (only added/staged, not committed) or unstage
### git rm --cached file_name(with extension) <br>
or, <br>
### git reset file_name(with extension)

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

## To bring in changes from a specific commit from another branch and commit(same repository)
### git cherry-pick commit_id

<br>

## To bring in changes from a specific commit from another branch and only add but not commit(same repository)
### git cherry-pick commit_id -n

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

## To forcefully revert back to the state of the latest commit, discarding any local changes and disregarding any conflicts or warnings.
### git checkout HEAD~ --force

<br>
