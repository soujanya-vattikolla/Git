### Git:
Free and open source version control system.

### What is version control?
We can track down all the changes made, track the bugs. We can also go back to the previous version of code if required.

### Terms:
Directory: Folder <br>
Terminal or Command Line: Interface for Text Commands(create, update, install..) <br>
CLI: (Command Line Interface) <br>
cd: Change Directory <br>
Code Editor: Place to write code <br>
Repository: Project, place/folder where project is kept. <br>
GitHub: A website to host your repositories online. 

### Git Commands:
Clone: Bring a repository that is hosted somewhere like GitHub into a folder on your local machine. <br>
add: Track your files and changes in Git. <br>
commit: Save your files in Git. <br>
push: Upload Git commits to remote repo like GitHub <br>
pull: Download changes from remote repo to local machine

### In terminal command:
git clone <ssh> ## To clone the github repository to VS Code <br>
git status ## Show us all the files created,updated or deleted
git add . ## Track all the files listed (new files, updated files)
git commit -m "<message>" -m "<description>"

#### In order to use git push command, we need to create a SSH key
### Open Git Bash
ssh-keygen -t rsa -b 4096 -C "<github email address>"
## Enter a filename <testkey>
### To list the files : ls | grep testkey
cat <testkey.pub> 
To copy all the key : clip < ~/<testkey.pub>
## Go to Github--settings--SSH and GPG keys---New SSH Keys(here paste the key)
We can find a new key in SSH keys


 
                                              

