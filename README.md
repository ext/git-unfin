# git-unfin

Similar to stash but with real commits. Helps when you frequently use different machines and want to move unfinished commits around.

## Usage

Save all changes:

    git unfin [MESSAGE..]

Save everything (including untracked, but not ignored):

    git unfin --all [MESSAGE..]

Restore unfinshed commit back to working copy:

    git unfin --reset
