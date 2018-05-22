# Git Reverts

Git revert or rollbacks are performed with two statements: **revert** and **reset**. I recommend using the former because the reset command will remove items from the history.  In this example however i will show you how to do both.  

![test](image/commits.png)

## Revert
In this sample there are 5 commits.  Note that the **commit id** is a 7 digit number.  for example `f271fa9`.  you can use this number to do reverts.  You can do the reverts one by one starting from last and moving down on list. 
You can also do ranges.

## Reset
Remember that when you **reset** you **loose changes!!**
```
git reset --hard 05e9f89
```
then you have to do a push force if git push fails. This happens because the way git is configured.
```
git push –force
```

## Example

1. do a revert to commit 3
1. this get you to 3 files and each should say commit 3.
1. do a reset to delete commit five which stores the restore commit.

