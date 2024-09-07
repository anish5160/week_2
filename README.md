# Week 2 DevOps
1. Create a New Branch Called feature-x from the main Branch and Switch to It
   git checkout main              # Switch to the main branch
   git pull origin main           # Get the latest changes from the remote repository
   git checkout -b feature-x      # Create a new branch called feature-x and switch to it

2. Update Your feature-x Branch with the Latest Changes from the main Branch
   git fetch origin               # Fetch the latest changes from the remote repository
   git checkout feature-x         # Switch to your feature-x branch
   git merge origin/main          # Merge the latest changes from the main branch into feature-x

3. Resolve Conflicts in index.js and Mark the File as Resolved
   After resolving conflicts manually in index.js:
   git add index.js               # Stage the resolved file
   git commit                     # Complete the merge and commit the changes
4. See a List of All Branches, Including Remote Branches
   git branch -a                  # List all local and remote branches
5. Rebase Your feature-x Branch onto main to Maintain a Linear History
   git checkout feature-x         # Switch to your feature-x branch
   git fetch origin               # Fetch the latest changes from the remote repository
   git rebase origin/main         # Rebase feature-x onto the latest main branch
6. Squash Your Commits into a Single Commit Before Merging Back into main
   git rebase -i origin/main      # Start an interactive rebase onto the main branch
   # In the editor that opens, mark all commits except the first as 'squash' (or 's')
   # Save and close the editor to squash the commits into one
7. Push the feature-x Branch to the Remote Repository, Making It Available for Others
   git push origin feature-x      # Push the feature-x branch to the remote repository
I have done all this steps practically as you can see the branches section in the repository.
Also I will attach some screenshots.




