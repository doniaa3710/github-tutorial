# GitHub Tutorial

_Donia Abdelhalim_

---
## Git vs. GitHub
##### The difference between **Git vs. GitHub**:  
**Git** keeps snapshots/files of your code as a checkpoint of where you are. Having different versions would be useful because you may mess up your code, and you would be able to go back to the any version. Git can also be known as a version control while **Github** would be the host for the repository. This means that the code will be stored. 

_ALSO_:  
**Git** does not require Github, but **GitHub** reguired Git.   
**Github** visually tracks changes, makes collaboration on files easy and most importantly, stores code in the cloud.


---
## Initial Setup

To create a **Github Account** you would start by:  
* Type www.Github.com into the URL or click on [Github](https://github.com/) to be directed 
* On the top right hand corner you will see an icon **Sign in or Sign up**  
* Click **Sign up** or **log on** if you already have an account
* Start by creating your personal account, make sure to include your username, a reachable email and password
* After continuting, click on the continue button again after picking the plan you would like to continue with. 

#### **REMEMBER TO READ ALL DIRECTIONS**  
* To enhance your experience with GitHub, answer a quick survey question as to who you are and submit your results. Don't worry you won't be graded on your experience!
* Make sure you  **Read the Guide** if you are a new user or not!  

**NOTE**: you will be directed to a new tab explaining the basic fundementals and power of GitHub

After reading the guidelines, you can head back to the previous tab and **start a project.**    
**You may be asked to confirm your email**  

How to make a repo:  
1. `cd ~/workspace`
2. `mkdir filename` - makes the directory
3. `cd filename` - goes into your file 
4. `git init` - initalizes git in the directory  

**SSH key:** stands for secure shell and establishes a secure connection between your computer and GitHub




---
## Repository Setup

Init: Initializes git in the repository  
_First add and commit_  
1. `touch README.md`  - create a file 
2. Open `READMe.md`
3. Add text
4. `git add .` - adds the file to the stage

**New repo:**  
1. Go to **Github.com**
2. Create repository  
 
**Remote: Now your remote is on github**

---
## Workflow & Commands

`git status`: command to see which files have been edited since the last commit  
`git add`: add the file to the stage to be committed  
`git commit`: takes a 'snapshot' of the files on the stage. The message should be present-tense and describe what was modified in this snapshot  
`git push`: push the committed file back up to the remote

---
## Rolling Back Changes   
To undo any mistakes:   
Undo edit: after you've made ab edit, you can undo it using `git checkout -- filename`  
Undo add: after you've added a change, you can undo it using `git reset HEAD filename`  
Undo commit: after you've made a commit, undo it using `git reset --soft HEAD~1` or `git reset HEAD~1`
Undo push: after you've pushed to the remote undo it using `git reset --hard HEAD~1`