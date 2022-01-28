#How to squash all commits in single commit
git branch backup
git pull
git rebase origin/master
git rebase --abort(if it fails)
git reset origin/master
git status
git add src
git status
git commit
git diff backup
git push --force
