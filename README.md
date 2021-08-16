# gitcommands

git remote add origin "url" 

git remote -v 

git branch -v -a 

git stash list 

git pull origin <master> 

git push –u origin <branchname> to seup the upstraem 

git push origin –-delete <branchname> 

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
