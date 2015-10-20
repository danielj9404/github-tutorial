# GitHub Tutorial

by  _Daniel Jeronimo_ 

---
## Git vs. GitHub
Git is a version control which keeps _snapshots_ of the code and does not require github.   
Github can see the changes you make, stores code in the cloud and you can collaborate with anyone on files. 

---
##Initial Setup
1. To make a github account you have to make a username that you can remember and a password.
2. Then in order to link you github to nitrous, on the top right click on your profile icon and click on settings.
3. When you click setting, in the left side click on the _SSH keys_ and put add _SSH keys_.
4. When you pick a title put Nitrous.io then go to your nitrous account and in the _top right_ click your username and go to dashboard.
5. If your in dashboard click on _SSH keys tab_ and **copy/paste** your Nitrous.io _SSH key_ into github which should start with **ssh-rsa** and press add key.
6. Go to nitrous and click on the container tab, open **IDE** and type yes to confirm.
7. `git config` is used after you initialzed your directory and when you made your github account.
8. `git config` is for github to memorize who you are so in order to do that you have to type **git config -- global user.name "First Last"** name.
9. Also you do it for your email so you type **git config --global user.email "username@hstat.org"** both `git configs` help github memorize who it is and who you are so that way when you save your work in github it knows right away who it is.


---
## Repository Setup
Initialize 
In order to set up a repository follow these steps.  
1. Then put `git init` it initializes the directory and is only done once.  
2. Make a repository by typing `mkdir` which make a new repository, then type the name that you want to give that file so you can remember which file is which when trying to find a subject for a specific work.     
3. Then you type `cd (name of the file)`,`cd` makes you go inside the repository, type `pwd`, it helps you see in which file you are currently working on.    
4. After you finish your work or want to save it to github to save your work you put `git add README` which means you are adding changes to the repository.  
5. Then put `git commit -m "file name"` which saves the snapshots of your code to your remote of github.  
  
 


---
## Workflow & Commands
1. `Git status` is used when 
2. `Git add` is used when you want to add to your github remote repository like more detail in your files or change the code in your files. 
3. `git commit -m "README"` is used when you
4. `git push` is used when you made changes of your code in nitrous or c9.io and put them up in the "sky" which means that the work was saved into github and then you can see what changes you have done. 
