# GitCommands

## The main commands of the Git

1. git : ensure that whether the git has been installed on your machine
2. clone : clone a repository from the gitub
   eg : clone https://github.com/ratheesh-ram/GitCommands.git
3. Status : this will shows the status of the git repository
4. git config --list : this command lists the configuration of the git
6. git commit :
   1. git commit -a : commit all the changes in the file
      eg : git commit -a -m "Added git, clone, status, git commit commands to the text file"
7. git log : shows the logs of the repository in the local computer

   ➜ /d/GitTuto/gitcommands : (main)git remote
   origin

   ➜ /d/GitTuto/gitcommands : (main)git remote -v
   origin https://github.com/ratheesh-ram/GitCommands.git (fetch)
   origin https://github.com/ratheesh-ram/GitCommands.git (push)

   ➜ /d/GitTuto/gitcommands : (main)git push origin master

8. git push origin : origin is the name of the remote
9. git push origin master : push the changes to the remote server with in the master branch
10. git stash (To save your un-committed changes in a "stash". Note: this removes changes from working tree!)
11. git stash pop

**\*\*\*\***\*\*\***\*\*\*\*** ADDING EXISTING DIRECTORY IN TO GIT **\*\***\*\***\*\***\*\***\*\***\*\***\*\***

1. git init : this command will make the current directory in to a git repository
2. git add <Filename> : this will add the file in to git Staging Area
3. git add . : this will add all the files to the staging area there in git detected an changes
4. git commit - m "message" this will commit the changes
5. since this is an new git repository in order to push the changes we need to add origin. for that login to github and create a new repository and do the following commands
   git branch -M main
   git remote add origin https://github.com/ratheesh-ram/WebpackConfig.git
   git push -u origin main
6. git pull origin main : this will pull all the changes which has been done by others to the current project and update it
7. git remote : shows the remote name associated with the git directory
8. git remote -v : shows details about remote
9. git branch -M main : this will add new branch main

## this is the latest some updation of git
