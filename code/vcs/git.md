# Gkb.1
## Git
### ? How to push existing Project to remote --bare repo
This example is pretty bland.
**On server:**  
1.`mkdir my_project.git`  
2.`cd my_project.git`  
3.`git --bare init`  
**On client:**  
1.`mkdir my_project`  
2.`cd my_project`  
3.`touch .gitignore`    
4.`git init`  
5.`git add .`  
6.`git commit -m "Initial commit"`  
7.`git remote add origin youruser@yourserver.com:/path/to/my_project.git`  
8.`git push --set-upstream origin master`

### ? How do you do this on various IDEs...
**Android Studio:**
**On server:**  
1.`mkdir my_project.git`  
2.`cd my_project.git`  
3.`git --bare init`
**On client:**  
1. New Project ([Android Doc][http://developer.android.com/training/basics/firstapp/creating-project.html])
2. VCS > Git >
