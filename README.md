# Git command

Github is a company that lets you host your file using git.

# command to set username and email
    git config --global user.name Aditya 
    git config --global user.email aditya@gmail.com
# command to get username and email
    git config --global user.name
    git config --global user.email

when you create a working directory first you have to run  below command inside that folder:

     git init
This command will create .git folder inside working directory and this folder contains ```index``` file which keep all the stage log and  ```object``` folder which contains all the commit logs
    
    git add filename   ||   git add ./
    git commit -m "message"
    
# To check the status
    git status

# Unstage 

    git reset HEAD -- filename
    
    
# To get git commit log
    git log
  
Branch is a pointer to pointing to last commit id.

# command to create new branch
    git branch branch_name
# command to switch to new branch
    git checkout branch_name
# Fast Forward Merge    
 Merge: Incorporating the changes of one branch to another branch.
 
 If ```dev``` is commit ahead from ```master``` and you want merge ```dev``` in ```master``` then first checkout to ```master``` then run command: ```git merge dev```

# Command to delete a branch
    git branch -d branch_name


# Link
 https://onedrive.live.com/view.aspx?resid=9CA786A045148134!387&ithint=file%2cpptx&authkey=!APNPMmwu5OB4u3Y
    
 
