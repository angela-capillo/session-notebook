# Creating a new remote repository on GitHub

1. Open GitHub and click on the "Repositories" tab
2. Click on the "New" button and create a new repository
3. Select owner and choose a repository name
4. Choose whether you want the repository to be public and if you want to add a README file
5. Click create repository

## Connecting the newly created repository with your local one

Copy the SSH repository address and add it as the remote repository to the local repository (a repository can be linked to multiple remote repositories, so you need to give them nicknames to distinguish them; "origin" is the standard name for the main remote repository): git remote add origin <ssh link>
Check if the remote repository was successfully linked with the command: git remote -v
A "fetch" and a "push" address should be printed to the terminal
