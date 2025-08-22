# git exercises

## bundle 1 
### (Exercise 1)
```bush
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
git add filegit push origin ft/bundle-2
git add services.html
git push origin ft/bundle-2

git stash save "message"
git stash list 
git stash pop stash@{index}
git commit -m " "
git reset --hard 

## bundle 2 (Exercise 1)
git branch -M ft/bundle-2
git push origin ft/bundle-2
git add services.html
git commit -m " "
create a pull request from the github repository and add a person as a collaborator and then add them as a reveiwer.

## bundle 2 (Exercise 2)
git checkout main
git branch -M ft/service-redesign
git add service.html
git commit -m ""
git push origin ft/service-redesign
Using the link provided in the terminal create a pull request in your GitHub.
git checkout main 
git add .
git commit -m " "
git push 
git checkout ft/service-redesign
git diff main
git merge main
git commit -m " "
```