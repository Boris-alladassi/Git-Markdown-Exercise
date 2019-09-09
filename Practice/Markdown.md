# MARKDOWN PRACTICE
1. Hello World

## Tables

| Types | Description |
| ------ | ----------- |
| Dog person  | social, outgoing |
| Cat person| open-minded, independent |

## Git/Github Tips
>stage, commit, push, pull

>staging area is like the pet store, once you bring a pet home you're commited

>be careful with the command: **git rm -rf**

>always pull newest changes:

>**git pull origin master** will pull changes from the origin remote, master branch and merge them to the local checked-out branch.

>**git pull origin/master** will pull changes from the locally stored branch origin/master and merge that to the local checked-out branch. The origin/master branch is essentially a "cached copy" of what was last pulled from origin, which is why it's called a remote branch in git parlance. This might be somewhat confusing.

>You can see what branches are available with git branch and **git branch -r** to see the "remote branches".

*Repositories*

1. $git init [Name]: Creating new local repository

2. $git clone [url]: Downloading from remote repository

*Make Changes*

1. $git status: list all recent modified files to be committed
2. $git diff: Shows file differences not yet staged
3. $git add .: snapshots the file in preparation for versioning stage 
4. $git commit -m:"Informative and descriptive commit message": records file snapshots permanently in version history 
5. $touch [file]:creating a file in local repository
6. $git add [file.md]: stage file
7. $git commit [file.md]: brings up vim and type in commit message
8. $git commit -am: stage and commit at the same time


*Synchronize Changes*

1. $git merge [bookmark]/[branch]: combine bookmarks branch into current local branch
2. $git push: upload all local branch commit to github
3. $git pull: downloads bookmark history and incorporates changes
