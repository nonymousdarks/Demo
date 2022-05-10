`git init`
git add file
git commit -m "message"
git status
git diff file
git log
git log --pretty=oneline
git reset --hard HEAD^
git reset --hard commitId
git reflog
git diff HEAD -- file
git checkout -- file
git restore file
git reset HEAD file
git restore --staged
git rm file
ssh-keygen -t rsa -C "youremail@example.com"
git remote add origin git@github.com:yourname/yourrepository.git
git push -u origin master
git remote -v
git remote rm origin
git clone git@github.com:yourname/yourrepository.git
git checkout -b dev
git branch dev
git checkout dev
git branch
git merge dev
git branch -d dev
git switch -c dev
git switch dev
git log --graph --pretty=oneline --abbrev-commit
git merge --no-ff -m "merge with no-ff" dev

