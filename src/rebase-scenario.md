git rebase origin/{branch-name} # will use the latest commit in the repo

play this scenario:
create local branch, do some modif
on dev branch do some modifications
push to remote
on local branch
git rebase origin/develop
