# Basic git commands

1. git init
2. git status
3. git add .
4. git add <FILE>
5. git commit -m "<COMMENT>"
6. git log --oneline 

--> get ID for each commit

7. git log 
--> more detailed log

8. git checkout <commit_ID> <FILE>

file will automatically be staged

9. git reset HEAD <FILE>

remove file from being staged (de-stage the file)

10. git checkout -- <FILE>

discard the changes for the file (do not track the file anymore, and revert to the HEAD)

11. git restore <FILE>

discard the changes for the file (do not track the file anymore, and revert to the HEAD)

12. git reset <FILE>

unstage a staged file, but leave working directory unchanged

13. git reset

reset the staging area to the last comit without disturbing the working directory


