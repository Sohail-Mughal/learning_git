
# learning_git
all the commands should be executed inside git repository(containig . git directory)

1.  git init // to initilize a directory as git repository
//git debugging tools
2.  git remote -v //to list all the remote repository connected to your local
3.  git status   // list all the changes in local repository
4.  git branch  // list all the branches
//normal commands

note:always check before adding always check the status the it is staged or unstaged 
5.  git add file_name // file which is added or edited in local
6.  git commit -m "Message" // message represent what you have edited



note: always check before pushing the remote name and branch name
7.  git push -u remote_name branch_name // pushing first time
8.  git push remote_name branch_name // pushing normally
9.  gitk and gitg                   //GUI Tools
10. git remote add "remote_name" ssh_address_of_remote // it will add the ssh adress of remote or http, just after this command execute 1 command to chech wether the remote is added or not. 
11. git diff file_name             // to check the edited part isnide the file.
12. git add file_name             // to update what will be committed
13. git checkout file_name       // to discard changes in working directory
14. git commit -m "reason for commiting"  //

//creating a new branch from a point in the master branch, the commands will create a new branch having similar data as Master Branch
15. git branch "branch_name"    //creates a new branch with desires name
16. git checkout "branch_name" //switch to a new branch. one can check the data inside by ls command
17. git push remote_branch :"old_branch_name_to_be_deleted"  //deletes the branch with name written as old branch from remote
18. git branch -m "old_branch_name" "new_branch_name"  //renames the branch from old to new
19. git branch -d "branch_name"  //deletes the branch from local 
20. git checkout -b "branch_name"  //creates a new branches and switch to the current branch.	
