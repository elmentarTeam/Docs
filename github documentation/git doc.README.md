# Git doocumentation #

** git config ** - gives you all possible commands

** git config ** --global user.name ""
** git config ** --global user.email c@g.com 

** git config ** --list  - shows all settings

** git help **
** git <command> --help **
** git help config ** - help to specific command(config)

** git init ** - inisiallisaton of git in specific project

** git clone [url] ** - copy existing project to your repository. its build a grit package and put there an existing project. If you want another name for grit, just write url name/grit.git newname it will be an untracked file!!!

** git add [filename in your package] ** - lets changes to be commited

** git add . ** - save changes in the repository

** git status ** - shows your status 

** .[oa] ** - it will ignore all files that finish with 'oa'. And will not copy it to repository. It's good for dist package, bundle.js...

** git diff ** - to see what's you've change but still not indexed

** git commit ** - save all the chages you made. Be sure that before you made an "git add" command

** git commit ** -a - making index ad save the changes

** git rm ** - delete the index of file before the total delete (git commit)

** git mv readme.txt readme ** - renaming readme.txt to readme
 
** git commit --amend ** - cancel the last commit

** git init ** - inisiallisaton of git in specific project

** git clone [url] ** - copy existing project to your repository. its build a grit package and put there an existing project. If you want another name for grit, just write url name/grit.git newname it will be an untracked file!!!

** git add [filename in your package] ** - lets changes to be commited

** git add . ** - save changes in the repository

** git status ** - shows your status 

** .[oa] ** - it will ignore all files that finish with 'oa'. And will not copy it to repository. It's good for dist package, bundle.js...

** git diff ** - to see what's you've change but still not indexed

** git commit ** - save all the chages you made. Be sure that before you made an "git add" command

** git commit -a **- making index ad save the changes

** git rm ** - delete the index of file before the total delete (git commit)

** git mv readme.txt readme ** - renaming readme.txt to readme
 
** git commit --amend - ** cancel the last commit

** git reset HEAD filename  ** - cancel the indexsationof the file
 
** git remote ** - shows the deleted repositories
 
** git remote -v ** - shows the URL of deleted repository
 
** git remote add [name][URL] ** - return the deleted file
 
** git fetch [filename] ** - same shit, different name
 
** git pull ** - adds deleted branch to yours branch
 
** git tag  **   - shows all the 'tag tree'
** git tag -a **
 
** git config --global alias.ci commit ** -  from now you can write "git ci" and not "git commit"
 
** git branch testing ** - build the new branch named "testing"
 
** git checkout testing ** - pass to the new branch, named "testing"
 
** git checkout -b "branch name" ** - create a new branch and swiching on it
 
** git merge master ** - making update of commit info on the new branch and pass the changes to master. The new branch also points to master
 
** git branch -d [branch name] ** - delete a branch
 
** git branch ** - shows the names of existing branches. '*' symbol shows on witch branch you sitiing right now
 
**  git branch -v ** - shows the last commit on every branch
  
**  git branch --merged -  **      shows the branches that you've already merged with master
**  git branch --no-merged - **    -//- not merged
  
*  !!! If a branch not marged, you can't delete it with git branch -d and you can do it by the next command
  git branch -D *
  
**  git push [name of the server you sending] [branch name] ** - update the server brunch
  
 ** git push [name of the server you sending] [branch name]:[branch name] ** - same shit different name. You can give another name to the branch on the web server
  
**  git push [webserver name] [branch name] ** - delete branch from the webserver
  
**  git rebase --onto [main branch] [child branch] [grandson branch] **  - making marge to main branch from grandson branch
  
 