# git exercises

## bundle 1 (Exercise 1)
git init
git branch -M main
git add .
git status
git commit -m "inital commit"
git remote add origin <--remote-->
git push -u origin main
git branch dev
git push origin dev
git branch
git checkout dev
git branch -M test
git branch -d test
git push origin --delete test


## bundle 1 (Exercise 2)
git add file
git stash save "message"
git stash list 
git stash pop stash@{index}
git commit -m " "
git reset --hard 

## bundle 2 (Exercise 1)
git branch -M ft/bundle-2
git branch
git add services.html
git push origin ft/bundle-2
git checkout maingit 
git pull origin main
git merge ft/bundle-2
git push -u origin main