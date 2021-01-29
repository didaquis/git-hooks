# prepare-commit-msg
Automatically add branch name and branch description to every commit message except merge commit.

# Instructions of use:
* Open terminal and go to your repository `cd name-of-your-repository`
* Create the hook file `nano -w .git/hooks/prepare-commit-msg` (if something goes wrong, make sure the "hooks" directory exists and you have permissions on it)
* Copy-paste the content of "prepare-commit-msg" file on your hook file
* Set execution permissions `chmod +x .git/hooks/prepare-commit-msg` (step not require on Windows computer)

