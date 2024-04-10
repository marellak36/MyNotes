git clone 
git checkout "branch"  --switch  
git checkout -b "" - new branch and then commit.
git branch -r (show remote branches)

**PUSH to remote repo**
git checkout "branch"
git add .
git commit -m ""
git push origin ""

git merge develop (merge a remote branch into your current branch(Devlop) to bring it up to date)

git rebase  -- apply any commits of current branch ahead of specified one

**GIT Rebase Master On Develop** 
Git reset “master commit”  “5541f22ecaad1b89448”
Git stash 
Git pull origin master
Git stash pop
Git add , commit 
Git push —force


**SAVE WORK and move to a new bug fix**
git stash  -- save working copy before moving to new copy
git stash pop -- put back saved copy
git stash drop

git cherrypick  [ Pick a specific commit and push to desired branch)


