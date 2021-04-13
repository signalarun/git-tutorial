# Git tutorial


# Commands

 + Initialize Git repository  
   `git init` 
 + Stage  
   `git add .`
 + Status  
   `git status`
 + Commit  
   `git commit -m "my first commit"`
 + Log commit  
   `git log --oneline`
 + Checkout  
  `git checkout <commit number> readme.md`
 + Reset file
   - Unstage a staged file, leaving working directly unchanged  
   `git reset <file>`
 + Reset
   - Reset staging area to the last commit without disturbing the working directory  
   `git reset`
   
 + To configure your user name to be used by Git, type the following at the prompt:  
   - `git config --global user.name "Your Name"`
 + To configure your email to be used by Git, type the following at the prompt:
   - `git config --global user.email <your email address>` 
 + You can check your default Git global configuration, you can type the following at the prompt:
   - `git config --list`
 + To set up your local repository to link to your online Git repository
   - `git remote add origin <repository URL>`
 + To push the commits to the online repository
   - `git push -u origin master`
 + To clone an online repository to your computer
   - `git clone <repository URL>`
