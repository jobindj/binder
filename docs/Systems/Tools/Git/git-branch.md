# `git branch`


## Change default branch name to `main`

1. Rename in local repo: `git branch -m master main`
2. Push to remote repo: `git push -u origin main`
3. Go to remote hosting platform (github/gitlab) and change the default branch to `main`
4. The `master` branch is usually protected. Remove this so that it can be deleted
5. Either delete `master` branch online or use `git push origin --delete master`

