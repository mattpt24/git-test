GIT HELP
--------------------------

git add .                                    - Adds all files to 'staging' area ready for commit
git add "file-name"                          - Adds a specific file to 'staging' area for commit
git commit -m "Message"                      - Commits changes
git push origin "branch-name"                - Pushes commit to a remote repo branch of your choice
git pull                                     - Pulls in the latest version of the repo to your local version 
git log / git log --oneline                  - Shows Commit History
git checkout "commit iD"                     - Goes to that version
git checkout "branch-name"                   - Goes to that branch
git checkout -b "branch-name"                - Creates new branch and automatically places you there
git branch                                   - Displays all branches *green one is one you're on
git branch -D "name of branch"               - Destroys branch (cant be on it when run)
git stash                                    - Stash changes for later allows you to not have to commit


If reverting back to old commit HEAD will detach (Meaning no longer on a branch and instead on a specific commit)
TO FIX - Create a branch new branch and begin working from this new branch going forward.


***
the "" are just to highlight them as placeholder. 
Dont use "" accept with git commit -m "Comment here"
