# gitcommands

git remote add origin "url" 

git remote -v 

git branch -v -a 

git stash list 

git pull origin <master> 

git push –u origin <branchname> to seup the upstraem 

#to delete remote

git push origin –-delete <branchname> 

git push origin :<branchname>

git branch -D <branchname> ( deletes local branch) 

# push an empty commit to your branch to re-trigger status checks: 
git commit -m "retrigger checks" --allow-empty 
# and then 
git push <branchname> 
  
# moving changed files to another branch
git stash
git checkout correct-branch
git stash pop

#  Changing a commit message 
  git commit –amend 
  Then Changing the message of the most recently pushed commit
  git push –force 
  Note: https://docs.github.com/en/github/committing-changes-to-your-project/changing-a-commit-message 
# Renaming a gitlab branch and delete the original one
  git checkout branch
  
  git checkout -b branch_old
  
  git push --delete origin branch
  
  git push --set-upstream origin branch_old
