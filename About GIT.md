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
### Open Git Bash <br>
ssh-keygen -t rsa -b 4096 -C "<github email address>" <br>
## Enter a filename <testkey>  <br>
### To list the files : ls | grep testkey  <br>
cat <testkey.pub>  <br>
To copy all the key : clip < ~/<testkey.pub> <br>
## Go to Github--settings--SSH and GPG keys---New SSH Keys(here paste the key) <br>
We can find a new key in SSH keys <br>
## In the terminal: git push origin master <br>
 
#### To create a repo locally 
Step 1 : In terminal: move to the folder demorepo <br>
Step 2: Create a readme.md file <br>
Step 3: Make the demorepo as git file, go to terminal type: git init <br>
Step 4: git status <br>
Step 5: git add README.md <br>
Step 6: git status <br>
Step 7: git commit -m "<message>" -m "<description>" <br>
Step 8: Go to github create a new repoistory, copy the SSH key <br>
Step 9: Go to terminal: git remote add origin <paste the SSH key> <br>
Step 10: To check the repoistory: git remote -v <br>
Step 11: git push -u origin main <br>

### Git Branching
Master Branch: <br>
Feature Branch: <br>
Hot Fix Branch <br>
#### To know th branch we are working on:  <br>
 git branch  <br>
#### To create a new feature branch:  <br>
 git checkout -b <featurereadme> <br>
#### To switch between branches:  <br>
 git branch     <br>
 git checkout main  <br>
 or    <br>
 git branch  <br>
 git checkout <featurereadme>  <br>
#### To know the changes done  <br>
 git diff <featurereadme>   <br>
####   <br>
 git checkout <featurereadme>  <br>
 git status  <br>
 git push -u origin <featurereadme>  <br>
#### Merge both the branches   <br>
In github, click on compare and pull request and then merge the branches   <br>
#### Delete the feature branch   <br>
 git branch -d <featurereadme>   <br>
#### Undoing the changes    <br>
 git reset       <br>
 or        <br>
 git reset <README.md>    <br>
#### Undo the changes after commit  <br>
 git reset HEAD~1
 


 
                                              

