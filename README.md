#OpenBrowserAfterPush

This hook should open browser just before you push your commits to a remote (while the page is loading the push request has finished). "pre-push" file should be added to .git/hooks/ dir in the root directory and its' permission should be set to "chmod +x".

###Todo:
+ It would be a good idea if you can check to which branch are you pushing. Sometimes you are on branch "x" but you're pushing to "y" - this script will open "x", but it should open "y"
+ Also it's gonna be awesome if you work with team (on forked project) so when you push, the script opens the page with view comparing yours code and the code on the repository that has been forked.
+ Change config value from "user.name" to "user.username" to be sure that the user will use git username and not the first and last name.

