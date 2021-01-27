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
