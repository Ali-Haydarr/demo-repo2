# Pushing repository from localhost

## initialize git
git init<br/>
## check the status
git status<br/>
## track all files
git add .<br/>
## check status again - not necessary
git status<br/>
## commit
git commit -m "title" -m "description"<br/>
## before pushing to github, create an empty repository on github and copy the ssl connection string
create a new repository on github<br/>
get ssl connection string from github<br/>
## tell git where to push the repository
git remote add origin "ssl connection string goes here"<br/>
## check if origin is ok
git remote -v<br/>
## push the repository, if you add "-u", then you can just use "git push"
git push -u origin master<br/>
git push