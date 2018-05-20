# Git Reverts

Git revert or rollbacks are performed with two statements: **revert** and **reset**. I recommend using the former because the reset command will remove items from the history.  In this example however i will show you how to do both.  

In this sample there are 5 commits.  

![test](image/commits.png)

## Example

1. do a revert to commit 3
1. this get you to 3 files and each should say commit 3.
1. do a reset to delete commit five which stores the restore commit.

