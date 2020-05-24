#### To change a folder/directory/file name:
1. Create a folder in desktop
2. Navigate to the local folder through CMD
3. type `git clone ***clone link of the repo***`
4. the above command has cloned the whole repo in your machine
5. now to rename use the command `git mv old_filename new_filename`
6. the above command is a move command which automatically created a new folder while moving contents of the old folder to the new one
7. we need to check if we are in the master branch so type `git branch`. Doing this will show the branch that you are working in.
8. now we need to verify whether the changes we did during _line #5_ were reflected or not. So type `git status`
9. the above command will show all the changes you did
10. now its time for commitments. command `git commit -m "Rename file"`
11. now push. command: `git push origin master`
### done
