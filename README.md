# practice_repo git assignment commands
1.Pull and Merge difference

- Make example of pull request and two branch merge event.

git init
git add .
git commit -m "added file"
git clone (url)
git checkout -b feature1
git push origin feature1
pull request and merge

2.Rebase

- Try to rebase feature branch with master branch

git checkout main
git pull origin main
git checkout feature1
git rebase main
git push --force origin feature1

3.Change commit message

- Commit push on commit in feature branch and then change commit message


git checkout feature1
git commit --amend -m "changes commit"
git push --force origin feature1

4.cherry pick

- Pick some commits from feature branch to master branch

git checkout main
git log
git cherrypick <commit-hash>
git push
  
5.Drop commit

- Remove some commit from feature branch.
  
git checkout feature1
git log --oneline
git reset --hard<commit hash>
git push --force origin feature1

