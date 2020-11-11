# Git Book by GitProcess
Git Book, Git References, Git Documentation

## Most used git commands

## git clone 
Clone a public repo <br/>
`git clone https://github.com/username/repo-name.git local-machine-folder-name`

## git init
Initialize or reinitialize a git repo <br/>
`git init`

## git add
Add / save all the changes in a repo <br/>
`git add --all`

## git config
Add your user-email and username before making a commit if not set yet <br/>
`git config --global user.email 'youremailhere'` <br/>
`git config --global user.name 'yournamehere'` <br/>

## git commit
Commit a change <br/>
`git commit` <br/>

Commit all the changes made in your repo with a message <br/>
`git commit -m 'your message'`

## git remote remove origin
Remove a remote origin from your local machine after cloning a repo from github <br/>
`git remote remove origin`

## git remote add origin 
Add a remote origin where you want push your codes from local machine <br/>
`git remote add origin https://github.com/username/repo-name.git`

## git push
Push your local code to github <br/>
`git push origin master`

Set upstream to master branch and push local codes together <br/>
`git push -u origin master`

When you set upstream once, you can use directly `git push` to push your code
`git push`

Force to push your current codes no matter whatever conflict it has <br/>
`git push -f origin master`


## git pull
Pull all the codes from github repo to your local machine on base branch <br/>
`git pull`

## git checkout
Move your cursor to one branch to another branch. <br/>

This will move your cursor to `local` branch. (here 'local' is a branch name, not your local machine) <br/>
`git checkout local` <br/>

Again this will move your cursor to `master` branch <br/>
`git checkout master`

If you don't have a `local` branch, this will create a 'local' branch and at the same time the cursor will move to that new branch <br/>
`git checkout -b local`

This will move your cursor to a specific commit back and set head there <br/>
`git checkout your_commit_reference_name_here`

## git log
Check recent commit history- get commit id, author, time and commit message
`git log`

## git reset
Reset your uncommitted but saved works. First save the file or close and reopen the file then use the command <br/>
`git reset --hard`
Then you can restore data from the github <br/>
`git pull`

## git restore
Restore your currently changed file <br/>
`git restore`

## git clean
Undo your uncommitted codes and delete new files and directory<br/>
`git clean --fd`
