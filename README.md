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
`git commit -m 'local update'`

## git remote remove origin
Remove a remote origin from your local machine after cloning a repo from github <br/>
`git remote remove origin`

## git remote add origin 
Add a remote origin where you can push your codes from local machine <br/>
`git remote add origin https://github.com/username/repo-name.git`

## git push
Push your local code to github <br/>
`git push origin master`

Set upstream to master branch and push local codes together <br/>
`git push -u origin master`


## git pull
Pull all the codes from github repo to your local machine on base branch <br/>
`git pull`
