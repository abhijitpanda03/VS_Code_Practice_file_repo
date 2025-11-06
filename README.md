# VS_Code_Practice_file_repo
Files will created for practice

Git offers a comprehensive set of commands for managing version control. Here are some of the most commonly used and essential Git commands, categorized by their primary function:

1. Setting up and Initializing Repositories:
git init: Initializes a new local Git repository in the current directory.
git clone <url>: Creates a local copy of a remote repository.
git config: Sets user-specific and repository-specific configuration options, such as username and email.

2. Staging and Committing Changes:
git status: Shows the status of the working directory and staged files. 
git add <file>: Adds a specific file to the staging area. 
git add . or git add -A: Adds all new and changed files to the staging area.
git commit -m "Commit message": Records staged changes to the repository with a descriptive message.
git diff: Shows unstaged changes in the working directory.
git diff --staged: Shows changes in the staging area compared to the last commit.

3. Branching and Merging:
git branch: Lists all local branches.
git branch <branch-name>: Creates a new local branch.
git checkout <branch-name>: Switches to a different branch.
git checkout -b <branch-name>: Creates a new branch and switches to it. 
git merge <branch-name>: Merges the specified branch into the current active branch.
git log: Displays the commit history.

4. Working with Remote Repositories:
git remote add <name> <url>: Adds a new remote repository.
git pull: Fetches changes from a remote repository and merges them into the current branch.
git push <remote> <branch>: Uploads local branch commits to a remote repository.

5. Undoing Changes and History Management:
git reset <file>: Unstages changes for a specific file.
git reset --hard <commit-hash>: Resets the current branch to a specific commit, discarding all subsequent changes.
git revert <commit-hash>: Creates a new commit that undoes the changes of a previous commit.
git stash: Temporarily saves changes that are not ready to be committed.
git stash pop: Applies the latest stashed changes and removes them from the stash list.

6. Advanced Commands:
git rebase: Rewrites commit history by moving or combining commits.
git reflog: Shows a log of all actions performed on the local repository.
git blame <file>: Shows who last modified each line of a file.
This list covers many of the most frequently used Git commands, but Git offers a much wider array of commands for more specialized tasks. You can use git help <command> to get detailed information about any specific Git command.