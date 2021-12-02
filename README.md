### To delete branch locally,
git branch -d branch_name

### To delete branch remotely,
git push origin --delete branch_name

### To remove a specific staged file(only added/staged, not committed) or unstage
git rm --cached file_name(with extension) <br>
or, <br>
git reset file_name(with extension)


### To remove all staged files (only added/staged, not committed) or unstage
git reset HEAD


