# Hello Git

## Standard workflow
1) Clone the repository by using 'git remote add origin -url-'

2) Create a branch using 'git branch -name-' and cd into it using 'git checkout -name-'

3) Push the branch to the remote repository using 'git push --set-upstream origin -name-'

4) Make your changes

5) Push your changes using 'git add .', 'git commit -m  '-message-', 'git push'

6) Create a pull request

7) Merge the changes

8) Pull changes to your local main branch using 'git pull'

## Handling merge conflicts
1) Merge changes from the main branch into the branch that you are currently in using 'git merge main'

2) Check out the versioning system on your editor to see merge conflicts

3) Figure out which lines of code you want to keep and apply changes

4) Repeat steps 5 to 8 of your standard workflow

## Soft, mixed and hard resets
Lets say we committed changes we want to discard. We can revert to an older commit by using 3 types of resets:

1) A soft reset reverts back to a commit hash and stages changes made after that commit hash, it can be done using 'git reset --soft -commit hash-'

2) A mixed reset reverts back to a commit hash but does not stage changes made after that commit hash, though those changes will still be present in your project. It can be done using 'git reset -commit hash-

3) A hard reset reverts back to a commit hash and discards all changes made after that commit hash, no staging and saving. It can be done using 'git reset --hard -commit hash-'