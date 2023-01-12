# GitPractical

## 1. Pull and Merge difference
Pull : If we pull any branch or file in our local repository from any remote repository, the branch or file will be fetched as well as merge to the branch according to our need.

Command : git push -u origin feature1

Merge : When we merge any feature branch to master branch all the commits in the feature branch will reflect in the master branch.

Command : git merge feature1

## 2. Rebase

Command : git rebase feature2

## 3. Change commit message

Command : git commit --amend -m "Changed the commit message."

## 4. Cherry pick

Command : git cherry-pick 6caca58

## 5. Drop commit

Command : git reset --hard HEAD~1

