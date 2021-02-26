# GitCommands

## The main commands of the Git

1. git : ensure that whether the git has been installed on your machine
2. clone : clone a repository from the gitub
   eg : clone https://github.com/ratheesh-ram/GitCommands.git
3. Status : this will shows the status of the git repository
4. git commit :
   1. git commit -a : commit all the changes in the file
      eg : git commit -a -m "Added git, clone, status, git commit commands to the text file"
5. git log : shows the logs of the repository in the local computer

   ➜ /d/GitTuto/gitcommands : (main)git remote
   origin

   ➜ /d/GitTuto/gitcommands : (main)git remote -v
   origin https://github.com/ratheesh-ram/GitCommands.git (fetch)
   origin https://github.com/ratheesh-ram/GitCommands.git (push)

   ➜ /d/GitTuto/gitcommands : (main)git push origin master

6. git push origin : origin is the name of the remote
7. git push origin master : push the changes to the remote server with in the master branch
