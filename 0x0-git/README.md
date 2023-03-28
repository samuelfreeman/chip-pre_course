git init: Initializes a new Git repository in the current directory.
Making Changes
git add [filename]: Adds a file or changes to the staging area.
git add .: Adds all changes in the current directory to the staging area.
git commit -m "Commit message": Commits the changes in the staging area with a message.
git commit -a: Commits all changes in tracked files.
Viewing Changes
git status: Displays the status of the repository, including which files are staged, unstaged, and untracked.
git log: Displays the commit history of the repository.
git diff: Shows the differences between the working directory and the last commit.
Branches
git branch: Lists all the branches in the repository.
git branch [branch-name]: Creates a new branch with the given name.
git checkout [branch-name]: Switches to the specified branch.
git merge [branch-name]: Merges the specified branch into the current branch.
Working with Remote Repositories
git remote add [remote-name] [remote-url]: Adds a new remote repository with the specified name and URL.
git remote -v: Lists all remote repositories and their URLs.
git push [remote-name] [branch-name]: Pushes changes to the specified branch in the remote repository.
git pull [remote-name] [branch-name]: Pulls changes from the specified branch in the remote repository.
Undoing Changes
git reset [filename]: Unstages a file from the staging area.
git reset --hard: Resets the repository to the last commit, discarding all changes.
git revert [commit-hash]: Reverts a commit by creating a new commit that undoes the changes made in the specified commit.
These are just a few of the many Git commands available. You can find a complete list of Git commands and their descriptions in the Git documentation.



