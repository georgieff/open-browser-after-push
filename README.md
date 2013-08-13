###OpenBrowserAfterPush

This hook should open browser just before you push your commits to a remote (while the page is loading the push request has finished). "pre-push" file should be added to .git/hooks/ dir in the root directory and its' permission should be set to "chmod +x".

#Todo:
It would be a good idea if you can check to which branch are you pushing. Sometimes you are on branch "x" but you're pushing to "y" - this script will open "x", but it should open "y"