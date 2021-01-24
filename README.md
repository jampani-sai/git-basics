Go to required directory and intialize git
# git init

Each file in working directory is either untracked or tracked
Tracked files can be unmodified, modified, or staged.

Adding the files to be tracked by git 
# git add <filename>

Check the status of the files
# git status # -s or --short for simplified output. 

The tracked and modified files should be added again to staged and commited.

To commit the changes done 
# git commit -m "<Summary of the changes>" # -a option to commit all changed files

Add the files or file patterns to be ignored in .gitignore file

To see the changes which are not yet staged
# git diff # --staged to compare with the staged changes to the last commit

If deleted a file in working directory, is should be deleted in git and then commit
# git rm <filename> # --cached to stop the file to be tracked
