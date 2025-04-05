## Hello Git

'git remote add origin <repo_clone_url>' links the local project to a remote repository on Github.

'git branch <branch_name>' to create a new branch. 

'git checkout <branch_name>' to navigate to that branch.

'git branch <branch_name> <root_name>' to create a branch with the specified root.

An upstream branch is a remote branch that your local branch tracks. 'git push --set-upstream origin <branch_name>' pushes a local branch to the remote repository with the same root, it then sets the remote branch as the upstream branch which tracks changes from the local branch. After linking, you can just run 'git push' instead of the entire upstream command again.

If someone has made changes to your remote branch, to retrieve said changes, use the 'git pull' command.

A pull request lets you share your changes with your team.

# Standard workflow
1) Clone the repository.
2) Create a branch.
3) Push the branch to the remote repository.
4) Make your changes.
5) Push your changes
6) Create a pull request
7) Merge the changes
8) Pull changes to your local main branch.