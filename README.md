# AMA

 git config --global user.name "AMA"
 git config --global user.email "AMA033@gmail.com"


git init


git remote add origin repoName
git branch -M main
git pull --rebase origin main
git push -u origin main


git add index.html
git restore --staged index.html
git add .
git restore --staged .

git clean -f
git restore .
git status

git log
git commit -m "creat header"