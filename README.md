Merge all these branches to the main branch using Pull Request.  
The workflow should be:  
1. Merge hotfix, bugfix, feature, documentation  
2. Always pull before pushing 
3. Use rebase while merging hotfix, three-way merge for bugfix and feature, squash merge for documentation. 

Commands for reference: 
a) git pull origin main [ -- (ff-only|no-rebase|rebase)] 
b) git merge|rebase --continue 
c) git merge|rebase --continue 

