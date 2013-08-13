OpenBrowserAfterPush
#########
This hook should open browser just before you push your commits to origin remote (while the page is loading the push request has finished). "pre-push" file should be added to .git/hooks/ dir in the root directory and its' permission should be set to "chmod +x".

Todo:
For now the script only opens the repo situated with origin remote and the branch you're currently working on (not the one you're pushing to)