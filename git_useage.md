### git command
git init
git remote add origin <GitHub rep URL>
git add .
git commit -m "comment"

git remote -v
git fetch origin

git push origin main
git pull origin <branch name>

git status
git log --oneline
git log --graph --oneline --all

### git branch
git checkout <new branch name>
git checkout -b <new branch name>

git branch -d <branch name>
git push origin --delete <branch name>

git branch     # list local branch
git branch -r  # list remote branch
git branch -m <new branch name>

### git reset
git reset <filename>
git reset --hard <commit ID>

git reset --soft HEAD~1   //
git reset --hard HEAD~1   //

git revert <commit ID>
git diff
