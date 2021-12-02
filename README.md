### To delete branch locally,
git branch -d branch_name

### To delete branch remotely,
git push origin --delete branch_name

### To remove a specific staged file (only added/staged, not committed) or unstage
git rm --cached file_name(with extension) <br>
or, <br>
git reset file_name(with extension)


### To remove all staged files (only added/staged, not committed) or unstage
git reset HEAD


### To remove all staged changes (even from files) and staged files(only added/staged, not committed) or unstage
git reset --hard HEAD


### To exit from git log press 'q' (just q)

### To view all commits with ids in a clean way 
git log --pretty==oneline


### To view all commits with ids in a clean way (shorter version)
git log --oneline


### To display changes between a specific commit and current head
git diff commit_id
 