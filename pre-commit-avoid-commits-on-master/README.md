# pre-commit
A simple hook for Git that prevents commits on the "master" branch

# Instructions of use:
* Open terminal and go to your repository `cd name-of-your-repository`
* Create the hook file `nano -w .git/hooks/pre-commit` (if something goes wrong, make sure the "hooks" directory exists and you have permissions on it)
* Copy-paste the content of "pre-commit" file on your hook file
* Set execution permissions `chmod +x .git/hooks/pre-commit`
* Follow these instructions for each computer and repository

## Tip:
If you also want to avoid commits to "develop" branch, replace this line `if [ "$branch" = "master" ]; then` with this one `if [ "$branch" = "master" ] || [ "$branch" = "develop" ]; then` 
